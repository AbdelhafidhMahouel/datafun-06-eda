# datafun-06-eda

**Created by:** Abdelhafidh Mahouel  
**Date:** 2026-02-16

## Clone the Repository from GitHub (One Time Only)

1. Open Terminal
2. Navigate to the working folder:
```bash
cd C:/Repos
```
3. Clone the repository:
```bash
git clone https://github.com/AbdelhafidhMahouel/datafun-06-eda.git
```
4. Navigate into the project folder:
```bash
cd datafun-06-eda
```
5. Open the project in VS Code:
```bash
code .
```

## Pull Updates from GitHub

Before starting work on the project, pull the latest updates:
```bash
git pull
```

## Set Up the Virtual Environment (Windows)

When working on this project for the first time, set up the Python virtual environment:

1. Create the virtual environment:
```bash
py -m venv .venv
```

2. Activate the virtual environment:
```bash
.venv\Scripts\Activate
```

3. Install project dependencies:
```bash
py -m pip install -r requirements.txt
```

## Notes
- The `.venv/` folder is excluded using `.gitignore`.
- The VS Code Python interpreter is set to the `.venv` environment.

## After Making Changes

After making changes to the project files, run:
```bash
git add .
git commit -m "after .venv setup"
git push -u origin main
```