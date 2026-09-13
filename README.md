# react-native-device-info

> Device Information for React Native iOS and Android

---

## Table of Contents

1. [Overview](#overview)
2. [Tech Stack](#tech-stack)
3. [Repository Structure](#repository-structure)
4. [Key Components](#key-components)
5. [Setup & Installation](#setup--installation)
6. [Running the Application](#running-the-application)
7. [Infrastructure & CI/CD](#infrastructure--cicd)
8. [Contributing](#contributing)

---

## Overview

**react-native-device-info** is part of the [Unacademy](https://github.com/unacademy) engineering ecosystem.

Device Information for React Native iOS and Android

**Topics / Tags:** _None_

---

## Tech Stack

| Attribute | Value |
|-----------|-------|
| **Primary Language** | Unknown |
| **Framework / Platform** | React Native |
| **Package Manager** | — |

### Dependencies

**Dev Dependencies:**
- `@react-native-community/eslint-config`
- `@semantic-release/changelog`
- `@semantic-release/commit-analyzer`
- `@semantic-release/git`
- `@semantic-release/github`
- `@semantic-release/npm`
- `@semantic-release/release-notes-generator`
- `@testing-library/react-hooks`
- `@types/jest`
- `@types/react`


---

## Repository Structure

```
react-native-device-info/
├── .flowconfig
├── .github/
│   ├── .npmignore
│   ├── ISSUE_TEMPLATE
│   ├── issue_template.md
│   ├── pull_request_template.md
│   ├── workflows
├── .gitignore
├── .husky/
│   ├── .gitignore
│   ├── pre-commit
├── .prettierrc
├── .prettierrc.json
├── .releaserc
├── CHANGELOG.md
├── CODEOWNERS
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── LICENSE
├── MAINTAINERS.md
├── README.md
├── RNDeviceInfo.podspec
├── __tests__/
│   ├── async-hook-wrappers.test.ts
│   ├── getters.test.ts
│   ├── supported-platform-info.test.ts
├── android/
│   ├── .npmignore
│   ├── build.gradle
│   ├── gradle
│   ├── gradlew
│   ├── gradlew.bat
├── babel.config.js
├── example/
│   ├── .buckconfig
│   ├── .eslintrc.js
│   ├── .flowconfig
│   ├── .gitattributes
│   ├── .gitignore
... (truncated)
```

---

## Key Components

Below is an analysis of the key files and modules:

| File / Directory | Purpose |
|-----------------|---------|
| `CHANGELOG.md` | Source file |
| `CODEOWNERS` | Source file |
| `CODE_OF_CONDUCT.md` | Source file |

> **Note:** Only the first 20 non-trivial files are listed. See the repository tree above for the complete structure.

---

## Setup & Installation

### Prerequisites

- Git (`git --version`)
- Unknown runtime installed



### Steps

```bash
git clone git@github.com:unacademy/react-native-device-info.git
cd react-native-device-info
# Follow language-specific setup
```

### Available Scripts

```bash
# analyze
npm run analyze   # yarn ts-check && yarn flow-check

# flow-check
npm run flow-check   # npx flow-bin check-contents < src/index.js.flow

# ts-check
npm run ts-check   # npx tsc --noEmit

# clean
npm run clean   # cd example && npx react-native-clean-project --keep-node-modules --remove-iOS-build --remove-iOS-pods --remove-android-build --clean-android-project --keep-brew --keep-pods && \rm -fr ios/Pods

# dev-sync
npm run dev-sync   # yarn build && cp -r package.json *podspec lib windows android ios src jest example/node_modules/react-native-device-info/

# lint
npm run lint   # npx eslint ./ --ignore-pattern example --ignore-pattern node_modules --fix --quiet

# shipit
npm run shipit   # yarn clean && semantic-release

# example:install
npm run example:install   # yarn && cd example && yarn && cd .. && yarn dev-sync

# example:install:pods
npm run example:install:pods   # cd example/ios && pod install

# example:android
npm run example:android   # cd example && yarn android

```


---

## Running the Application

_Refer to the project's build system or CI configuration._

---

## Infrastructure & CI/CD

- CI/CD pipeline configured (`.github/workflows` or equivalent)
- Test suite present — run tests before submitting PRs

---

## Contributing

1. Create a feature branch: `git checkout -b feat/your-feature`
2. Commit your changes: `git commit -m "feat: describe your change"`
3. Push and open a PR targeting `master`
4. Ensure all CI checks pass before requesting review

---

## Original README (Excerpt)

> <!-- markdownlint-disable MD024 MD034 MD033 -->

# react-native-device-info

[![npm version](https://badge.fury.io/js/react-native-device-info.svg)](http://badge.fury.io/js/react-native-device-info)
[![npm total downloads](https://img.shields.io/npm/dt/react-native-device-info.svg)](https://img.shields.io/npm/dt/react-native-device-info.svg)
[![npm monthly downloads](https://img.shields.io/npm/dm/react-native-device-info.svg)](https://img.shields.io/npm/dm/react-native-device-info.svg)
[![npm weekly downloads](https://img.shields.io/npm/dw/react-native-device-info.svg)](https://img.shields.io/

---

*This README was auto-generated on 2026-09-14 by the Unacademy repo-summarizer tool.*
*For corrections or additions, edit this file directly or open an issue.*
