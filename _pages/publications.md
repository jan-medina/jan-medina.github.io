---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Research Snapshot

My publications reflect a blend of **applied mathematics, network science, algorithmic modeling, and computational biology** that complements my current work in scalable AI and data systems.
{: .text-justify}

{% if author.googlescholar %}
- 🔎 **Google Scholar (full citation profile):** <a href="{{author.googlescholar}}">{{author.googlescholar}}</a>
{% endif %}
- 📄 **This page:** curated list with direct publication links and recommended citations.
- 🤝 **For recruiters/hiring managers:** these publications demonstrate depth in quantitative reasoning, model design, and end-to-end technical execution.

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
