---
layout: ../../layouts/MarkdownPostLayout.astro
title: "Working with Layouts"
author: Kate Wang
description: "Experimenting with BaseLayout and making pages feel consistent."
pubDate: 2025-11-16
---

For this part of the assignment, I focused on how Astro layouts work. I created a `BaseLayout.astro` file that includes the page structure: header, footer, and an `<h1>` for the page title.

What I like most is the `<slot />` feature. Instead of repeating the same HTML on every page, the layout manages all the structure while each page just adds the content. This keeps the navigation consistent across the entire site, and I can update the design by changing just one file.

This was also the first time I passed variables from a page into a layout. It made the site feel much more organized compared to writing everything directly in HTML.