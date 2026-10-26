# Canva Video Walkthrough — GitHub Pages

A responsive 8½-minute walkthrough for editing a 30-second broadcast story in Canva's desktop video editor. Eight steps cover setup, import, trim/split, B-roll, audio, lower thirds, export, and a three-question check. Includes an original schematic of the edit, a cut decision, browser-local progress, and a downloadable checklist.

The 8½-minute estimate covers reading and short checks. Hands-on video editing and upload/export wait times are additional. The page itself does not edit video, play sample footage, or connect to Canva. No student footage is supplied or required to read the lesson. Knowledge-check completion does not verify the student's actual video.

## Deploy on GitHub Pages

1. Create or open the GitHub repository where this lesson should live.
2. Upload the **contents of this folder** to the repository root: `index.html`, `styles.css`, `app.js`, `broadcast-edit-checklist.txt`, and `.nojekyll`. Keep the files together. If using GitHub's upload screen, include `.nojekyll` from a file picker that shows hidden files; it is helpful but not essential for this buildless site.
3. Commit the files to `main` (or your chosen branch).
4. In the repository, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**. Select your branch and **/(root)**, then Save.
6. Wait for GitHub's Pages deployment to finish, then use the site link shown in Settings → Pages.

For a repository already hosting a site, put these files in a `canva-video/` subfolder of its published directory and link to `canva-video/`. Do not replace the existing home page. Relative asset links support GitHub project sites and subfolders. No build, package install, domain, secret, or backend is required. This package has not been uploaded or published to GitHub.

## Preview locally

From this folder, run `python3 -m http.server 8000`, then open `http://localhost:8000/`. Stop with Ctrl+C. You may also open `index.html` directly for a quick preview.

## Content & privacy

- Content: `app.js` (step text, durations, diagrams, quiz) and `index.html` (introduction, notes, final checklist).
- Styling: `styles.css`; system fonts and CSS illustrations, no remote dependencies.
- Sources: official Canva help linked in the expandable teacher notes; checked October 26, 2026. Canva versions and account rollouts can differ.
- Timings: 45 + 60 + 75 + 90 + 60 + 60 + 60 + 60 = 510 seconds (8:30).
- Progress: localStorage key `khs-canva-video-v1`. Reset progress clears the lesson state. No analytics, uploads, student names, or teacher submission.
- Checklist boxes below the lesson are temporary and not saved. The text checklist can be downloaded separately.
- Uses fictional example name and campus story; not an official Canva course. No Canva or Microsoft logos or screenshots.

Publishing reference: [GitHub Pages source configuration](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Verification

JavaScript syntax and local file references checked. Desktop browser checks passed for all eight steps, quiz correction feedback, completion guard, successful completion, saved progress after reload, and reset. Responsive layouts are included; a separate mobile-browser test was not performed. No GitHub deployment was performed.
