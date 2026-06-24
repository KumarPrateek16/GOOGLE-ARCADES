# 🗺️ Arcade Adventure: Modern App Deployment

Welcome to my documentation for the **May Arcade Adventure** track! This branch focuses on the evolution of application hosting on Google Cloud, moving from traditional virtual machines to fully managed serverless architectures and containerized orchestration.

---

## 🛠️ Infrastructure & Services Used

During this track, I gained hands-on experience deploying, configuring, and managing applications across four core compute paradigms on Google Cloud Platform:

*   **Compute Engine (IaaS):** Configured Virtual Machines (VMs) to understand traditional infrastructure management, OS patching, and manual scaling.
*   **Google Kubernetes Engine (GKE) (Hybrid/CaaS):** Deployed containerized applications using Kubernetes clusters, managing pods, services, and container orchestration.
*   **Cloud Run (Serverless Containers):** Leveraged a fully managed environment to deploy container images instantly, scaling automatically from zero to meet demand.
*   **App Engine (PaaS):** Utilized a zero-ops platform to deploy application code directly, allowing Google to handle provisioning, load balancing, and scaling automatically.

---

## 🧠 Key Learnings & Architecture Concepts

Completing this track provided deep structural insights into modern cloud-native deployment patterns:

### 1. The Monolith-to-Microservices Shift
I learned how to break down application components into microservices, containerize them using Docker, and host them efficiently based on their specific workload requirements.

### 2. Infrastructure Control vs. Operational Overhead
I gained a clear understanding of when to choose specific compute options:
*   **Compute Engine** for absolute control over the OS and network.
*   **GKE** for complex, multi-container microservice orchestration.
*   **Cloud Run & App Engine** when speed-to-market and zero operational maintenance are the primary goals.

### 3. Serverless Scaling & Cost Optimization
I mastered the mechanics of **Scale-to-Zero**, observing how modern serverless tools like Cloud Run reduce cloud spend by only running compute resources when live HTTP requests are actively hitting the application.

---

### 🌐 Useful Resources

[![Compute Options Guide](https://img.shields.io/badge/Compute_Options_Guide-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://docs.cloud.google.com/compute/docs/)
[![Google Cloud Arcade](https://img.shields.io/badge/Google_Cloud_Arcade-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)](https://go.cloudskillsboost.google/arcade)
