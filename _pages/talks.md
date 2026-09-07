---
layout: page
title: Talks and Presentations
permalink: /talks/
description:
nav: false
nav-order: b
---

{%- comment -%}
Single source of truth: the "Talks and Presentations" section of _pages/about.md.
Edit the list THERE; this page re-renders it at build time. The extraction takes
everything after the section heading, up to the next heading or HTML comment.
{%- endcomment -%}
{%- capture about_raw -%}{% include_relative about.md %}{%- endcapture -%}
{{ about_raw | split: "##### **Talks and Presentations**" | last | split: "<!--" | first | split: "#####" | first | markdownify }}
