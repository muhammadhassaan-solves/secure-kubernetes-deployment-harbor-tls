<h1>Secure Deployment of Containerized App to Kubernetes using Harbor & TLS</h1>

<h2>Description</h2>
This project showcases a secure end-to-end container deployment to Kubernetes using a self-hosted Harbor registry over HTTPS. It includes TLS certificate generation, Docker and Minikube trust setup, and Kubernetes secret-based authentication. The goal was to demonstrate practical DevOps skills in secure image delivery, private registry integration, and production-ready deployment workflows.


<h2>Tools & Technologies</h2>

- Harbor (Private Registry)
- Kubernetes (Minikube)
- Docker (with cert trust)
- TLS/SSL (OpenSSL)
- NodePort Services
- YAML + kubectl
- Ubuntu 24.04


<h2>Project Walk-through</h2>

<p align="center">
1. Define a Simple Web App <br />
<img src="https://i.postimg.cc/28L3czzk/1.jpg"/>
<br />
<br />
2. Optimize with Multi-Stage Dockerfile <br/>
<img src="https://i.postimg.cc/vZpKrt08/2.jpg" />
<br />
<br />
3. Push to Harbor Over HTTPS  <br/>
<img src="https://i.postimg.cc/521pq9zG/3.jpg"/>
<br />
<br />
4. Deploy to Kubernetes with Private Registry <br/>
<img src="https://i.postimg.cc/1Xm5rq9X/4.jpg" />
<br />
<br />
5. Test & Access App via NodePort <br/>
<img src="https://i.postimg.cc/NMYgQH2D/5.jpg" />
<br />
<br />
  
</p>

