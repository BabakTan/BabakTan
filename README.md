## Hi there 👋

<!--
**BabakTan/BabakTan** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
# 🚀 AWS DevOps Project

![AWS DevOps](assets/aws-devops.png)

---

## 📌 Hakkında
Bu repo, **AWS üzerinde DevOps uygulamalarını** göstermek için hazırlanmıştır.  
CI/CD pipeline, container deployment, otomasyon ve monitoring senaryolarını içermektedir.

---

## 🛠️ Kullanılan Teknolojiler
- ☁️ **AWS Services**: EC2, S3, Lambda, EKS  
- 🔄 **DevOps Tools**: GitHub Actions, Docker, Kubernetes, Terraform  
- 📊 **Monitoring**: CloudWatch, Prometheus, Grafana  

---

## ⚙️ Pipeline Akışı
```mermaid
flowchart LR
    A[💻 Developer] -->|push code| B[🔀 GitHub Repo]
    B --> C[🤖 CI/CD Pipeline]
    C --> D[🐳 Build & Test]
    D --> E[☁️ Deploy to AWS]
    E --> F[📈 Monitoring]
