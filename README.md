# MagicStream 🎬✨

> **Movie streaming platform** with AI recommendation built with modern web technologies.  
> `React` · `Go` · `gin-gonic` · `MongoDB` · `Docker`

---

> ⚠️ **Fork notice**  
> This project was originally created by [GavinLonDigital](https://github.com/GavinLonDigital/MagicStream).  
> I forked it to learn **Docker & CI/CD** as part of the course  
> *Master Full-Stack Docker & CI/CD – Build a Production-Ready Pipeline*.

---

## 📖 About

This project is a full-stack simulation of a modern **Movie Streaming Platform**, designed to showcase how different technologies can be combined to deliver a scalable, AI-powered application.

- ⚛️ **React** frontend for an engaging user experience  
- 🐹 **Go / gin-gonic** backend for high-performance API services  
- 🤖 **LangChainGo + OpenAI** for AI-powered movie recommendations  
- 🗄️ **MongoDB** for scalable media metadata and user preferences storage  
- 🐳 **Docker** for containerized dev & production environments  

---

## ✨ Features

| Feature | Description |
|---|---|
| 🎥 Movie Streaming | Simulated on the frontend using React + React-Player |
| ⚙️ REST API | Written in Go, running on gin-gonic |
| 🤖 AI Recommendations | Powered by LangChainGo + OpenAI |
| 🗄️ Database | Scalable storage via MongoDB |
| 🐳 Docker Support | Dev & prod Dockerfiles + docker-compose |

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend / Client | JavaScript / React |
| Backend / Server | Go / gin-gonic |
| Storage / Database | MongoDB |
| Containerization | Docker / Docker Compose |

---

## 🐳 What I Added (Docker & CI/CD)

```
├── Client/magic-stream-client/
│   ├── Dockerfile.dev
│   ├── Dockerfile.prod
│   └── public/env.template.js
├── Server/MagicStreamServer/
│   ├── Dockerfile.dev
│   └── Dockerfile.prod
├── docker-compose.yaml
├── docker-compose.dev.yaml
├── docker-compose.prod.yaml
└── seed/
```

---

## 🚀 Installation

### 1. Clone the repo

```bash
git clone git@github.com:ates/MagicStreamApp.git
cd MagicStreamApp
```

### 2. Run in development

```bash
docker-compose -f docker-compose.dev.yaml up --build
```

### 3. Run in production

```bash
docker-compose -f docker-compose.prod.yaml up --build
```

---

## 🎬 Original Tutorial

▶️ [How to Build the App on YouTube](https://youtu.be/jBf7of9JTV8) — by **GavinLonDigital**

---

## 📄 License

This project is based on open-source work by GavinLonDigital.  
Fork maintained by **ates** for learning purposes.