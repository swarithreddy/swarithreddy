<h1 align="center">Swarith Reddy</h1>

<p align="center">
  <b>Security-minded backend developer — practical systems, applied ML, and automation that ships.</b><br/>
  B.Tech CSE @ VJIT, Hyderabad · Class of 2027 · CGPA 9+
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/swarithreddy/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:swarithreddy5@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://linktr.ee/SwarithReddy"><img src="https://img.shields.io/badge/Linktree-39E09B?style=for-the-badge&logo=linktree&logoColor=white" alt="Linktree"/></a>
  <a href="https://leetcode.com/u/SwarithReddy/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"/></a>
  <a href="https://www.hackerrank.com/profile/swarithreddy2005"><img src="https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank"/></a>
</p>

---

## What I build

A lot of my work is software that **checks, verifies, or defends something**: a threaded port scanner that writes its own audit report, a URL service that handles collisions and abuse at the database and API layer, and an attendance system that only passes when face, QR code and location all agree.

I work mostly in **Python and Node.js**, backend-first, and I try to finish projects properly: tests, persistence, and packaging so someone else can actually run them.

**Right now:** Cybersecurity Intern (Cyber Investigator) at Supraja Technologies since Dec 2025, doing web-app VAPT and API penetration testing against the OWASP Top 10 and OWASP API Security Top 10.
**Looking for:** entry-level Software Engineer / Developer roles, graduating 2027.

---

## Selected work

### 🔍 Advance Port Scanner & AI Security Assessor
`Python` `Tkinter` `SQLite` `Gemini API` `ReportLab` `PyInstaller`

- Multi-threaded TCP/UDP scanner with **512 concurrent workers**, across IP ranges and domains
- GUI stays responsive through thread-safe background execution
- Gemini-based risk assessment with **automatic model fallback**, paired with a static vulnerability database
- Scan history in SQLite, **PDF audit reports** via ReportLab, shipped as a standalone Windows executable

### 🔗 URL Shortener — full-stack link service
`Node.js` `Express` `MongoDB` `node-cron` · [source](https://github.com/swarithreddy/All_Projects)

- Base62 short codes with custom aliases and REST endpoints (`POST /shorten`, `GET /:code`, `GET /analytics/:code`)
- **Collisions resolved at the database layer** with unique indexes and retry-on-collision, plus duplicate-URL detection
- Click analytics, link expiry, and an hourly node-cron cleanup job
- Abuse protection with `express-rate-limit`: 20 requests per 15 minutes per IP

### 🛡️ Multi-Factor Geofenced Attendance System
`Python` `Flask` `OpenCV` `Geopy` `Pandas`

- Three independent checks: **facial recognition, QR verification, and location**
- Identity matching with ORB feature extraction and Hamming-distance comparison
- Submissions rejected outside a 20 m classroom radius
- Attendance logs and audit records exported to Excel

### 🤖 RAG-based AI Assistant
`Python` `LLM` `Vector Store` `Embeddings` · [source](https://github.com/swarithreddy/All_Projects/tree/main/01-Portfolio/RAG-based-ai)

- Retrieval-augmented generation pipeline that answers questions from your own documents instead of relying on the model's memory alone
- Documents are chunked, embedded and indexed so the most relevant context is retrieved for each query
- Retrieved context is passed to the LLM to produce grounded answers, which cuts down hallucination

**Also built:** IoT energy monitoring & automatic billing (Arduino, Embedded C — 🥇 hackathon, 2024) · House Price Predictor (Scikit-learn, Pandas) · Student Task Manager (Flask, SQLite) · IEEE VJIT chapter website (HTML, CSS, JS) · [Online resume](https://github.com/swarithreddy/online-resume) (vanilla HTML/CSS/JS, no framework) · Task Tactics (linked lists in C)

📂 More of my academic and experimental work is in [**All_Projects**](https://github.com/swarithreddy/All_Projects).

---

## Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=py,java,cpp,c,js,nodejs,express,flask,django,mongodb,mysql,sqlite,opencv,tensorflow,pandas,numpy,git,github,linux,postman,arduino&perline=11" alt="Tech stack"/>
</p>

**Security:** Nmap · Metasploit · Burp Suite · SQLMap · OWASP Top 10 · OWASP API Security Top 10
**ML:** Scikit-learn · TensorFlow · OpenCV · Pandas · NumPy
**Web:** HTML · CSS · JavaScript, with Node.js/Express and Flask on the backend
**Fundamentals:** Data Structures & Algorithms · OOP · DBMS · Operating Systems · Computer Networks

---

## Experience & recognition

| | |
|---|---|
| 🔐 **Cybersecurity Intern**, Supraja Technologies | Web-app VAPT, API pen-testing, recon and threat intelligence, client-facing investigation reports |
| 🚀 **Founder**, JobPrep (early-stage) | Career-prep platform concept for freshers: job discovery, role roadmaps, quizzes, ATS checking. Backed by ₹2 lakh from an investor |
| 🏆 **Hackathons** | 1st Prize at Hackfest 2025 and Cybronix 2025 · College finalist, Smart India Hackathon · 1st Prize, IoT hackathon (2024) |
| 🧠 **Training** | Machine Learning, IIT Kanpur (2025) · Cisco PCAP (Python) and CLA (C) |
| 💻 **Problem solving** | HackerRank Gold (C++), Silver (Java) · Qualified JEE Mains & Advanced (2023) |
| 👥 **Leadership** | Vice Chair, IEEE Computer Society and Computer Society of India at VJIT · Class Representative · Volunteer, HOPE |

---

<p align="center">
  If you're hiring for backend, security-leaning, or general software roles — or just want to talk about any of the above — <a href="mailto:swarithreddy5@gmail.com">drop me a line</a>.
</p>
