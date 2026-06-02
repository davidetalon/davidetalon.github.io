# Academic Personal Site

A vibe-coded small, Markdown-first personal site designed for GitHub Pages.

## Update your information

Edit the front matter at the top of `index.md` to change your name (`author_name`), role, institution, email address, and profile image.

Edit the Markdown content files in `_includes/content/`:

- `about.md` for your biography and research interests
- `news.md` for announcements
- `publications.md` for papers and links
- `teaching-service.md` for courses and community work
- `more.md` for a CV link, profiles, and additional interests

Replace `assets/images/profile-placeholder.jpg` with a headshot using the same filename, or update `profile_image` in `index.md`.

## Publish on GitHub Pages

1. Push this repository to GitHub.
2. In the repository settings, open **Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder, then save.

GitHub Pages builds Jekyll and Markdown automatically. Your site will appear at `https://USERNAME.github.io/REPOSITORY/`, or at `https://USERNAME.github.io/` when the repository is named `USERNAME.github.io`.
The homepage uses relative asset paths, so either address works without adjusting the configuration.

## Preview locally

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.
