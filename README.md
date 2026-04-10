# IA2 Personal Job-Seeking Website (GitHub Pages)

This folder now contains a complete IA2 website starter that already matches the assignment structure and rubric focus.

## Files
- `index.html`: One-page website with all 6 required IA2 sections.
- `styles.css`: Responsive, mobile-friendly styling.
- `content-template.md`: Fill-in template for replacing placeholders.
- `GU_Jialin_Resume_AI_CV.pdf`: final one-page resume used by website Resume section.
- `submission_word_template.txt`: Source text for Word submission file.
- `IA2_Submission.docx`: Word submission document (generated from template).

## IA2 Requirement Coverage
- Platform: GitHub Pages compatible static site.
- 6 required sections included:
  - Home / Headline
  - About Me
  - Skills (Technical / Business / Tools)
  - Projects (2 project cards, each with full required fields)
  - Resume / CV
  - Contact (Email required)
- Word submission document included (`Name / Student ID / Website URL`).

## What You Should Verify Before Final Submission
- Confirm project repository/report links if you want direct per-project links instead of profile-level links.
- After deployment, update `Website URL` in `submission_word_template.txt` and regenerate `IA2_Submission.docx` if needed.
- Confirm the final resume file is `GU_Jialin_Resume_AI_CV.pdf`.

## Deploy to GitHub Pages

## 1) Initialize local git repo (if needed)
```bash
git init
git add .
git commit -m "Initial IA2 website"
```

## 2) Create your GitHub repository
Create a repo on GitHub, for example: `ia2-job-website`.

## 3) Connect and push
```bash
git remote add origin https://github.com/<your-username>/ia2-job-website.git
git branch -M main
git push -u origin main
```

## 4) Enable GitHub Pages
On GitHub repo page:
- Settings -> Pages
- Source: `Deploy from a branch`
- Branch: `main` and folder `/ (root)`
- Save

Your URL will be:
`https://<your-username>.github.io/ia2-job-website/`

## 5) Final QA
- All links open successfully.
- Mobile layout is readable.
- Project A and B include all required fields.
- Word file has your real `Name`, `Student ID`, and final website URL.

## Local Preview
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000/`.

## Word Submission
Edit `IA2_Submission.docx` with your real values and submit it to LMS.
