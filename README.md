# HealConnect Prototype - GitHub Actions Build (Windows portable .exe)

This repository is ready to be pushed to GitHub. The included GitHub Actions workflow will build a portable one-click Windows `.exe`
using **electron-builder** and upload it as a workflow artifact you can download.

## How to use

1. Create a new GitHub repository and push the contents of this folder to the `main` branch.
2. On GitHub, go to **Actions** → trigger the workflow (it runs automatically on push).
3. After the workflow completes, open the workflow run and download the artifact named **healconnect-windows-portable**.
4. The downloaded `.exe` is a portable, one-click app. Double-click to run.

Notes:
- The build uses the `build/icon.ico` included here (a simple stethoscope-like icon). If you prefer a different icon, replace `build/icon.ico` before pushing.
- The workflow installs dependencies and runs `electron-builder`; the build may take several minutes.
- If you want me to push this repository to GitHub for you and trigger the build, I can provide exact commands and the files as a zip.