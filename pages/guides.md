---
layout: default
title: Guides & Resources
permalink: /pages/guides/
---

# Guides & Resources

Your central hub for alliance strategy, coordination, and key systems.

---

## 🔥 Core Guides

{% assign guides = site.pages | where_exp: "page", "page.path contains 'pages/guides_data/'" | sort: "title" %}

{% for guide in guides %}
### 👉 [{{ guide.title }}]({{ site.baseurl }}{{ guide.url }})

{{ guide.description }}

---
{% endfor %}

📖 *More guides will be added over time.*
