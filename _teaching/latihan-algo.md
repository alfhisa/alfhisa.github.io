---
title: "Latihan Responsi Algo"
collection: teaching
type: "Undergraduate course"
permalink: /teaching/latihan-algo
venue: "BINUS University, School of Computer Science"
date: 2026-01-07
location: "Jakarta, Indonesia"
---

COMP6100001 - Software Engineering | This course provides a comprehensive examination of the principles, methodologies, and tools necessary for the structured development, deployment, and maintenance of high-quality software systems. Aimed at aspiring software engineers, it connects theoretical foundations with practical applications, equipping students to address real-world challenges in the software industry. The course is relevant to Object-Oriented Software Engineering and Advanced Topics in Software Engineering.

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