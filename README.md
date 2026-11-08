# AOAOK Departmental Test Exam Portal

Official online examination portal for the **Association of Agricultural Officers Kerala (AOAOK)**.

## Quick Deployment to GitHub Pages (2 Minutes)

1. Create a new GitHub repository: `exam-portal`
2. Drag and drop `index.html` (and optionally `CNAME`) into your repository.
3. Go to **Settings** -> **Pages** -> under **Branch** select `main` -> **Save**.
4. Your portal is live at: `https://<your-username>.github.io/exam-portal/`

## Custom Domain (exam.aoaok.in)
- Under Pages -> Custom domain, enter: `exam.aoaok.in`
- In your domain DNS manager, add a CNAME record:
  - Host: `exam`
  - Points to: `<your-username>.github.io`

## Connecting to Google Sheets Backend
- On first opening the portal on GitHub, enter your Google Apps Script Web App URL when prompted.
- All questions, candidates, timer sync, and results will automatically flow to your Google Sheets!
