
# My Flask App

This is a simple Python Flask web application created to practice CI/CD pipelines using GitHub and Docker.

## 🚀 Features

- Python Flask-based web server  
- Docker support (with Dockerfile)  
- Ready for CI/CD pipeline integration  

## 🛠️ How to Run (Locally with Docker)

### 1. Clone the Repository

git clone https://github.com/lokesh6509/LK_git.git
cd LK_git

### 2. Build the Docker Image

docker build -t myflaskapp .


### 3. Run the Container

docker run -p 5000:5000 myflaskapp

Then open your browser and visit:  
**http://localhost:5000**

## 📁 Files in the Project

- `app.py` – Main Flask app  
- `Dockerfile` – To build the Docker image  
- `requirement.txt` – Flask dependency list  

## 📚 Purpose

This project is part of my learning journey in DevOps to understand:

- Git and GitHub workflow  
- Docker basics  
- Setting up CI/CD pipelines (GitHub Actions, Jenkins, etc.)  

## 👤 Author

- [lokesh6509](https://github.com/lokesh6509)
💡 Recommended Way to Add It in Terminal
Use this one-liner to paste everything correctly without formatting issues:

cat > README.md << 'EOF'
