CI/CD Pipeline for Automated Testing & Deployment 🚀
Overview
This project demonstrates a Continuous Integration/Continuous Deployment (CI/CD) pipeline using GitHub Actions and GitHub Pages.
The pipeline automates code testing (Pytest) and deployment whenever updates are pushed to GitHub.
Features
✅ Automated Testing → Runs Pytest on each commit.
✅ Test Coverage Analysis → Uses Pytest-Cov to measure test coverage.
✅ GitHub Actions Workflow → Automates testing & deployment.
✅ Static Site Hosting → Deploys updates via GitHub Pages.

Project Structure

├── .github/workflows/ci-cd-pipeline.yml  # GitHub Actions workflow  
├── test_sample.py                        # Automated test cases  
├── index.html                            # Webpage for GitHub Pages deployment  
├── styles.css                            # Styling for the website  
└── README.md                             # Project documentation  

Getting Started
1️⃣ Clone the Repository

git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY

2️⃣ Install Dependencies
pip install pytest pytest-cov


3️⃣ Run Tests Locally
pytest --cov . test_sample.py

4️⃣ Push Code to GitHub
git add .
git commit -m "Updated project"
git push origin master

Live Deployment
View the live project here:

https://crabstalker.github.io/my-ci-cd-project


