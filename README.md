# DevOps Assignment
 
A simple Node.js application that starts an HTTP server and responds with “Hello DevOps World!” when accessed. This project is containerized using Docker and ready for deployment to Kubernetes or any container platform.
 
---
 
## 🚀 Project Structure
 
```
.
├── Dockerfile
├── index.js
└── package.json
```
 
---
 
## 🧩 Requirements
 
* Node.js (v16+)
* Docker
 
---
 
## ⚙️ Run Locally
 
```bash
# Install dependencies
npm install
 
# Start the app
npm start
```
 
App runs at: **[http://localhost:5000](http://localhost:8000)**
 
---
 
## 🐳 Run with Docker
 
```bash
# Build Docker image
docker build -t devops-node-app .
 
# Run container
docker run -p 8000:8000 devops-node-app
```
 
Access at: **[http://localhost:5000](http://localhost:8000)**
 
---
 
## Output
 
When running successfully, terminal will show:
 
```
Server running at http://localhost:8000
```
 
And browser/curl will return:
 
```
Hello DevOps World!
```
 
---
 
##  Author
 
**Garima Sharma**
 
