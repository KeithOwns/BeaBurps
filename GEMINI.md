## Gemini Added Memories

- **File Backups:**
  * Whenever you are about to modify a project file using a tool, you must first create a copy of the original file inside the `Archive` folder.
  * **Exclusions:** Do not create backups for `HISTORY.md`, files already located inside the `Archive` folder, or temporary build/dependency files (e.g., `.git/`, `node_modules/`, `.tmp`, `.log`, `.bak`).
  * **Structure:** Replicate the file's original folder path structure inside the `Archive/` directory to avoid filename collisions (e.g., backup `src/db.js` to `Archive/src/db.js`).
