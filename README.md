# DevOps Practice

Тестовое задание на стажировку DevOps.

## Приложение

Простое веб-приложение на Python и Flask, возвращающее `Hello, World!`.

Приложение работает на порту `32777`.

## Технологии

- Python
- Flask
- Docker
- Docker Hub
- Kubernetes
- Minikube

## Структура проекта

- `app.py` - исходный код приложения
- `requirements.txt` - зависимости Python
- `Dockerfile` - инструкция сборки Docker-образа
- `deployment.yaml` - Kubernetes Deployment
- `service.yaml` - Kubernetes Service
- `architecture.drawio` - схема организации контейнеров и сервисов

## Docker

Docker-образ:

`ifiqo/hello-world:latest`

## Kubernetes

Для приложения создан Deployment с двумя репликами.

Проверка:

```bash
kubectl get deployments
kubectl get pods