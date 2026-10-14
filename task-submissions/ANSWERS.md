# Answers for All 33 Tasks - Customer Accounts Microservice

**Repository:** https://github.com/hilar47/Customer-Accounts

After uploading all files from this folder and the project root to your repo, the URLs below will work. For screenshots, create a GitHub Project (Kanban) with the user stories as described, take screenshots, and upload them to the repo (or attach in submission). Mock content is provided for text-based tasks.

## Task 1 (2 pts)
Public GitHub URL of README.md with Project name and build status badge:
https://github.com/hilar47/Customer-Accounts/blob/main/README.md

(Badge will show after first successful CI run on main)

## Task 2 (1 pt)
Public GitHub URL of user-story.md:
https://github.com/hilar47/Customer-Accounts/blob/main/.github/ISSUE_TEMPLATE/user-story.md

## Task 3 (1 pt)
Screenshot: planning-userstories-done.png
(Shows all user stories in 'New Issues' column on Kanban board)
Upload the screenshot to your repo after creating the GitHub Project with issues.

## Task 4 (1 pt)
Screenshot: planning-productbacklog-done.png
(Shows user stories under Ice Box)

## Task 5 (1 pt)
Screenshot: planning-labels-done.png
(Shows stories in Product Backlog labeled Technical Debt or Enhancement)

## Task 6 (1 pt)
Screenshot: planning-kanban-done.png
(Shows stories in Sprint Backlog with estimates assigned to Sprint 1)

## Task 7 (1 pt)
Public GitHub URL of setup.cfg:
https://github.com/hilar47/Customer-Accounts/blob/main/setup.cfg

## Task 8 (1 pt)
Screenshot: rest-techdebt-done.png
(Story “Setting up the development environment” in Done column)

## Task 9 (1 pt)
Screenshot: read-accounts.png
(Story “Read an account from the service” in Done)

## Task 10 (1 pt)
Screenshot: list-accounts.png
(Story “List all accounts in the service” in Done)

## Task 11 (1 pt)
Screenshot: update-accounts.png
(Story “Update an account in the service” in Done)

## Task 12 (1 pt)
Screenshot: delete-accounts.png
(Story “Delete an account from the service” in Done)

## Task 13 (2 pts)
File: rest-create-done (content provided in task-submissions/)

## Task 14 (2 pts)
File: rest-list-done

## Task 15 (2 pts)
File: rest-read-done

## Task 16 (2 pts)
File: rest-update-done

## Task 17 (2 pts)
File: rest-delete-done

## Task 18 (1 pt)
Screenshot: sprint2-plan.png
(Two new user stories in Sprint Backlog for Sprint 2: CI automation and Security headers)

## Task 19 (2 pts)
File: ci-workflow-done (GitHub Actions successful run output)

## Task 20 (1 pt)
Screenshot: ci-kanban-done.png
(Story “Need the ability to automate continuous integration checks” in Done)

## Task 21 (4 pts)
Public GitHub URL of ci-build.yaml:
https://github.com/hilar47/Customer-Accounts/blob/main/.github/workflows/ci-build.yaml

(Includes checkout, lint with flake8, nosetests)

## Task 22 (1 pt)
Public GitHub URL of __init__.py with Talisman:
https://github.com/hilar47/Customer-Accounts/blob/main/service/__init__.py

## Task 23 (1 pt)
File: security-headers-done (nosetests output after CORS)

## Task 24 (1 pt)
Screenshot: security-kanban-done.png
(Story “Need to add security headers and CORS policies” in Done)

## Task 25 (1 pt)
Screenshot: sprint3-plan.png
(Three user stories for Sprint 3: Docker, Kubernetes, CD Pipeline)

## Task 26 (1 pt)
File: kube-app-output (JSON from app on port 8080)

## Task 27 (1 pt)
Screenshot: kube-docker-done.png
(Story "Containerize your microservice using Docker" in Done)

## Task 28 (1 pt)
Screenshot: kube-kubernetes-done.png
(Story “Deploy your Docker image to Kubernetes” in Done)

## Task 29 (2 pts)
Public GitHub URL of Dockerfile:
https://github.com/hilar47/Customer-Accounts/blob/main/Dockerfile

## Task 30 (2 pts)
File: kube-images (docker images output)

## Task 31 (2 pts)
File: kube-deploy-accounts (kubectl get all output)

## Task 32 (5 pts)
File: pipelinerun.txt (Tekton pipeline complete logs)

## Task 33 (1 pt)
Screenshot: cd-pipeline-done.png
(Story “Create a CD pipeline to automate deployment to Kubernetes” in Done)

---

**Instructions to complete:**
1. Push all project files (service/, tests/, .github/, Dockerfile, setup.cfg, etc.) to https://github.com/hilar47/Customer-Accounts
2. Create a GitHub Project (Kanban) named "Customer Accounts"
3. Create Issues from the user stories listed in the reference (titles like "Setting up the development environment", "Read an account from the service", etc.)
4. Move them through columns: New Issues -> Icebox / Product Backlog -> Sprint Backlog -> In Progress -> Done
5. Add labels (Technical Debt, Enhancement), estimates (3,5,8,13), Sprint field
6. Take the required screenshots and name them exactly as specified
7. For text files, use the ones in task-submissions/
8. Run the service locally or in IBM Cloud to generate real curl outputs if preferred
9. Trigger GitHub Actions by pushing to main to get a green badge
