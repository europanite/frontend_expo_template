<!-- P2M_REPORT -->
<!-- GENERATED at 2026-10-11 09:57:12 -->
# Project Export: frontend_expo_template

## Overview

- Root: `/home/skinner/frontend_expo_template`
- Files: **31**
- Total size: **35977 bytes**
- Project ignore files: `.gitignore` (110 patterns), `.dockerignore` (42 patterns)
- Total LOC: 990 | SLOC: 840 | TODOs: 0

### Language mix
- markdown: 6
- javascript: 6
- tsx: 6
- yaml: 4
- typescript: 3
- plain: 2
- json: 2
- html: 2

### Top 12 largest files (bytes)
- `LICENSE` — 11340 bytes
- `CODE_OF_CONDUCT.md` — 4085 bytes
- `.github/workflows/ci.yml` — 2006 bytes
- `README.md` — 1911 bytes
- `.dockerignore` — 1877 bytes
- `.github/workflows/pages.yml` — 1669 bytes
- `SECURITY.md` — 1181 bytes
- `frontend/app/components/SettingsBar.tsx` — 1046 bytes
- `frontend/app/jest.config.ts` — 1011 bytes
- `frontend/app/context/Auth.tsx` — 1001 bytes
- `frontend/app/App.tsx` — 991 bytes
- `frontend/app/screens/HomeScreen.tsx` — 872 bytes

### Top 12 longest files (LOC)
- `LICENSE` — 201 LOC
- `.github/workflows/ci.yml` — 72 LOC
- `.dockerignore` — 71 LOC
- `CODE_OF_CONDUCT.md` — 68 LOC
- `.github/workflows/pages.yml` — 60 LOC
- `frontend/app/screens/HomeScreen.tsx` — 55 LOC
- `README.md` — 54 LOC
- `SECURITY.md` — 38 LOC
- `frontend/app/context/Auth.tsx` — 35 LOC
- `frontend/app/app.json` — 34 LOC
- `frontend/app/components/SettingsBar.tsx` — 33 LOC
- `.github/ISSUE_TEMPLATE/bug_report.md` — 30 LOC

### Project tree (included subset)
```
frontend_expo_template/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── workflows/
│   │   ├── ci.yml
│   │   ├── docker.yml
│   │   └── pages.yml
│   └── pull_request_template.md
├── frontend/
│   └── app/
│       ├── __mocks__/
│       │   ├── expoConstantsMock.js
│       │   ├── expoMock.js
│       │   └── expoRouterMock.js
│       ├── __tests__/
│       │   └── smoke.test.tsx
│       ├── components/
│       │   └── SettingsBar.tsx
│       ├── context/
│       │   └── Auth.tsx
│       ├── public/
│       │   ├── 404.html
│       │   ├── _config.yml
│       │   └── google095bf08db4fb15d0.html
│       ├── screens/
│       │   ├── HomeScreen.tsx
│       │   └── HomeScreenUtil.tsx
│       ├── app.json
│       ├── App.tsx
│       ├── babel.config.js
│       ├── index.ts
│       ├── jest.config.ts
│       ├── jest.setup.ts
│       ├── jest.setupFiles.js
│       ├── metro.config.js
│       └── tsconfig.json
├── .dockerignore
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── README.md
└── SECURITY.md
```

## Table of contents (files)

- 1. [.dockerignore](#.dockerignore)
- 2. [.github/ISSUE_TEMPLATE/bug_report.md](#.github-ISSUE_TEMPLATE-bug_report.md)
- 3. [.github/pull_request_template.md](#.github-pull_request_template.md)
- 4. [.github/workflows/ci.yml](#.github-workflows-ci.yml)
- 5. [.github/workflows/docker.yml](#.github-workflows-docker.yml)
- 6. [.github/workflows/pages.yml](#.github-workflows-pages.yml)
- 7. [CODE_OF_CONDUCT.md](#CODE_OF_CONDUCT.md)
- 8. [CONTRIBUTING.md](#CONTRIBUTING.md)
- 9. [frontend/app/__mocks__/expoConstantsMock.js](#frontend-app-__mocks__-expoConstantsMock.js)
- 10. [frontend/app/__mocks__/expoMock.js](#frontend-app-__mocks__-expoMock.js)
- 11. [frontend/app/__mocks__/expoRouterMock.js](#frontend-app-__mocks__-expoRouterMock.js)
- 12. [frontend/app/__tests__/smoke.test.tsx](#frontend-app-__tests__-smoke.test.tsx)
- 13. [frontend/app/app.json](#frontend-app-app.json)
- 14. [frontend/app/App.tsx](#frontend-app-App.tsx)
- 15. [frontend/app/babel.config.js](#frontend-app-babel.config.js)
- 16. [frontend/app/components/SettingsBar.tsx](#frontend-app-components-SettingsBar.tsx)
- 17. [frontend/app/context/Auth.tsx](#frontend-app-context-Auth.tsx)
- 18. [frontend/app/index.ts](#frontend-app-index.ts)
- 19. [frontend/app/jest.config.ts](#frontend-app-jest.config.ts)
- 20. [frontend/app/jest.setup.ts](#frontend-app-jest.setup.ts)
- 21. [frontend/app/jest.setupFiles.js](#frontend-app-jest.setupFiles.js)
- 22. [frontend/app/metro.config.js](#frontend-app-metro.config.js)
- 23. [frontend/app/public/404.html](#frontend-app-public-404.html)
- 24. [frontend/app/public/_config.yml](#frontend-app-public-_config.yml)
- 25. [frontend/app/public/google095bf08db4fb15d0.html](#frontend-app-public-google095bf08db4fb15d0.html)
- 26. [frontend/app/screens/HomeScreen.tsx](#frontend-app-screens-HomeScreen.tsx)
- 27. [frontend/app/screens/HomeScreenUtil.tsx](#frontend-app-screens-HomeScreenUtil.tsx)
- 28. [frontend/app/tsconfig.json](#frontend-app-tsconfig.json)
- 29. [LICENSE](#LICENSE)
- 30. [README.md](#README.md)
- 31. [SECURITY.md](#SECURITY.md)

---

## Files

<a id=".dockerignore"></a>
### 1. `.dockerignore`
- Size: 1877 bytes | LOC: 71 | SLOC: 63 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 4739dbb2b40c

#### Brief
# ─────────────────────────────
# Git / VCS

#### Auto Summary
# ─────────────────────────────

#### Content

```
# ─────────────────────────────
# Git / VCS
# ─────────────────────────────
.git
.gitignore
.gitattributes

# ─────────────────────────────
# Node / package manager
# ─────────────────────────────
node_modules
**/node_modules
npm-debug.log*
yarn-debug.log*
yarn-error.log*
pnpm-debug.log*

# ─────────────────────────────
# Expo / build artifacts
# ─────────────────────────────
.expo
.expo-shared
dist
web-build
web-build-*/
build
coverage
reports

# Expo web export
**/dist
**/web-build

# ─────────────────────────────
# OS / editor
# ─────────────────────────────
.DS_Store
Thumbs.db
desktop.ini
.vscode
.idea

# ─────────────────────────────
# Env / secrets
# ─────────────────────────────
.env
.env.*
*.env
*.env.local
*.env.development
*.env.production

# ─────────────────────────────
# Docker / Compose
# ─────────────────────────────
Dockerfile
Dockerfile.*
docker-compose.yml
docker-compose.*.yml

# ─────────────────────────────
# Logs / scratch files
# ─────────────────────────────
*.log
*.tmp
*.swp
*.swo

# Jest / test outputs
jest-stare
nyc_output
```

<a id=".github-ISSUE_TEMPLATE-bug_report.md"></a>
### 2. `.github/ISSUE_TEMPLATE/bug_report.md`
- Size: 666 bytes | LOC: 30 | SLOC: 24 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 4b4d2b96744a

#### Brief
---
name: Bug Report

#### Auto Summary
Description

#### Content (verbatim)

```markdown
---
name: Bug Report
about: Create a report to help us improve
title: "[Bug] "
labels: bug
assignees: ''
---

## Description
<!-- A clear and concise description of what the bug is -->

## Steps to Reproduce
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

## Expected Behavior
<!-- A clear and concise description of what you expected to happen -->

## Screenshots
<!-- If applicable, add screenshots to help explain your problem -->

## Environment
- OS: [e.g. Ubuntu 22.04]
- Browser/Version: [e.g. Chrome 117]
- Node/Python Version: [e.g. Node 18, Python 3.10]

## Additional Context
<!-- Add any other context about the problem here -->
```

<a id=".github-pull_request_template.md"></a>
### 3. `.github/pull_request_template.md`
- Size: 744 bytes | LOC: 27 | SLOC: 21 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 1b6e1aab4d9a

#### Brief
# Pull Request

#### Auto Summary
Pull Request

#### Content (verbatim)

```markdown
# Pull Request

## Overview
<!-- Briefly describe the purpose of this PR and the problem it solves   -->

## Changes
<!-- List the main changes made in this PR -->
- 

## Testing
<!-- Describe how you tested the changes -->
- [ ] Built and ran locally without errors
- [ ] All tests passed
- [ ] Verified functionality manually (describe how)

## Related Issues
<!-- Link to related issues if applicable -->
- Closes #

## Checklist
- [ ] Code is clean and free of unnecessary comments/debug prints
- [ ] Proper naming conventions and documentation are followed
- [ ] Updated documentation/README if necessary
- [ ] CI pipeline passes successfully

## Notes for Reviewers
<!-- Additional context or things reviewers should pay attention to -->
```

<a id=".github-workflows-ci.yml"></a>
### 4. `.github/workflows/ci.yml`
- Size: 2006 bytes | LOC: 72 | SLOC: 72 | TODOs: 0 | Modified: 2026-10-11 09:50:53 | SHA1: b9ac406a8df1

#### Brief
name: CI
on:

#### Auto Summary
name: CI

#### Content

```yaml
name: CI
on:
  push:
  pull_request:
concurrency:
  group: frontend-ci-${{ github.ref }}
  cancel-in-progress: true
permissions:
  contents: read
jobs:
  test:
    name: Jest on Node ${{ matrix.node }}
    runs-on: ubuntu-latest
    strategy:
      fail-fast: false
      matrix:
        node: [18, 20, 22, 24]
    env:
      CI: "1"
      EXPO_TUNNEL: "false"
      EXPO_DEVTOOLS_LISTEN_ADDRESS: 0.0.0.0
      EXPO_PUBLIC_API_BASE: http://localhost:8000
    steps:
      - name: Checkout
        uses: actions/checkout@v7
      - name: Use Node ${{ matrix.node }}
        uses: actions/setup-node@v6
        with:
          node-version: ${{ matrix.node }}
          cache: npm
          cache-dependency-path: frontend/app/package-lock.json
      - name: Install deps
        working-directory: frontend/app
        run: npm ci
      - name: Run Jest with coverage (CI mode)
        working-directory: frontend/app
        run: npm test -- --ci --runInBand --coverage --verbose
      - name: Upload coverage
        if: always()
        uses: actions/upload-artifact@v6
        with:
          name: coverage-node${{ matrix.node }}
          path: frontend/app/coverage
          if-no-files-found: warn
  web-export-smoke:
    name: Expo web export (smoke)
    needs: test
    runs-on: ubuntu-latest
    env:
      CI: "1"
    steps:
      - name: Checkout
        uses: actions/checkout@v7
      - name: Use Node 24
        uses: actions/setup-node@v7
        with:
          node-version: 24
          cache: npm
          cache-dependency-path: frontend/app/package-lock.json
      - name: Install deps
        working-directory: frontend/app
        run: npm ci
      - name: Build (expo export -p web)
        working-directory: frontend/app
        run: npx expo export -p web
      - name: Upload dist (preview artifact)
        if: always()
        uses: actions/upload-artifact@v7
        with:
          name: expo-web-dist
          path: frontend/app/dist
          if-no-files-found: error
```

<a id=".github-workflows-docker.yml"></a>
### 5. `.github/workflows/docker.yml`
- Size: 846 bytes | LOC: 29 | SLOC: 29 | TODOs: 0 | Modified: 2026-10-11 09:52:08 | SHA1: 5607e74bf32a

#### Brief
name: docker
on:

#### Auto Summary
name: docker

#### Content

```yaml
name: docker
on:
  push:
  pull_request:
  workflow_dispatch:
jobs:
  docker-tests:
    runs-on: ubuntu-latest
    env:
      CI: "1"
      EXPO_TUNNEL: "false"
      EXPO_DEVTOOLS_LISTEN_ADDRESS: 0.0.0.0
      EXPO_PUBLIC_API_BASE: http://localhost:8000
      REACT_NATIVE_PACKAGER_HOSTNAME: 192.168.3.2
    steps:
      - name: Checkout
        uses: actions/checkout@v7
      - name: Set up Docker Buildx
        uses: docker/setup-buildx-action@v4
      - name: Run tests via docker-compose (deterministic CI)
        run: |
          docker compose -f docker-compose.test.yml up --build --exit-code-from frontend_test
      - name: Upload test reports (if mounted)
        if: always()
        uses: actions/upload-artifact@v7
        with:
          name: frontend-reports
          path: reports/frontend
          if-no-files-found: warn
```

<a id=".github-workflows-pages.yml"></a>
### 6. `.github/workflows/pages.yml`
- Size: 1669 bytes | LOC: 60 | SLOC: 60 | TODOs: 0 | Modified: 2026-10-11 09:51:51 | SHA1: 862a8652c6ce

#### Brief
name: GitHub Pages
on:

#### Auto Summary
name: GitHub Pages

#### Content

```yaml
name: GitHub Pages
on:
  push:
    branches: [ "main" ]
  workflow_dispatch:
permissions:
  contents: read
  pages: write
  id-token: write
concurrency:
  group: "pages"
  cancel-in-progress: true
jobs:
  build:
    if: github.ref == 'refs/heads/main'
    runs-on: ubuntu-latest
    steps:
      - name: Checkout
        uses: actions/checkout@v7
      - name: Use Node.js 24
        uses: actions/setup-node@v7
        with:
          node-version: 24
          cache: npm
          cache-dependency-path: |
            frontend/app/package-lock.json
      - name: Install deps
        working-directory: frontend/app
        run: npm ci
      - name: Generate sitemap
        run: |
          LASTMOD="$(git log -1 --format=%cs)"
          cat > frontend/app/public/sitemap.xml <<EOF
          <?xml version="1.0" encoding="UTF-8"?>
          <urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
            <url>
              <loc>https://europanite.github.io/frontend_expo_template/</loc>
              <lastmod>${LASTMOD}</lastmod>
            </url>
          </urlset>
          EOF
          cat frontend/app/public/sitemap.xml
      - name: Build
        working-directory: frontend/app
        run: npx expo export -p web
      - name: Upload Pages artifact
        uses: actions/upload-pages-artifact@v5
        with:
          path: frontend/app/dist
  deploy:
    if: github.ref == 'refs/heads/main'
    needs: build
    runs-on: ubuntu-latest
    environment:
      name: github-pages
      url: ${{ steps.deployment.outputs.page_url }}
    steps:
      - name: Deploy to GitHub Pages
        id: deployment
        uses: actions/deploy-pages@v5
```

<a id="CODE_OF_CONDUCT.md"></a>
### 7. `CODE_OF_CONDUCT.md`
- Size: 4085 bytes | LOC: 68 | SLOC: 50 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 724cc33f0dca

#### Brief
# Contributor Covenant Code of Conduct

#### Auto Summary
Contributor Covenant Code of Conduct

#### Content (verbatim)

```markdown
# Contributor Covenant Code of Conduct

## Our Pledge
We as members, contributors, and leaders pledge to make participation in our community a harassment-free experience for everyone, regardless of age, body size, visible or invisible disability, ethnicity, sex characteristics, gender identity and expression, level of experience, education, socio-economic status, nationality, personal appearance, race, religion, or sexual identity and orientation.

We pledge to act and interact in ways that contribute to an open, welcoming, diverse, inclusive, and healthy community.

## Our Standards
Examples of behavior that contributes to a positive environment include:
- Demonstrating empathy and kindness toward other people
- Being respectful of differing opinions, viewpoints, and experiences
- Giving and gracefully accepting constructive feedback
- Taking responsibility and apologizing to those affected by our mistakes
- Focusing on what is best for the community, not just for ourselves

Examples of unacceptable behavior include:
- The use of sexualized language or imagery, and sexual attention or advances
- Trolling, insulting or derogatory comments, and personal or political attacks
- Public or private harassment
- Publishing others’ private information without explicit permission
- Other conduct which could reasonably be considered inappropriate in a professional setting

## Enforcement Responsibilities
Community leaders are responsible for clarifying and enforcing our standards of acceptable behavior and will take appropriate and fair corrective action in response to any behavior that they deem inappropriate, threatening, offensive,
or harmful.

## Scope
This Code of Conduct applies within all community spaces, and also applies when an individual is officially representing the community in public spaces.

## Enforcement
Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the maintainers of this project. All complaints will be reviewed and investigated promptly and fairly.

All community leaders are obligated to respect the privacy and security of the reporter of any incident.

## Enforcement Guidelines
Community leaders will follow these guidelines in determining the consequences for any action they deem in violation of this Code of Conduct:

1. **Correction**  
- *Impact*: Use of inappropriate language or other behavior deemed unprofessional.  
- *Consequence*: A private, written warning, with clarity around the nature of the violation and an explanation of why the behavior was inappropriate.

2. **Warning**  
- *Impact*: A violation through a single incident or series of actions.  
- *Consequence*: A warning with consequences for continued behavior. No interaction with the people involved, including unsolicited interaction with those enforcing the Code of Conduct, for a specified period of time.

3. **Temporary Ban**  
- *Impact*: A serious violation of community standards, including sustained inappropriate behavior.  
- *Consequence*: A temporary ban from any sort of interaction or public communication with the community for a specified period of time.

4. **Permanent Ban**  
- *Impact*: Demonstrating a pattern of violation of community standards, including sustained inappropriate behavior, harassment of an individual, or aggression toward or disparagement of classes of individuals.  
- *Consequence*: A permanent ban from any sort of public interaction within the
   community.

## Attribution

This Code of Conduct is adapted from the  
- [Contributor Covenant][v2.1], version 2.1, available at [https://www.contributor-covenant.org/version/2/1/code_of_conduct.html][v2.1].

Community Impact Guidelines were inspired by  
- [Mozilla’s code of conduct enforcement ladder][mozilla-coc].

For answers to common questions about this code of conduct, see the FAQ at  
- [Contributor Covenant FAQ][faq].

[v2.1]: https://www.contributor-covenant.org/version/2/1/code_of_conduct.html
[mozilla-coc]: https://github.com/mozilla/diversity
[faq]: https://www.contributor-covenant.org/faq
```

<a id="CONTRIBUTING.md"></a>
### 8. `CONTRIBUTING.md`
- Size: 834 bytes | LOC: 25 | SLOC: 19 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 12ea21d94090

#### Brief
# Contributing Guidelines

#### Auto Summary
Contributing Guidelines

#### Content (verbatim)

```markdown
# Contributing Guidelines

Thank you for considering contributing to this project!  
We welcome bug reports, feature requests, and pull requests.  
Please follow the guidelines below to make the process smooth for everyone.

---

## How to Contribute

### 1. Reporting Issues
- Check the [issue tracker](../../issues) to avoid duplicates.
- Use the appropriate [issue template](.github/ISSUE_TEMPLATE/) when creating a new issue.
- Provide as much detail as possible (steps to reproduce, expected behavior, environment, etc.).

### 2. Suggesting Features
- Open a new **Feature Request** issue.
- Explain the problem your idea solves.
- Provide examples, use cases, or references if possible.

### 3. Submitting Pull Requests
Fork the repository and create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
```

<a id="frontend-app-__mocks__-expoConstantsMock.js"></a>
### 9. `frontend/app/__mocks__/expoConstantsMock.js`
- Size: 97 bytes | LOC: 3 | SLOC: 3 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 042b2b318b7a

#### Brief
module.exports = {
  default: { expoConfig: {}, manifest: null, appOwnership: 'standalone' },

#### Auto Summary
module.exports = {

#### Content

```javascript
module.exports = {
  default: { expoConfig: {}, manifest: null, appOwnership: 'standalone' },
};
```

<a id="frontend-app-__mocks__-expoMock.js"></a>
### 10. `frontend/app/__mocks__/expoMock.js`
- Size: 174 bytes | LOC: 7 | SLOC: 7 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: d58b65ebbe06

#### Brief
const dummy = new Proxy({}, { get: () => undefined });
module.exports = {

#### Auto Summary
const dummy = new Proxy({}, { get: () => undefined });

#### Content

```javascript
const dummy = new Proxy({}, { get: () => undefined });
module.exports = {
  ...dummy,
  registerRootComponent: () => {},
  installExpoGlobals: () => {},
  default: dummy,
};
```

<a id="frontend-app-__mocks__-expoRouterMock.js"></a>
### 11. `frontend/app/__mocks__/expoRouterMock.js`
- Size: 179 bytes | LOC: 7 | SLOC: 7 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: bec4abda4523

#### Brief
module.exports = {
  useRouter: () => ({ push: () => {}, replace: () => {}, back: () => {} }),

#### Auto Summary
module.exports = {

#### Content

```javascript
module.exports = {
  useRouter: () => ({ push: () => {}, replace: () => {}, back: () => {} }),
  useSegments: () => [],
  Slot: () => null,
  Stack: () => null,
  default: {},
};
```

<a id="frontend-app-__tests__-smoke.test.tsx"></a>
### 12. `frontend/app/__tests__/smoke.test.tsx`
- Size: 288 bytes | LOC: 10 | SLOC: 8 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 29a77aa1510f

#### Brief
import React from 'react';
import { Text } from 'react-native';

#### Auto Summary
import React from 'react';

#### Content

```tsx
import React from 'react';
import { Text } from 'react-native';
import { render, screen } from '@testing-library/react-native';

function Hello(){ return <Text testID="hi">hi</Text>; }

test('smoke', async () => {
  render(<Hello />);
  expect(screen.getByTestId('hi')).toBeTruthy();
});
```

<a id="frontend-app-app.json"></a>
### 13. `frontend/app/app.json`
- Size: 755 bytes | LOC: 34 | SLOC: 34 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: c891589da619

#### Brief
{
  "expo": {

#### Auto Summary
{

#### Content

```json
{
  "expo": {
    "name": "app",
    "slug": "app",
    "version": "1.0.0",
    "orientation": "portrait",
    "icon": "./assets/icon.png",
    "userInterfaceStyle": "light",
    "newArchEnabled": true,
    "splash": {
      "image": "./assets/splash-icon.png",
      "resizeMode": "contain",
      "backgroundColor": "#ffffff"
    },
    "ios": {
      "supportsTablet": true
    },
    "android": {
      "adaptiveIcon": {
        "foregroundImage": "./assets/adaptive-icon.png",
        "backgroundColor": "#ffffff"
      },
      "edgeToEdgeEnabled": true
    },
    "experiments": {
      "baseUrl": "/frontend_expo_template"
    },
    "web": {
      "favicon": "./assets/favicon.png",
      "output": "single",
      "bundler": "metro"
    }
  }
}
```

<a id="frontend-app-App.tsx"></a>
### 14. `frontend/app/App.tsx`
- Size: 991 bytes | LOC: 30 | SLOC: 27 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: c327cd2f2101

#### Brief
import React from "react";
import { View } from "react-native";

#### Auto Summary
import React from "react";

#### Content

```tsx
import React from "react";
import { View } from "react-native";
import { NavigationContainer } from "@react-navigation/native";
import { createNativeStackNavigator } from "@react-navigation/native-stack";
import { SafeAreaProvider } from "react-native-safe-area-context";
import { StatusBar } from "expo-status-bar";

import { AuthProvider } from "./context/Auth";
import SettingsBar from "./components/SettingsBar";
import HomeScreen from "./screens/HomeScreen";

const Stack = createNativeStackNavigator();

export default function App() {
  return (
    <SafeAreaProvider>
      <StatusBar style="dark" />
      <AuthProvider>
        <NavigationContainer>
          <SettingsBar />
          <View style={{ flex: 1 }}>
            <Stack.Navigator screenOptions={{ headerShown: false }}>
              <Stack.Screen name="Home" component={HomeScreen} />
            </Stack.Navigator>
          </View>
        </NavigationContainer>
      </AuthProvider>
    </SafeAreaProvider>
  );
}
```

<a id="frontend-app-babel.config.js"></a>
### 15. `frontend/app/babel.config.js`
- Size: 294 bytes | LOC: 15 | SLOC: 15 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: d5c5f238e459

#### Brief
module.exports = function (api) {
  api.cache(true);

#### Auto Summary
module.exports = function (api) {

#### Content

```javascript
module.exports = function (api) {
  api.cache(true);
  return {
    presets: ['babel-preset-expo'],
    env: {
      test: {
        plugins: [
          ['transform-inline-environment-variables', {
            include: ['EXPO_PUBLIC_API_BASE']
          }],
        ],
      },
    },
  };
};
```

<a id="frontend-app-components-SettingsBar.tsx"></a>
### 16. `frontend/app/components/SettingsBar.tsx`
- Size: 1046 bytes | LOC: 33 | SLOC: 30 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 082e903ac4cd

#### Brief
import React from "react";
import { View, useWindowDimensions } from "react-native";

#### Auto Summary
import React from "react";

#### Content

```tsx
import React from "react";
import { View, useWindowDimensions } from "react-native";
import { SafeAreaView } from "react-native-safe-area-context";
import { StatusBar } from "expo-status-bar";

const BAR_BG = "#000000ff";
const CONTENT_MAX_W = 480;

export default function SettingsBar() {
  const { width } = useWindowDimensions();
  const isNarrow = width < 420;

  return (
    <SafeAreaView edges={["top"]} style={{ backgroundColor: BAR_BG }}>
      <StatusBar style="dark" backgroundColor={BAR_BG} />
      <View style={{ backgroundColor: BAR_BG, paddingHorizontal: 12, paddingVertical: 10 }}>
        <View style={{ alignItems: "center" }}>
          <View style={{ width: "100%", maxWidth: CONTENT_MAX_W, gap: 8 }}>
            <View
              style={{
                flexDirection: isNarrow ? "column" : "row",
                alignItems: "center",
                gap: 8,
                flexWrap: "wrap",
              }}
            >
            </View>
          </View>
        </View>
      </View>
    </SafeAreaView>
  );
}
```

<a id="frontend-app-context-Auth.tsx"></a>
### 17. `frontend/app/context/Auth.tsx`
- Size: 1001 bytes | LOC: 35 | SLOC: 25 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 8a2139845413

#### Brief
Simple auth context that stores token/email in memory.
You can later persist it with AsyncStorage if needed.

#### Auto Summary
// Simple auth context that stores token/email in memory.

#### Content

```tsx
// Simple auth context that stores token/email in memory.
// You can later persist it with AsyncStorage if needed.
import React, { createContext, useContext, useState, ReactNode } from "react";

type User = { email: string } | null;

type AuthCtx = {
  user: User;
  token: string | null;
  authHeader: () => Partial<Record<string, string>>;
};

const AuthContext = createContext<AuthCtx | null>(null);

const API_BASE = process.env.EXPO_PUBLIC_API_BASE!;

export function AuthProvider({ children }: { children: ReactNode }) {
  const [token, setToken] = useState<string | null>(null);
  const [user, setUser] = useState<User>(null);

  const authHeader = () =>
    token ? { Authorization: `Bearer ${token}` } : {};

  return (
    <AuthContext.Provider value={{ user, token, authHeader }}>
      {children}
    </AuthContext.Provider>
  );
}

export function useAuth() {
  const ctx = useContext(AuthContext);
  if (!ctx) throw new Error("useAuth must be used within AuthProvider");
  return ctx;
}
```

<a id="frontend-app-index.ts"></a>
### 18. `frontend/app/index.ts`
- Size: 307 bytes | LOC: 8 | SLOC: 3 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: fd1e69b3b668

#### Brief
import { registerRootComponent } from 'expo';

#### Auto Summary
import { registerRootComponent } from 'expo';

#### Content

```typescript
import { registerRootComponent } from 'expo';

import App from './App';

// registerRootComponent calls AppRegistry.registerComponent('main', () => App);
// It also ensures that whether you load the app in Expo Go or in a native build,
// the environment is set up appropriately
registerRootComponent(App);
```

<a id="frontend-app-jest.config.ts"></a>
### 19. `frontend/app/jest.config.ts`
- Size: 1011 bytes | LOC: 29 | SLOC: 29 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 6aa9c9ed7996

#### Brief
module.exports = {
   preset: 'jest-expo',

#### Auto Summary
module.exports = {

#### Content

```typescript
 module.exports = {
   preset: 'jest-expo',
   testEnvironment: 'jsdom',
   setupFilesAfterEnv: ['<rootDir>/jest.setup.ts'],
  moduleNameMapper: {
     '\\.(png|jpe?g|gif|svg)$': '<rootDir>/__mocks__/fileMock.js',
     '\\.(css|scss)$': '<rootDir>/__mocks__/styleMock.js',
     'react-native-reanimated': 'react-native-reanimated/mock',
    '^expo($|/.+)': '<rootDir>/__mocks__/expoMock.js',
    '^expo-router($|/.+)': '<rootDir>/__mocks__/expoRouterMock.js',
    '^expo-constants$': '<rootDir>/__mocks__/expoConstantsMock.js',
   },
  setupFiles: ['<rootDir>/jest.setupFiles.js'],
   transformIgnorePatterns: [
     'node_modules/(?!(react-native'
       + '|@react-native'
       + '|react-clone-referenced-element'
       + '|@react-navigation'
       + '|react-navigation'
       + '|expo(nent)?'
       + '|@expo(nent)?/.*'
       + '|expo-modules-core'
       + '|expo-.*'
       + '|@expo/.*'
       + '|@react-native/polyfills'
     + ')/)',
   ],
   testMatch: ['**/__tests__/**/*.test.(ts|tsx)'],
 };
```

<a id="frontend-app-jest.setup.ts"></a>
### 20. `frontend/app/jest.setup.ts`
- Size: 88 bytes | LOC: 2 | SLOC: 2 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: f764402eb556

#### Brief
import '@testing-library/jest-native/extend-expect';
import '@testing-library/jest-dom';

#### Auto Summary
import '@testing-library/jest-native/extend-expect';

#### Content

```typescript
import '@testing-library/jest-native/extend-expect';
import '@testing-library/jest-dom';
```

<a id="frontend-app-jest.setupFiles.js"></a>
### 21. `frontend/app/jest.setupFiles.js`
- Size: 395 bytes | LOC: 9 | SLOC: 8 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 8572a798e340

#### Brief
if (!Object.getOwnPropertyDescriptor(globalThis, '__ExpoImportMetaRegistry')) {
  Object.defineProperty(globalThis, '__ExpoImportMetaRegistry', {

#### Auto Summary
if (!Object.getOwnPropertyDescriptor(globalThis, '__ExpoImportMetaRegistry')) {

#### Content

```javascript
if (!Object.getOwnPropertyDescriptor(globalThis, '__ExpoImportMetaRegistry')) {
  Object.defineProperty(globalThis, '__ExpoImportMetaRegistry', {
    configurable: true,
    value: { get: () => null, has: () => false },
  });
}

jest.mock('@react-native/animated', () => ({}), { virtual: true });
jest.mock('react-native/Libraries/Animated/NativeAnimatedHelper', () => ({}), { virtual: true });
```

<a id="frontend-app-metro.config.js"></a>
### 22. `frontend/app/metro.config.js`
- Size: 128 bytes | LOC: 3 | SLOC: 3 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 2c699d1e4a93

#### Brief
const { getDefaultConfig } = require('expo/metro-config');
const config = getDefaultConfig(__dirname);

#### Auto Summary
const { getDefaultConfig } = require('expo/metro-config');

#### Content

```javascript
const { getDefaultConfig } = require('expo/metro-config');
const config = getDefaultConfig(__dirname);
module.exports = config;
```

<a id="frontend-app-public-404.html"></a>
### 23. `frontend/app/public/404.html`
- Size: 484 bytes | LOC: 12 | SLOC: 12 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 0ece023f9b6b

#### Brief
<!DOCTYPE html><html><head>
  <meta charset="utf-8"><title>Redirecting...</title>

#### Auto Summary
<!DOCTYPE html><html><head>

#### Content

```html
<!DOCTYPE html><html><head>
  <meta charset="utf-8"><title>Redirecting...</title>
  <script>
    (function(){
      var path = window.location.pathname.replace(/\/frontend_expo_template/, '');
      var search = window.location.search || '';
      var hash = window.location.hash || '';
      var url = '/frontend_expo_template/?redirect=' + encodeURIComponent(path + search + hash);
      window.location.replace(url);
    })();
  </script>
</head><body>Redirecting...</body></html>
```

<a id="frontend-app-public-_config.yml"></a>
### 24. `frontend/app/public/_config.yml`
- Size: 255 bytes | LOC: 10 | SLOC: 10 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 0648166169b0

#### Brief
title: "frontend_expo_template"
description: "A Template For Frontend Expo Development."

#### Auto Summary
title: "frontend_expo_template"

#### Content

```yaml
title: "frontend_expo_template"
description: "A Template For Frontend Expo Development."
baseurl: "/frontend_expo_template"
url: "https://europanite.github.io"
theme: minima
markdown: kramdown
plugins:
  - jekyll-feed
  - jekyll-sitemap
highlighter: rouge
```

<a id="frontend-app-public-google095bf08db4fb15d0.html"></a>
### 25. `frontend/app/public/google095bf08db4fb15d0.html`
- Size: 53 bytes | LOC: 1 | SLOC: 1 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 6d7f2ccca405

#### Brief
google-site-verification: google095bf08db4fb15d0.html

#### Auto Summary
google-site-verification: google095bf08db4fb15d0.html

#### Content

```html
google-site-verification: google095bf08db4fb15d0.html
```

<a id="frontend-app-screens-HomeScreen.tsx"></a>
### 26. `frontend/app/screens/HomeScreen.tsx`
- Size: 872 bytes | LOC: 55 | SLOC: 37 | TODOs: 0 | Modified: 2026-09-11 14:43:58 | SHA1: 9232d916de35

#### Brief
import React from "react";
import {

#### Auto Summary
import React from "react";

#### Content

```tsx
import React from "react";
import { 
  View, 
  Text, 
  TouchableOpacity,
  Linking 
} from "react-native";
import {REPO_URL} from "./HomeScreenUtil" 

export default function HomeScreen() {
  return (
    <View style={{ flex: 1 }}>
      <View
          style={{
            alignSelf: "center",
            width: "100%",
            paddingHorizontal: 12,
            paddingVertical: 10,
            gap: 8,
          }}
      >
        <TouchableOpacity onPress={() => Linking.openURL(REPO_URL)}>
          <Text
            style={{
              fontSize: 24,
              fontWeight: "800",
              marginBottom: 12,
              color: "#333333ff",
              textDecorationLine: "underline",
            }}
          >
            Frontend Expo Template
          </Text>
        </TouchableOpacity>
      </View>
    </View>

  );
}
```

<a id="frontend-app-screens-HomeScreenUtil.tsx"></a>
### 27. `frontend/app/screens/HomeScreenUtil.tsx`
- Size: 169 bytes | LOC: 2 | SLOC: 2 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: f2261476189a

#### Brief
export const REPO_URL      = "https://github.com/europanite/frontend_expo_template";
export const REPO_URL_PAGE = "https://europanite.github.io/frontend_expo_template/";

#### Auto Summary
export const REPO_URL      = "https://github.com/europanite/frontend_expo_template";

#### Content

```tsx
export const REPO_URL      = "https://github.com/europanite/frontend_expo_template";
export const REPO_URL_PAGE = "https://europanite.github.io/frontend_expo_template/";
```

<a id="frontend-app-tsconfig.json"></a>
### 28. `frontend/app/tsconfig.json`
- Size: 231 bytes | LOC: 10 | SLOC: 10 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 76a1a9cc4416

#### Brief
{
  "extends": "expo/tsconfig.base",

#### Auto Summary
{

#### Content

```json
{
  "extends": "expo/tsconfig.base",
  "compilerOptions": {
    "strict": true,
    "moduleResolution": "bundler",
    "lib": ["esnext", "dom"],
    "types": ["jest", "@testing-library/jest-dom", "node"],
    "baseUrl": ".",
  }
}
```

<a id="LICENSE"></a>
### 29. `LICENSE`
- Size: 11340 bytes | LOC: 201 | SLOC: 169 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 64f2208f2896

#### Brief
Apache License
                           Version 2.0, January 2004

#### Auto Summary
Apache License

#### Content

```
                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "[]"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright 2025 europanite

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

<a id="README.md"></a>
### 30. `README.md`
- Size: 1911 bytes | LOC: 54 | SLOC: 36 | TODOs: 0 | Modified: 2026-10-11 09:52:41 | SHA1: 0a8a32ef189f

#### Brief
# [Frontend Expo Template](https://github.com/europanite/frontend_expo_template "Frontend Expo Template")

#### Auto Summary
[Frontend Expo Template](https://github.com/europanite/frontend_expo_template "Frontend Expo Template")

#### Content (verbatim)

```markdown
# [Frontend Expo Template](https://github.com/europanite/frontend_expo_template "Frontend Expo Template")

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
![OS](https://img.shields.io/badge/OS-Linux%20%7C%20macOS%20%7C%20Windows-blue)

[![CI](https://github.com/europanite/frontend_expo_template/actions/workflows/ci.yml/badge.svg)](https://github.com/europanite/frontend_expo_template/actions/workflows/ci.yml)
[![docker](https://github.com/europanite/frontend_expo_template/actions/workflows/docker.yml/badge.svg)](https://github.com/europanite/frontend_expo_template/actions/workflows/docker.yml)
[![GitHub Pages](https://github.com/europanite/frontend_expo_template/actions/workflows/pages.yml/badge.svg)](https://github.com/europanite/frontend_expo_template/actions/workflows/pages.yml)

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
```

<a id="SECURITY.md"></a>
### 31. `SECURITY.md`
- Size: 1181 bytes | LOC: 38 | SLOC: 24 | TODOs: 0 | Modified: 2026-03-17 23:28:06 | SHA1: 647f781fb4b9

#### Brief
# Security Policy

#### Auto Summary
Security Policy

#### Content (verbatim)

```markdown
# Security Policy

## Supported Versions

The following table shows which versions of `frontend_expo_template` are currently being supported with security updates.

| Version | Supported          |
|---------|--------------------|
| main    | :white_check_mark: |

We only provide security updates and fixes for the latest code on the **main** branch.

---

## Reporting a Vulnerability

If you discover a security vulnerability within this project, please help us keep the community safe by following these steps:

- Provide as much detail as possible:
   - A clear description of the vulnerability
   - Steps to reproduce the issue
   - The potential impact
   - Any suggested fixes or mitigations

---

## Security Best Practices for Users

- Always pull the latest image or rebuild the environment to ensure patched dependencies.
- Avoid exposing ports publicly unless necessary.
- Use strong passwords and secrets when connecting to external resources.
- Regularly update Python packages and system dependencies.

---

## Acknowledgements

We deeply appreciate the efforts of security researchers and contributors who help us improve the security of `frontend_expo_template`.
```
