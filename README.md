![job](./job_r.png)

<div align="center">

<h1>Roman <a href="https://github.com/rmnp1"> <img src="https://img.shields.io/badge/@rmnp1-1e1e2e?style=flat-square&logo=github&logoColor=cba6f7" alt="@rmnp1" /></a></h1>



<h3>Backend Engineer · Python </h3>

<p><em>I build reliable server-side systems — database-backed web apps, containerized services, and clean backend logic that holds up under pressure.</em></p>

</div>

---

<div align="center">

### Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rmnpl)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:rmncurrit@gmail.com)

![Visitor Count](https://komarev.com/ghpvc/?username=rmnp1&style=for-the-badge&color=6e40c9&label=PROFILE+VIEWS)

</div>

---

## `$ whoami`

Backend-focused developer with a bias toward simplicity, correctness, and maintainability. I design and ship full-stack web applications using Python and Flask — with SQLAlchemy ORM, PostgreSQL, Docker containerization, and Jinja2-driven frontends.

**Engineering focus:**

- **Full-Stack Web Development** — Building Flask applications end-to-end: routing, ORM models, Jinja2 templates, and CSS styling in one coherent system
- **Database Design & Migrations** — Modeling relational data with SQLAlchemy + PostgreSQL and managing schema evolution cleanly with Flask-Migrate
- **Application Containerization** — Packaging multi-service apps with Docker and Docker Compose for reproducible, portable deployments
- **User Authentication Systems** — Implementing secure sign-up, login, and session management flows from scratch
- **Automated Testing** — Writing pytest suites that catch regressions early and document expected behavior as executable specs
- **Modern Python Tooling** — Using `uv` for fast, deterministic dependency management and environment isolation

---

## `$ ls -la ./projects`

### 🎰 Flask Slot Machine

> A web-based slot machine app with full user authentication — built as a demonstration of production-grade Flask architecture.

<details>
<summary><strong>View project details</strong></summary>

**What it does:**
- User registration, login, and logout with session management
- Slot machine game logic handled entirely server-side in Python
- Persistent user state stored via SQLAlchemy ORM + PostgreSQL
- Responsive UI rendered with Jinja2 templates + CSS3
- Database schema versioned and migrated with Flask-Migrate
- Entire app containerized: one `docker compose up` and it runs

**Architecture decisions:**
- Kept game logic in the Flask layer — no JavaScript game engine, no client-side state
- SQLAlchemy models reflect a normalized schema; migrations are committed and reproducible
- Docker Compose wires the app and PostgreSQL containers together; no manual setup required
- `uv` manages the Python environment for fast, lockfile-driven installs
- pytest covers the core game and auth logic

</details>

**Stack:**

<div align="center">

![Python](https://img.shields.io/badge/Python-1e1e2e?style=flat-square&logo=python&logoColor=3b82f6)
![Flask](https://img.shields.io/badge/Flask-1e1e2e?style=flat-square&logo=flask&logoColor=a6e3a1)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1e1e2e?style=flat-square&logo=postgresql&logoColor=89b4fa)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1e1e2e?style=flat-square&logo=sqlalchemy&logoColor=cba6f7)
![Jinja2](https://img.shields.io/badge/Jinja2-1e1e2e?style=flat-square&logo=jinja&logoColor=fab387)
![HTML5](https://img.shields.io/badge/HTML5-1e1e2e?style=flat-square&logo=html5&logoColor=f38ba8)
![CSS3](https://img.shields.io/badge/CSS3-1e1e2e?style=flat-square&logo=css3&logoColor=89b4fa)
![Docker](https://img.shields.io/badge/Docker-1e1e2e?style=flat-square&logo=docker&logoColor=89dceb)
![Docker Compose](https://img.shields.io/badge/Compose-1e1e2e?style=flat-square&logo=docker&logoColor=89dceb)
![pytest](https://img.shields.io/badge/pytest-1e1e2e?style=flat-square&logo=pytest&logoColor=f38ba8)
![uv](https://img.shields.io/badge/uv-1e1e2e?style=flat-square&logo=python&logoColor=a6e3a1)

</div>

---

## `$ cat tech_stack.json`

<div align="center">

**Core Language**

![Python](https://img.shields.io/badge/Python-1e1e2e?style=flat-square&logo=python&logoColor=3b82f6)

**Web & Frameworks**

![Flask](https://img.shields.io/badge/Flask-1e1e2e?style=flat-square&logo=flask&logoColor=a6e3a1)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-1e1e2e?style=flat-square&logo=sqlalchemy&logoColor=cba6f7)
![Flask--Migrate](https://img.shields.io/badge/Flask--Migrate-1e1e2e?style=flat-square&logo=flask&logoColor=cba6f7)
![Jinja2](https://img.shields.io/badge/Jinja2-1e1e2e?style=flat-square&logo=jinja&logoColor=fab387)
![HTML5](https://img.shields.io/badge/HTML5-1e1e2e?style=flat-square&logo=html5&logoColor=f38ba8)
![CSS3](https://img.shields.io/badge/CSS3-1e1e2e?style=flat-square&logo=css3&logoColor=89b4fa)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1e1e2e?style=flat-square&logo=postgresql&logoColor=89b4fa)

**DevOps & Containers**

![Docker](https://img.shields.io/badge/Docker-1e1e2e?style=flat-square&logo=docker&logoColor=89dceb)
![Docker Compose](https://img.shields.io/badge/Compose-1e1e2e?style=flat-square&logo=docker&logoColor=89dceb)
![Git](https://img.shields.io/badge/Git-1e1e2e?style=flat-square&logo=git&logoColor=fab387)

**Testing & Tooling**

![pytest](https://img.shields.io/badge/pytest-1e1e2e?style=flat-square&logo=pytest&logoColor=f38ba8)
![uv](https://img.shields.io/badge/uv-1e1e2e?style=flat-square&logo=python&logoColor=a6e3a1)

</div>

---

## `$ gh stats --user rmnp1`

<div align="center">

<table border="0">
  <tr>
    <td width="45%" align="center">
      <a href="https://git.io/awesome-stats-card">
        <img
          src="https://awesome-github-stats.azurewebsites.net/user-stats/rmnp1?cardType=level&theme=tokyonight&preferLogin=true&Background=1e1e2e&Border=1e1e2e&Title=cba6f7&Text=cdd6f4&Ring=cba6f7&Fire=f38ba8&Icons=89b4fa"
          alt="GitHub Stats"
        />
      </a>
    </td>
    <td width="55%" align="center">
      <img
        src="https://streak-stats.demolab.com?user=rmnp1&hide_border=true&background=1e1e2e&ring=cba6f7&fire=f38ba8&currStreakLabel=cdd6f4&currStreakNum=cdd6f4&sideLabels=cdd6f4&sideNums=cdd6f4&dates=6c7086"
        alt="GitHub Streak"
      />
    </td>
  </tr>
</table>

</div>

---

<div align="center">
<sub>rmnp1 · rmncurrit@gmail.com · built with precision, not a template</sub>
</div>
