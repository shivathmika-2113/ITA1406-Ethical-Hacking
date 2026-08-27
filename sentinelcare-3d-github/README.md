# SentinelCare 3D Healthcare Network Security Demo

> A browser-only, white-and-dark-blue, **3D animated college-project demonstration** of healthcare network reconnaissance, AI-assisted analysis, and alert-response management.

SentinelCare translates the three modules in the project brief into an interactive application. It is intentionally a **safe academic demonstration**: no sign-in, server, database, real Nmap command, network connection, patient data, or third-party API is required.

## Run the Project in Chrome

After downloading or cloning this repository, double-click **`OPEN_IN_CHROME.bat`** on Windows. Chrome opens the project immediately. You can also open `index.html` directly in Chrome.

No `npm install`, `pnpm`, Node.js, terminal command, or account is needed to run the application.

## Open in VS Code

Open the complete project folder in VS Code. The primary source files are organized as follows:

| File or folder | Purpose |
|---|---|
| `index.html` | Application structure and all visible interface sections. |
| `src/styles.css` | White-and-dark-blue visual theme, responsive design, and 3D animations. |
| `src/app.js` | Local interactions, safe scan simulation, risk analysis, and response-state changes. |
| `assets/` | Place screenshots, diagrams, icons, or project images here. |
| `docs/` | Project explanation, ethical-use statement, and final demonstration script. |
| `scripts/` | Static project validation script and helper launch files. |
| `.github/workflows/` | Optional GitHub Pages deployment workflow. |

Save any change and refresh Chrome to see it.

## Three Project Modules

| Module | Demonstrable feature |
|---|---|
| **Module 1: Network Reconnaissance and Vulnerability Assessment** | Interactive, ethical Nmap `-sV` **simulation** of an approved lab asset, with open-service observations and exposure-baseline review. |
| **Module 2: AI Intrusion Detection and Attack Analysis** | Safe, local rule-based analysis of sanitized training scenarios, including attack category, priority, confidence, recommendation, and correlation hint. |
| **Module 3: Security Alert and Response Management** | Synthetic alert triage and a human-in-the-loop incident ledger that moves through triage, containment, validation, and closure. |

## GitHub Upload Steps

1. Create a new repository on GitHub, for example `sentinelcare-3d-security-demo`.
2. Extract this ZIP file.
3. Upload **all files and folders inside this project folder** to the repository. Do not upload only `index.html`.
4. Commit the files.
5. Optional: open **Settings → Pages**, select **GitHub Actions** as the source, and push the repository. The included workflow publishes the static app.

For command-line Git users, see [`docs/GITHUB_UPLOAD_GUIDE.md`](docs/GITHUB_UPLOAD_GUIDE.md).

## Important Safety Note

The Nmap screen is a visual simulation only. It never executes a command, contacts an IP address, performs exploitation, tests credentials, or connects to a hospital system. Use only authorized data and never include patient information, credentials, or personally identifiable information.

Read [`docs/ETHICAL_USE.md`](docs/ETHICAL_USE.md) before describing the system as a real-world security solution.

## Local Verification

If Node.js is available, you can verify the static file structure with:

```bash
npm run verify
```

This command is optional; it is not required to run the project.
