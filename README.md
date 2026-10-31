# Lower ISEE Math Mastery Pathway

A self-contained static website with a 36-question math diagnostic, personalized lessons for 12 topics, 5-question skill mastery checks, a distinct 36-question final assessment, and a printable growth report.

## Publish to GitHub Pages

1. Create a new GitHub repository (for example, `lower-isee-math-mastery`).
2. Upload `index.html`, `style.css`, `data.js`, and `app.js` to the **root** of the repository, keeping the filenames unchanged.
3. Open **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, and save.
4. Once GitHub finishes deployment, open the Pages URL shown in Settings.

You may also test the activity locally by opening `index.html` in a browser.

## Important notes

- The application uses **browser localStorage**. Progress is saved on the same browser/device but is **not** synchronized between devices, accounts, or teachers.
- No Firebase authentication or cloud database is configured. The supplied ACT reference included Firebase server-side code, but that code cannot safely be copied into an independent static site without a separate Firebase project, rules, and configuration.
- Retaking the diagnostic resets earlier practice results and the final assessment.
- The final check is available after the diagnostic. The teacher can decide when the student is ready; it is not locked behind every module.
- Questions are original and inspired by Lower ISEE math skills and formats. This is not an official ERB exam, and scores are not official ISEE scaled scores.


## Import / export progress

Open **Import / Export** in the top navigation. **Download progress backup** saves a JSON file with assessments, skill mastery, practice attempts, and any unfinished activity. To restore it on another device, open the same website, choose the JSON file, and click **Import progress**. Import replaces the current browser's progress after confirmation. Backups are local files; no server account or cloud synchronization is required. Keep backup files private because they contain student names and learning records.
