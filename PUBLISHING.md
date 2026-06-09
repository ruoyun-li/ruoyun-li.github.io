# Publishing your website

Your site is fully built and committed locally in this folder, with the GitHub
remote already set to `https://github.com/ruoyun-li/ruoyun-li.github.io.git`.
You just need to push it and turn on GitHub Pages.

## 1. Push the site to GitHub

Open Terminal, then run:

```bash
cd ~/Desktop/"personal website"
git push -u origin main
```

If the repository on GitHub already has files (e.g. a README created when you
made the repo) and the push is rejected, run this once to overwrite it with
your new site, then push normally afterward:

```bash
git push -u origin main --force
```

**Authentication:** when prompted for a password, use a GitHub
**Personal Access Token** (not your account password):
GitHub → Settings → Developer settings → Personal access tokens →
Tokens (classic) → Generate new token → check the `repo` scope → copy the token
and paste it as the password.

## 2. Turn on GitHub Pages

1. Go to `https://github.com/ruoyun-li/ruoyun-li.github.io`
2. **Settings** → **Pages**
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**
4. Branch: **main**, folder: **/ (root)** → **Save**

Wait 1–2 minutes for the first build. Your site will be live at:

### https://ruoyun-li.github.io

## 3. Making changes later

Edit the files (see below), then:

```bash
git add -A
git commit -m "Update site"
git push
```

GitHub rebuilds the site automatically within a minute or two.

## What to edit

| To change… | Edit this file |
|---|---|
| Home page text (intro, About Me, Education) | `_pages/about.md` |
| Your name, bio, email, social links, site URL | `_config.yml` |
| Top navigation menu | `_data/navigation.yml` |
| Profile photo | replace `images/profile.png` |

## Notes

- Your original photos and documents are kept in the `_source/` folder. It is
  git-ignored, so it stays on your computer and is **not** published.
- Social/academic links (Google Scholar, ORCID, LinkedIn, etc.) are left blank
  in `_config.yml` — fill them in to make the sidebar icons appear.
