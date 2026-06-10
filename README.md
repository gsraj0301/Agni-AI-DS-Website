<div align="center">
  <h1>🏛️ Agni AI DS</h1>
  <p><strong>Student Discussion & Showcase Forum for AI & DS Department</strong></p>
  <p>Share projects, events, hackathons, and achievements with your batchmates</p>
  <p>
    <img alt="Python" src="https://img.shields.io/badge/python-3.13-blue" />
    <img alt="Flask" src="https://img.shields.io/badge/flask-3.0-black" />
    <img alt="SQLite" src="https://img.shields.io/badge/sqlite-3-blue" />
    <img alt="License" src="https://img.shields.io/badge/license-MIT-orange" />
  </p>
</div>

---

## 📖 The Story

College life is full of moments worth sharing — a hackathon you won, a project you're proud of, a presentation that went well, an event you organized. But there was no single place where AI & DS students at Agni College could put it all together and see what their batchmates were up to.

Most of the communication happened in scattered WhatsApp groups. Posts got buried. Achievements went unnoticed. Projects were finished and never seen again.

I wanted to fix that.

Agni AI DS is a dedicated space for our department — a feed where students can post what they're building, share what they've learned, and see what everyone else is doing. It's like a living gallery of everything the AI & DS batch is working on. One place to showcase, connect, and inspire each other.

---

## ✨ Features

- **Student registration** — sign up with your college email (`@act.edu.in`)
- **Create posts** — share images with captions about your projects, events, and achievements
- **Category tagging** — Event, Hackathon, Presentation, Mini Project, Personal Development, and more
- **Feed dashboard** — responsive card grid showing every post from the department
- **Like / Unlike** — one-click toggle with instant updates, no page reload
- **Image lightbox** — click any image to view it full-size in a modal
- **Admin controls** — designated admins can delete any post
- **Responsive design** — works on mobile, tablet, and desktop

---

## 🛠️ Tech Stack

| Layer      | Technology                         |
| ---------- | ---------------------------------- |
| Backend    | Python 3.13, Flask                 |
| Database   | SQLite (raw sqlite3 module)        |
| Auth       | Werkzeug password hashing (scrypt) |
| Frontend   | HTML5, CSS3, Vanilla JavaScript    |
| Uploads    | Werkzeug secure_filename           |

---

## 📍 The Process

I noticed something in my first year — people were doing cool stuff but no one knew about it. A guy built a gesture-controlled robot for the tech fest. A girl trained a model that predicted stock prices. But unless you were in the right WhatsApp group at the right time, you'd never know.

I wanted a feed. Something simple — post an image, write a caption, let people react. No algorithm, no ads, no notifications spam. Just a chronological feed of what the batch is up to.

Built it with Flask because it's lightweight and perfect for a project like this. SQLite for the database because it's zero-config and runs anywhere. The frontend is all vanilla — no frameworks, no build tools, just clean HTML and CSS with a few lines of JavaScript for the like button and image modal.

The result is a platform that does one thing well: **let AI & DS students share what they're building with each other.**

---

## 🚀 Running Locally

```bash
pip install flask werkzeug
flask --app app run
```

---

<p align="center">
  Built with care by <strong>Raj G.</strong>
</p>
