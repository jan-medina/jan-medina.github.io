---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## How to use this page

This section is intentionally simple:

{% if author.googlescholar %}
- 🔎 **Google Scholar:** full publication and citation profile.
{% endif %}
- 📄 **This page:** selected publications with direct links and recommended citation text.
- 🧭 **Quick review for recruiters:** each entry highlights venue, year, abstract preview, and paper link.

## Selected Publications

{% include base_path %}

{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}

## Why this matters for industry roles

- Strong foundation in **formal modeling and statistical reasoning**.
- Proven ability to convert theory into **implementable algorithms**.
- Cross-domain experience spanning **mathematics, software, and scientific applications**.

If you'd like, I can share a concise walkthrough of how this research translates into modern AI/platform engineering decisions in production environments.
