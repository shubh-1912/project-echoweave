# 🎧 project-echoweave

**EchoWeave** is a backend system for an AI-powered music player, built with **Go** and structured using **microservices**.

Users can:
- Create accounts and store play history
- Play queued tracks with smooth, AI-assisted transitions

---

## 🧱 Microservices (WIP)

| Service         | Purpose                          |
|-----------------|----------------------------------|
| `auth-service`  | User signup/login & JWT auth     |
| `user-service`  | Profiles and play history        |
| `player-service`| Queue & playback logic           |
| `mixer-service` | AI-based song transitions        |
| `gateway`       | Unified API routing              |

---

## 📦 Tech Stack

- Go + Gin
- PostgreSQL (planned)
- Redis (planned)

---

## 🚀 Dev Setup

```bash
git clone https://github.com/shubh-1912/project-echoweave.git
cd project-echoweave
docker-compose up --build
