---
title: "Responsi Algorithm & Programming"
collection: teaching
permalink: /teaching/responsi-algo
order: 1
---

Halaman ini berisi **kumpulan contoh soal dan latihan responsi**
untuk mata kuliah **Algorithm and Programming**.

Silakan gunakan soal-soal berikut untuk:
- Persiapan responsi UAS
- Latihan Online Judge

---

## Daftar Contoh Soal
{% assign soal = site.teaching | where_exp:"p","p.permalink contains '/teaching/contoh-soal/'" %}

<ul>
{% for s in soal %}
  <li>
    <a href="{{ s.url }}">{{ s.title }}</a>
  </li>
{% endfor %}
</ul>
