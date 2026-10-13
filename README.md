# task-tracker

Go + React application using **AWS SAM** for infrastructure.

## Structure
- `backend/` — Go Chi API
- `frontend/` — React (Vite)
- `infra/` — SAM template
- `buildspec.yml` — CodeBuild example

## Deploy
```bash
sam build
sam deploy --guided
```
