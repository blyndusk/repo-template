# PSOC-front

> Primary School Online Course - Front

## I - Install

```bash
git clone https://github.com/blyndusk/PSOC-front
git config core.hooksPath .githooks
chmod +x ./.githooks/commit-msg
```

## II - Workflow Rules

### Branches

```bash
 └── master
     └── develop
         ├── feature/your-branch
         └── fix/your-branch
```

- **NEVER** directly push to `master` branch
- **NEVER** directly push to `develop` branch
  - **ALWAYS** work on **YOUR BRANCH** cloned from `develop` branch
  - **ALWAYS** do a **MERGE REQUEST** from **YOUR BRANCH** to `develop` branch
- **ALWAYS** name your branch like that:
  - `feature/name-of-the-feature`
  - `fix/name-of-the-fix`

### III - Commits

- **ALWAYS** name your commit message like that
  - `"(Add|Fix|Remove|Update): commit message"`
- **ELSE**, your commit will be rejected by **Git hooks**

## IV - Stack

- [Nodejs](https://nodejs.org)
- [Hapijs](https://hapi.dev)

## V - Team

- Maxime CHARPENTIER
- Sophia GOUNANI 
- Alexandre DELALOY
- Nancy CAMPBELL
- Nino LAMOUREUX
- Jason GOUROVITCH
- Nicolas MARTIN