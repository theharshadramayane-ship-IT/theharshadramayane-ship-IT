<!-- Animated Header -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&pause=1000&color=58A6FF&center=true&vCenter=true&width=800&lines=Hi,+I'm+The+Harshad+Ramayane+%F0%9F%91%8B;Aspiring+Software+Developer;MERN+Stack+%7C+Systems+%26+Backend;Architecting+High-Assurance+Infrastructure" alt="Typing SVG" />
  
  <p>
    <img src="https://komarev.com/ghpvc/?username=theharshadramayane-ship-IT&label=Profile%20Views&color=0e75b6&style=for-the-badge" alt="Profile Views" />
    <img src="https://img.shields.io/github/followers/theharshadramayane-ship-IT?label=Followers&style=for-the-badge&color=0e75b6" alt="Followers" />
    <img src="https://img.shields.io/badge/Focus-Systems%20Engineering-ff69b4?style=for-the-badge" alt="Focus" />
  </p>
</div>

<br/>

<!-- Intro Section -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0e75b6&height=100&section=header&text=Welcome%20to%20my%20Digital%20Space&fontSize=30&fontAlignY=35&animation=twinkling" width="100%" />
</div>

### 👨‍💻 Professional Summary
I'm an Information Technology (IT) student graduating in 2027, passionate about software development, problem-solving, and building practical applications. I don't just build web apps; I am actively transitioning into a **Systems & Backend Engineer**. I enjoy exploring technologies, understanding how software works deep down, and improving my skills through consistent coding, architecture design, and hands-on projects.

Currently, I am expanding my expertise from standard MERN stack applications into **high-performance backend infrastructure** using Go, Rust, and PostgreSQL.

<br/>

<!-- Animated Tech Stack -->
### 🛠️ Tech Stack & Tools

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=html,css,js,react,nodejs,express,mongodb,mysql,rust,go,postgres,ts,git,github,vscode,postman,docker&perline=6" alt="My Skills" />
  </a>
</div>

<br/>

<!-- 3D/Animated Feature Sections -->
### 🚀 About Me

<table>
  <tr>
    <td width="50%">
      <h4>🎓 Education & Core</h4>
      <ul>
        <li><b>IT Student</b> | Class of 2027</li>
        <li><b>MERN Stack</b> Full-Stack Developer</li>
        <li><b>DSA:</b> Practicing in JavaScript</li>
        <li><b>Backend:</b> Node.js, Express, Go</li>
      </ul>
    </td>
    <td width="50%">
      <h4>🦀 Systems & Rust Journey</h4>
      <ul>
        <li><b>Rust:</b> Ownership, Borrowing, Lifetimes</li>
        <li><b>Go:</b> Concurrency, Goroutines</li>
        <li><b>DB:</b> PostgreSQL, ACID Transactions</li>
        <li><b>Arch:</b> Memory Safety, FFI Boundaries</li>
      </ul>
    </td>
  </tr>
</table>

> [!TIP]
> **My goal is not just to learn Rust syntax, but to understand how to engineer reliable and efficient software with it.** I am currently building **OrderGuard**, a trading reliability system that uses Rust and Go to prevent financial loss from duplicate orders.

<br/>

### 🏗️ System Architecture (OrderGuard)
I am designing an infrastructure that uses a **Go backend** to orchestrate workflows, a **Rust library** for deterministic safety rules, and **PostgreSQL** for durable, crash-safe data. 

```text
[ Frontend (React/TS) ]
         │  (REST + Idempotency Key)
         ▼
[ Go Backend (Orchestrator) ]
         │
         ├──> [ PostgreSQL (Hosted) ] ── Durable state & Idempotency
         │
         └──> [ Rust Safety Library (cgo) ]
                  └── Deterministic Duplicate Detection
