# 🚀 Node.js CI/CD with GitHub Actions & Docker

This project demonstrates a simple CI/CD pipeline for a **Dockerized Node.js web app**, using **GitHub Actions** and **DockerHub**.

---

## 🔧 Tech Stack

- ⚙️ Node.js (no installation needed on local machine)
- 🐳 Docker
- 🧪 GitHub Actions
- 📦 DockerHub (for image hosting)

---

## 📁 Project Structure

```
📦 nodejs-demo-app/
 ┣ 📄 index.js
 ┣ 📄 package.json
 ┣ 📄 Dockerfile
 ┗ 📂 .github/
    ┗ 📂 workflows/
       ┗ 📄 main.yml
```

---

## ⚙️ How It Works

1. **Push to main** branch triggers GitHub Actions
2. GitHub builds Docker image using your Dockerfile
3. Authenticates to DockerHub using saved secrets
4. Pushes image to DockerHub:  
   `docker.io/<your-username>/nodejs-demo-app:latest`

---

## 🐳 DockerHub Image

📦 [View on DockerHub](https://hub.docker.com/r/<your-username>/nodejs-demo-app)

---

## 🧪 Test Locally from DockerHub

```bash
docker pull <your-username>/nodejs-demo-app:latest
docker run -p 3000:3000 <your-username>/nodejs-demo-app:latest
```

Visit: [http://localhost:3000](http://localhost:3000)

---

## 📸 Screenshots to Include

- ✅ GitHub Actions → successful CI/CD run
- ✅ DockerHub → image pushed with correct tag
- ✅ Browser → running app from pulled Docker image

---

## 📤 Submission

Repo Link:  
🔗 [https://github.com/<your-username>/nodejs-demo-app](https://github.com/<your-username>/nodejs-demo-app)

📝 Submitted via:  
👉 [Google Form](https://forms.gle/Ma32dADK92mcecjV8)

---

## 🙌 Credits

Built  by **Yasvanth Rajan**  
Thanks to the **DevOps Internship Team** for the hands-on opportunity!
