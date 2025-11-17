---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Building a Simple Blog"
author: Kate Wang
description: "Turning this site into a basic blog for my CSE 134B homework."
pubDate: 2025-11-17
---

Today I focused on turning the site into a real blog. I created a dedicated
`blog.astro` page and added a small list of posts that link to their own pages.
Even though the blog is simple, it fits perfectly with what the assignment is
looking for: reusable layouts, clean organization, and pages generated from
Markdown files.

To build the blog page, I followed these main steps:

1. **Created a blog index page** (`blog.astro`) that displays an introduction and a list of all posts.
2. **Added individual post pages** using Markdown files, each with its own layout and metadata.
3. **Set up a reusable PostLayout**, so every post automatically gets the same structure and styling.
4. **Linked everything together**, making sure the navigation menu and routing were consistent.
5. **Styled the post list**, giving each post a small “card” layout to make the page look cleaner.

Astro made this process surprisingly clean. Because layouts handle most of the structure,
I could focus more on content and styling rather than repeating code everywhere.

The site now has a homepage, an about page, and this blog section — and everything feels
much more like an actual website instead of just separate files. My next step is to
polish the layout and maybe try adding a small interactive feature.