# Pest Control Pros

Website for Pest Control Pros, specializing in pest control.

## Files included

- 14 pages in the root folder (`404.html`, `about.html`, `ant-control.html`, `cockroach-control.html`, `contact.html`, `general-pest-control.html`, `index.html`, `locations.html`, `pest-control-downtown-corona.html`, `pest-control-south-corona.html`, `privacy-policy.html`, `rodent-control.html`, `services.html`, `spider-control.html`)
- `blog/` - 2 pages
- `assets/` - stylesheet, scripts and images
- `.htaccess`
- `_redirects`
- `netlify.toml`
- `robots.txt`
- `sitemap.xml`
- `vercel.json`

## Setup

1. Upload everything in this folder to your web host
2. Keep the files in the site's root directory
3. **Shared/cPanel hosting:** make sure `.htaccess` uploaded too. It starts with a
   dot, so file managers hide it by default — turn on "show hidden files" and
   confirm it sits next to `index.html`. Without it every page except the
   homepage returns 404.
4. Open the site and check the pages, links and contact details

## Update notes

- All internal links now use real file names (`about.html`, `blog/index.html` ...), so the site also works when opened straight from a folder.
- Canonical URLs, schema and `sitemap.xml` use the same `.html` URLs. The server config files no longer redirect `.html` URLs.
- Buttons are parrot green; extra call buttons (mobile call bar, call strips, footer button) added.
- Social icons stay hidden until you replace the `#` links in the footer with your real profile URLs.

Generated with RankLocal.