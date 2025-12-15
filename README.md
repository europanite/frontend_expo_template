# [Frontend Expo Template](https://github.com/europanite/frontend_expo_template "Frontend Expo Template")

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
![OS](https://img.shields.io/badge/OS-Linux%20%7C%20macOS%20%7C%20Windows-blue)
[![CI](https://github.com/europanite/frontend_expo_template/actions/workflows/ci.yml/badge.svg)](https://github.com/europanite/frontend_expo_template/actions/workflows/ci.yml)
[![docker](https://github.com/europanite/frontend_expo_template/actions/workflows/docker.yml/badge.svg)](https://github.com/europanite/frontend_expo_template/actions/workflows/docker.yml)
[![GitHub Pages](https://github.com/europanite/frontend_expo_template/actions/workflows/deploy-pages.yml/badge.svg)](https://github.com/europanite/frontend_expo_template/actions/workflows/deploy-pages.yml)

![React Native](https://img.shields.io/badge/react_native-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![Jest](https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white)
![Expo](https://img.shields.io/badge/expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37)

!["web_ui"](./assets/images/web_ui.png)

[PlayGround](https://europanite.github.io/frontend_expo_template/)

A Client Side Expo Template.

---

## 🚀 Getting Started

### 1. Prerequisites
- [Docker Compose](https://docs.docker.com/compose/)

### 2. Build and start all services:

```bash
# set environment variables:
export REACT_NATIVE_PACKAGER_HOSTNAME=${YOUR_HOST}

# Build the image
docker compose build

# Run the container
docker compose up

```

### 3. Test:
```bash
docker compose \
-f docker-compose.test.yml up \
--build --exit-code-from \
frontend_test
```

---

# License
- Apache License 2.0