# Unit 003 — How to Create a Project and Run Your Code Locally in VS Code
- Track step 3/64 · Module: Working with Code Editors and IDEs
- Attribution: fleet run 41351867794 · model c4ai-aya-expanse-32b (cohere) · status pending (fidelity gate)
## Notes (summary)
- VS Code project = "workspace" = the directory opened. Create via CLI: home dir (`cd /d %USERPROFILE%` cmd / `cd ~` PowerShell/Terminal), `mkdir my-project`, open folder in VS Code (explorer context menu, app, or `code /path/to/folder`; macOS needs Shell Command: Install 'code' command in PATH first).
- New file via File > New File, e.g. index.html. Serve with Live Server extension (Go Live, http://localhost:5500/) instead of opening the file directly (avoids CSS loading bugs).
## Live checks (verbatim, signed-in UI 2026-11-01)
1. What does VS Code consider a "workspace"? -> The directory you opened in VS Code.
2. Why use a web server instead of opening HTML directly? -> It avoids unexpected bugs, such as CSS not loading properly.
3. Extension for easily setting up a local web server? -> Live Server.
Control: "Check your answer" (single, all 3).