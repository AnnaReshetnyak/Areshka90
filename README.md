<svg xmlns="http://www.w3.org/2000/svg" width="100%" height="250px" viewBox="0 0 1200 250">
  <defs>
    <linearGradient id="gradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#6366f1;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:1" />
    </linearGradient>
    
    <style>
      @keyframes float {
        0% { transform: translateY(0px); }
        50% { transform: translateY(-20px); }
        100% { transform: translateY(0px); }
      }
      .floating { animation: float 4s ease-in-out infinite; }
    </style>
  </defs>

  <rect width="100%" height="100%" fill="url(#gradient)"/>
  
  <!-- Wave Effect -->
  <path fill="#ffffff10" d="M0,150 C250,200 550,50 1200,150 L1200,250 L0,250 Z" style="opacity: 0.1;"/>
  
  <!-- Main Content -->
  <g transform="translate(100, 100)" class="floating">
    <text x="0" y="40" font-family="Arial" font-size="40" fill="white" font-weight="bold">
      👋 Hello, I'm 
      <tspan fill="#fbbf24">[Anna]</tspan>
    </text>
    <text x="0" y="90" font-family="Arial" font-size="28" fill="white" opacity="0.9">
      MLOps Engineer | AI Infrastructure Builder
    </text>
  </g>

  <!-- Animated Circles -->
  <circle cx="1050" cy="80" r="40" fill="#ffffff20" class="floating"/>
  <circle cx="1100" cy="180" r="30" fill="#ffffff20" class="floating" style="animation-delay: -2s"/>
</svg>
# Areshka90
# 👋 Hi there! I'm Anna, a passionate MLOps Engineer

Welcome to my GitHub profile! I'm on a mission to bridge the gap between Machine Learning and DevOps by building scalable, reliable, and automated ML systems. 🚀

### 🔍 What I'm Focused On
- 🛠️ ML Model Deployment: Streamlining the journey from Jupyter notebooks to production-ready systems.
- 🔄 CI/CD Pipelines: Automating ML workflows with tools like GitHub Actions, Jenkins, and Airflow.
- ☁️ Infrastructure as Code: Leveraging Terraform and AWS CloudFormation for reproducible environments.
- 📊 ML Monitoring: Implementing robust solutions for model performance tracking with Prometheus and Grafana.
- 🤝 Collaboration: Bridging the gap between data scientists, engineers, and DevOps teams.

---

### 🛠️ Tech Stack
Machine Learning & Frameworks  
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat&logo=mlflow&logoColor=white)

DevOps & Cloud  
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)

Monitoring & Logging  
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![ELK](https://img.shields.io/badge/ELK-005571?style=flat&logo=elastic&logoColor=white)

Version Control  
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=github-actions&logoColor=white)

---

### 🚀 Featured Projects
1. ML Pipeline Automation  
   End-to-end automated training/deployment pipeline using MLflow and Kubernetes.  
   Python Kubeflow AWS Sagemaker MLflow

2. Real-time Model Monitoring  
   Dashboard for tracking model drift with FastAPI + Prometheus.  
   FastAPI Prometheus Grafana Docker

3. Serverless ML Inference  
   AWS Lambda-based model serving system with CI/CD integration.  
   AWS Lambda Terraform GitHub Actions PyTorch

---

### 🤝 Let's Collaborate!
I'm always open to:
- 💡 Discussing MLOps best practices
- 🚀 Contributing to open-source projects
- 🎯 Exploring innovative ML infrastructure solutions
