# Denver Post Site Launch Checklist
A checklist of miscellaneous tasks to do before launching a public site. 

## Usage
Make a new GitHub issue in your project called "Final Checklist" and copy/paste the following:


```
## Web Search Indexing
* [ ] If you have a staging site, tell the search engine robots not to index you with a robots.txt
* [ ] If you are launching on a custom domain, make sure you allow indexing when you are ready to launch.

## Google Analytics
* [ ] Add DFM's GA Tracking Code (***add link to boilerplate snippet here***)
* [ ] Email DFM's analytics team to get their edits on our GA implementation

## Sharing & Rich Snippets
- [ ] Set up general meta tags
 * `<meta name=“description”>`
 * `<meta name=“author”>`
- [ ] Set up Facebook meta tags & validate [here](https://developers.facebook.com/tools/debug/)
 * `<meta property=“og:site_name”>`
 * `<meta property=“og:title”>`
 * `<meta property=“og:type”>`
 * `<meta property=“og:description”>`
 * `<meta property=“og:url”>`
 * `<meta property=“og:image”>`
- [ ] Set up Twitter meta tags & validate [here](https://cards-dev.twitter.com/validator)
 * `<meta name=“twitter:card”>`
 * `<meta name=“twitter:site”>`
 * `<meta name=“twitter:creator”>`
 * `<meta name=“twitter:description”>` (note that this needs to be under 200 characters)
 * `<meta name=“twitter:title”>`
 * `<meta name=“twitter:url”>`
 * `<meta name=“twitter:image:src”>`

## Mobile Friendliness
Test on various mobile devices:
- [ ] scrolling is easy
- [ ] nav bar works
- [ ] hoverable things are tappable
- [ ] charts/maps look ok

## Advertising
Make sure there's at least one ad on the page.

## Page Speed
- [ ] run the site through https://developers.google.com/speed/pagespeed/insights/

## Miscellaneous Polish
- [ ] If on custom domain, add favicon
- [ ] If on custom domain, add 404 & 500 error pages

## Load Testing
If your site relies on a database or server-side code, it should use caching and be load tested. If it's a static HTML or Jekyll site, you can skip this section.

- [ ] set up page [caching](https://en.wikipedia.org/wiki/Web_cache)
- [ ] write a script to load test all your pages. [Here's a good example from Illinois Sunshine](https://github.com/datamade/illinois-sunshine/blob/master/cache_builder.py)

## GitHub Readme
If the site is open source, make sure the Readme.md is complete and accurate. 

Here's a few good examples:

- [Geomancer](https://github.com/associatedpress/geomancer/blob/master/README.md)
- [Illinois Sunshine](https://github.com/datamade/illinois-sunshine/blob/master/README.md)

The Readme should have the following sections:

- [ ] Overview
- [ ] Setup
- [ ] Running locally
- [ ] Team
- [ ] Errors / Bugs 
- [ ] Pull Requests
- [ ] Copyright and License
```
