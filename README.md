# Zoho Mail Helpdesk Website

A responsive static help-centre project for GitHub Pages.

## Publish on GitHub Pages
1. Extract this ZIP.
2. Upload the contents of `zoho-mail-helpdesk/` to the root of your GitHub repository.
3. In repository Settings → Pages, select deployment from the `main` branch and `/ (root)`.
4. Wait for GitHub Pages to publish the site.

## Edit content in one place
Open `config.js`. It controls site branding, navigation, category labels, article titles, descriptions, categories, card images, and each article URL. Update an article's `url` to point to a replacement published page. Keep `slug` aligned with the matching file under `articles/` when you want to rename the local article page.

## Article content
The `articles/` directory contains 100 standalone HTML article pages. Each page includes a full guide of approximately 1,200–1,300 words, related-article links, metadata, and a login call-to-action. The content is general guidance; product menus and plan availability may change, so verify current steps in the official Zoho product interface.

## URLs and indexing
`robots.txt` allows crawling and `sitemap.xml` lists the homepage, guide library, and all 100 article pages. After publishing, submit `https://us-zohomail-knowledgebase.github.io/sitemap.xml` in Google Search Console.

## Important identity note
This is an independent help resource and is not affiliated with Zoho Corporation. The login call-to-action points to Zoho's official login page; change it only to a destination you own or are authorized to use, and label it transparently.
