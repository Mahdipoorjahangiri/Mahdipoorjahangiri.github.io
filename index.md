---
layout: page
title: Home
nav_order: 1
permalink: /
---

<div style="display: flex; align-items: center; gap: 1.5rem; flex-wrap: wrap;">

  <img src="/assets/img/HeadShot.jpg" alt="Mahdi Poor Jahangiri" width="160" style="border-radius: 5%; flex-shrink: 0;" />

  <div>

  <h2>👋 Hi, I'm Mahdi Poor Jahangiri</h2>
  <p><strong>Aspiring Data Lover</strong></p>
  <p>🌱 Exploring tech, data science, AI and Personal Growth</p>
  <p>🛠️ Learning by doing, sharing what I learn</p>
  <p>📍 Iran / Tehran | Fluent in Persian & English</p>
  <p>
    <a href="https://github.com/Mahdipoorjahangiri">GitHub</a> •
    <a href="https://linkedin.com/in/mahdi-poorjahangiri">LinkedIn</a> •
    <a href="https://t.me/mahdi_poorjahangiri">Telegram</a>
  </p>

  </div>

</div>

---

## 🧠 About Me

I’m a computer science student with a deep curiosity for tech, data, and AI,
currently learning Python, data science tools & concepts.  
This website is my public learning journal.

---

## 💼 Work Experience 

- **Data Scientist Intern** – [tamironline](https://tamironline.com/) (Apr 2025–Present)

---

## 📚 Education

- 🎓 B.Sc. in Computer Science — Islamic Azad University, Central Tehran Branch *(in progress)*

---

## 🔧 Skills (Growing List)

| Skill         | Level         |
|---------------|---------------|
| Python        | ⭐⭐⭐✰✰   |
| Git & GitHub  | ⭐⭐✰✰✰    |
| SQL           | ⭐⭐✰✰✰    |
| Jupyter       | ⭐⭐⭐✰✰   |
| Pandas/Numpy  | ⭐⭐⭐✰✰   |
| Scikit-learn  | ⭐⭐✰✰✰    |
| PowerBI       | ⭐⭐✰✰✰    |
| Tableau       | ⭐⭐✰✰✰    |
| Linux         | ⭐⭐✰✰✰    |

> ⚠️ Learning is on Progress - this an is envolving journey

---

## Latest Posts
{% for post in site.posts limit:3 %}
- **{{ post.title }}**  
  <small>{{ post.date | date: "%b %d, %Y" }}</small>  
  {{ post.excerpt | strip_html | truncatewords: 15 }}
{% endfor %}
[View all posts](/posts)
---

Thanks for visiting!  
Feel free to connect, follow, or just say hi 👋
