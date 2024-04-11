---
layout: page
title: 2005 - 2024 考研英语真题
---

<ul>
    {% for exam in site.exams %}
        {% if exam.title != page.title %}
        <li>
            <a href="{{ exam.url }}">{{ exam.title }}</a>
        </li>
        {% endif %}
    {% endfor %}
</ul>
