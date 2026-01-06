# Customize checklist (quick)
1) Replace placeholder email + avatar:
   - `_config.yml` -> `author.email`
   - `_data/authors.yml` -> `email`, `picture.path`, `social.github`, etc.
   - Put an avatar at `assets/img/avatar.jpg`

2) Update project images:
   - Add images under `assets/img/projects/`
   - Update each file in `_projects/` to point to the right image

3) Optional: change accent image/color:
   - `_config.yml` -> `accent_image`, `accent_color`, `theme_color`

4) Deploy:
   - Commit changes, push to GitHub, enable GitHub Pages (build from /root on main).
   - Keep `CNAME` = `floognoodle.com` if using the custom domain.
