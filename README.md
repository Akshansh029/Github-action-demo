# GitHub Actions Demo

This repository is a personal sandbox for learning and practicing GitHub Actions — GitHub’s powerful CI/CD and automation tool.
Here, I explore how to automate workflows, run tests, deploy applications, and more.

## What I’m Learning

- Setting up basic workflows using .github/workflows
- Running jobs on push/pull requests
- Using environment variables and secrets
- Creating custom workflows for build/test/deploy
- Exploring matrix builds and conditional logic
- Using marketplace actions

## Using demo app

1. build the project

```
./gradlew build
```

2. build Docker image called java-app. Execute from root

```
docker build -t java-app .
```

3. push image to repo

```
docker tag java-app demo-app:java-1.0
```
