---
title: Notulen rapat
---

# Notulen rapat

Satu halaman per rapat, terbaru di atas.

{% assign rapat = site.pages | where_exp: "p", "p.dir == '/notulen/'" | where_exp: "p", "p.name != 'index.md'" | sort: "name" | reverse %}
{% for p in rapat %}
- [{{ p.title | default: p.name }}]({{ p.url | relative_url }})
{% endfor %}

[Kembali ke Tata Kelola](../)
