# DONGSANSUNJAE.github.io

Personal homepage for **Howon Chung**  
Undergraduate Student, Department of Electrical and Electronic Engineering, Yonsei University

Theme adapted from [Hyungjoo Chae](https://hyungjoo-homepage.netlify.app/) /
[Seungone Kim](https://seungonekim.github.io/) (Jekyll + Skeleton).

Site: https://dongsansunjae.github.io

## Edit

| What | File |
|------|------|
| Name, email, links | `_data/main_info.yaml` |
| About / News / Education | `index.html` |
| Vitae timeline | `_data/experience.yaml` |
| Publications | `_data/publications.yaml` |
| Profile photo | `assets/profile-pics/profile.png` |

## Preview locally

```bash
# Option A: GitHub Pages / Jekyll
bundle exec jekyll serve

# Option B: quick static peek (Liquid won't render)
python3 -m http.server 8000
```

## Deploy

Push to `main`. GitHub Pages will build the Jekyll site automatically
(Settings → Pages → Source: Deploy from a branch → `main` / root).
