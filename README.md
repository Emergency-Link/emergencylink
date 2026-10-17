# EmergencyLink

Group 5 project. This one repository holds everything for the project.

## What goes where

| Folder | What it holds | Who works in it |
| --- | --- | --- |
| `frontend/` | The user interface (Next.js) | Web Development |
| `backend/` | The server, API and database code | Web Development |
| `infra/` | AWS setup and deployment scripts | Cloud & DevOps |
| `docs/` | Plans, designs, test cases, the demo script | Project Management and others |
| `.github/workflows/` | The automatic checks and deployments | Cloud & DevOps |

## The branches (the short version)

| Branch | What it is |
| --- | --- |
| `main` | The stable, approved version. It feeds the demo environment. |
| `develop` | Finished work waiting to be tested. It feeds the staging environment. |
| `feature/<area>-<short-name>` | Your own working branch, for example `feature/frontend-login-button`. |

Nobody works directly on `main` or `develop`.

## How to do your work

1. Download the latest code:
   `git checkout develop` then `git pull origin develop`
2. Create your own branch from it:
   `git checkout -b feature/frontend-login-button`
3. Do your work and save it:
   `git add .` then `git commit -m "feat: add login button"`
4. Upload YOUR branch (not develop):
   `git push -u origin feature/frontend-login-button`
5. On GitHub, open a pull request from your branch into `develop`.
6. Wait for the automatic checks and one reviewer. Then click "Squash and merge".

## Running the project

To be added by the developers when they add their code (install, build and run commands).
