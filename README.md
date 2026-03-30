👨‍💻 Author

Made with ❤️ by Sameer


🚀 Django Notes App with Kubernetes

A production-ready Notes Application built using Django, containerized with Docker, and deployed on Kubernetes.

---

📌 Tech Stack

- 🐍 Django (Backend)
- 🐳 Docker (Containerization)
- ☸️ Kubernetes (Orchestration)
- ⚙️ Docker Compose (Local Setup)

---

📂 Project Structure

.
├── Dockerfile
├── docker-compose.yml
├── Deployment.yaml
├── Service.yaml
├── ConfigMap.yaml
├── Secrets.yaml
├── persistent-volume-claim.yaml
├── manage.py
├── requirements.txt
└── README.md

---

⚡ Features

- 📝 Notes Management API
- 📦 Dockerized Application
- ☸️ Kubernetes Deployment Ready
- 🔐 Config & Secrets Handling
- 💾 Persistent Storage Support

---

🐳 Run Locally with Docker

docker-compose up --build

App will be available at:
👉 http://localhost:8000

---

☸️ Deploy on Kubernetes

1. Apply all configs

kubectl apply -f .

2. Check pods

kubectl get pods

3. Check services

kubectl get svc

---

🔐 Environment Variables

Create a ".env" file for secrets (not committed to repo):

DEBUG=True
SECRET_KEY=your_secret_key
DATABASE_URL=your_db_url

---

📸 Screenshots (Optional)

Add your app screenshots here

---

🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

⭐ Support

If you like this project, give it a ⭐ on GitHub!
