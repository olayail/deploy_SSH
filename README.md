# deploy_SSH
Repository demonstrating how to deploy a project to a remote server using SSH key authentication and GitHub Actions.

SSH Deployment Instructions
Clone this repository.

Add the following secrets in GitHub Actions:

SSH_PRIVATE_KEY

SSH_HOST

USER_NAME

PROJECT_PATH

GIT_REPO

Push changes to the main branch to trigger deployment.

GitHub Actions will:

Connect to the remote server via SSH

Pull the latest version of the project

Place the greeting file (Saludo_andres.txt) on the server

```bash
ssh -i pemSMacServerEstudiantes ndgserver@201.190.115.29

