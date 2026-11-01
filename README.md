# Junteng Liu — Academic Homepage

Personal academic homepage of **Junteng Liu**, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (a fork of [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/)) and hosted on GitHub Pages.

Live site: <https://spaldingpitzenur80664.github.io/LJT-Homepage/>

## Content

- **About** (site root): research interests, academic background, research experience, skills, publications, and contact information.
- **Publications**: first-author and co-authored publications, also listed in the About section.

Personal information is taken exclusively from the supplied personal records; publication details are kept in `_publications/` and the site-wide author information lives in `_config.yml`.

## Building and deploying

The GitHub Actions workflow in `.github/workflows/jekyll.yml` builds the site with Jekyll and deploys it to GitHub Pages on pushes to `master`.

To build and preview locally:

```bash
bundle install
bundle exec jekyll serve
```

The site-wide configuration is `_config.yml`; the header links are defined in `_data/navigation.yml`.
