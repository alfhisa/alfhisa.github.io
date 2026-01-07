---
title: "Responsi UAS Algoritmh & Programming"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/responsi-uas-algo
venue: "BINUS University, School of Computer Science"
date: 2026-01-07
location: "Jakarta, Indonesia"
---

COMP6047001 - Algorithm and Programming | This page provides a curated set of practice problems for UAS preparation in the Algorithm and Programming course. The exercises focus on core algorithmic concepts and C programming fundamentals commonly assessed in the final examination.

## Topics
Daftar Soal
{% assign soal = site.teaching | where_exp:"p","p.permalink contains '/teaching/contoh-soal/'" %}

<ul>
{% for s in soal %}
  <li>
    <a href="{{ s.url }}">{{ s.title }}</a>
  </li>
{% endfor %}
</ul>