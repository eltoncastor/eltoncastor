# Elton Marques

I work in loss prevention at a retail company in Caruaru (PE), and I'm two semesters into a systems analysis and development degree. Most of what I know about programming came from building things I actually needed: a locker management system to replace 12 handwritten paper sheets, an OCR pipeline to digitize forms that used to eat hours of manual work.

## What I'm building

**Matriculation card reader**: a web app that reads and validates handwritten access-release logs from the employee entrance at work. When an employee needs to pass through the turnstiles outside their scheduled hours, whether from being late or a manager's scheduling gap, a manager radios the loss prevention assistant on duty to release them with the master card. That release used to be logged by hand: date, time, employee ID, reason for the release, and the manager who authorized it. OCR (PaddleOCR + OpenCV for preprocessing) reads and validates those entries. FastAPI backend, React frontend, running on a VPS behind Cloudflare Tunnel + Tailscale.

Live: [eltonmarques.com/leitor](https://eltonmarques.com/leitor)

There's also a desktop version (Python + Tkinter) doing something similar for internal paperwork at work: same OCR core, different interface, different constraints.

## Stack

### Languages
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white" />
</p>

### Web & Backend
<p align="left">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black" />
</p>

### Data & Automation
<p align="left">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white" />
  <img src="https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white" />
</p>

### Tools & Infrastructure
<p align="left">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat&logo=cloudflare&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailscale-000000?style=flat&logo=tailscale&logoColor=white" />
</p>

---

## Also

I'm in Programa Acelera, an internal leadership track at the company I work for. Different skill set than code, but it's teaching me things the terminal doesn't.

<p align="center"><i>Build. Learn. Improve. Repeat.</i></p>
