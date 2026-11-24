josephpro600 GitHub Profile — Setup Guide
Files in this package
- README.md — profile page content, dark-blue theme, typing SVG, clickable project cards, technology icons, stats and trophy widgets.
- .github/workflows/snake.yml — optional daily GitHub contribution snake generator.
1. Create the special profile repository
1. Sign in to GitHub as josephpro600.
2. Create a public repository named exactly josephpro600.
3. Initialize it with a README, or use an existing repository with that exact name.
4. The repository URL should be https://github.com/josephpro600/josephpro600.
GitHub displays the repository's README on your profile because the repository name matches your username.
2. Upload the README
1. Open https://github.com/josephpro600/josephpro600.
2. Open README.md and choose Edit, or choose Add file → Upload files.
3. Replace the README contents with the README.md in this package.
4. Commit the change to the main branch.
3. Add the optional snake workflow
1. In the profile repository, choose Add file → Create new file.
2. Enter this exact path: .github/workflows/snake.yml.
3. Paste the contents of .github/workflows/snake.yml from this package.
4. Commit to main.
5. Open the repository's Actions tab and run Generate Contribution Snake using Run workflow.
6. After the run succeeds, the workflow publishes generated SVGs to the output branch.
The snake is optional; the typing animation in the README works independently. If the workflow is blocked, check Settings → Actions → General and allow actions to run with write permissions for repository contents.
4. Confirm the profile
Open https://github.com/josephpro600 and refresh. The profile README should appear beneath your profile details.
5. Update project repository links
These exact repository links are known:
- ImariYange: https://github.com/josephpro600/ImariYange
- Smart Akazi Hub: https://github.com/josephpro600/smart-akazi-hub
The Nova AI, Rwanda Jobs Portal, Library Management System and TaskFlow repository URLs were not confirmed. Their cards currently link to your repository list rather than inventing repository names. Once you know the exact URLs, edit the corresponding href values in README.md.
Notes
- GitHub README files do not execute JavaScript, React or custom CSS. The typing effect is an externally hosted animated SVG.
- External badge, stats and animation services may occasionally be unavailable or rate-limited.
- The snake workflow is an additional contribution animation and is not required for the typing slideshow.
