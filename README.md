# devops-ci-app

Учебное Flask-приложение для практической работы № 10.

CI: Pylint → pytest → Docker build → smoke-test → GHCR.

В Pull Request выполняются проверки. Публикация образа выполняется при push в `main`.

- Health endpoint — `/health`.
- Образ — `ghcr.io/saymoon0/devops-ci-app`.
- Workflow — `.github/workflows/ci.yml`.
