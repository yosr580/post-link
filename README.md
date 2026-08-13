# Operation Mentor

An interactive, single-page quiz experience for exploring team projects. Users choose an agent, identify the project they think the agent built, and answer a short quiz.

## Requirements

- [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/downloads)
- A modern web browser such as Chrome, Edge, or Firefox
- Optional: Python 3 for a local development server

No Node.js installation, packages, or build step is required. This project is a static HTML site.

## Open the project in VS Code

1. Open a terminal.
2. Clone the repository:

   ```bash
   git clone https://github.com/yosr580/post-link.git
   ```

3. Enter the project folder:

   ```bash
   cd post-link
   ```

4. Open it in VS Code:

   ```bash
   code .
   ```

5. In VS Code, open `index.html`.

## Run the site locally

### Option 1: Open the file directly

Double-click `index.html`, or right-click it in VS Code and choose **Reveal in File Explorer**, then open it in a browser.

### Option 2: Use a local server (recommended)

From the project folder, run:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

To stop the server, return to the terminal and press `Ctrl + C`.

## Project structure

```text
post-link/
├── avatars/       # Agent portrait images
├── index.html     # Application markup, styles, quiz data, and behavior
└── README.md      # Setup instructions
```

## Make changes and share them

1. Edit `index.html` or add images in `avatars/`.
2. Test locally in the browser.
3. Commit and push your changes:

   ```bash
   git add .
   git commit -m "Describe your change"
   git push
   ```

## Access for other users

The GitHub repository is currently private. To let another person clone it, add them as a collaborator in GitHub:

1. Open the repository on GitHub.
2. Select **Settings**.
3. Open **Collaborators** under **Access**.
4. Invite them with their GitHub username or email.

After accepting the invitation, they can follow the cloning steps above in their own VS Code installation.
