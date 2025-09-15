---
layout: default
title: Home
---

## About

These are class notes I took while living abroad.

## Lessons

<ul>
    {% assign sorted_lessons = site.lessons | sort: "week" %}
    {% for lesson in sorted_lessons %}
        <li>
            <a href="{{ lesson.url | relative_url }}">Week {{ lesson.week }}</a>
        </li>
    {% endfor %}
</ul>
