# Lametti Lab Website

Speech, Language, and Communication Lab at Acadia University.

## Local Development

1. Install Ruby and Bundler
2. Run `bundle install`
3. Run `bundle exec jekyll serve`
4. Visit `http://localhost:4000`

## Deployment

This site is hosted on GitHub Pages. Push to the `main` branch to deploy.

## Custom Domain

To use `www.lamettilab.com`:
1. Add a `CNAME` file with `www.lamettilab.com`
2. Configure DNS at your domain registrar:
   - Add a CNAME record: `www` → `yourusername.github.io`
   - Or add A records pointing to GitHub Pages IPs
