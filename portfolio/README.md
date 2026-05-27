# Ragasudha M. — PMM Portfolio

Personal portfolio site built for GitHub Pages. No build tools, no dependencies — just HTML and CSS.

## Structure

```
portfolio/
├── index.html                          ← Main portfolio page
├── work/
│   ├── atlassian-automation-gtm.html   ← Case study (add your content)
│   ├── competitive-intelligence.html   ← Case study (add your content)
│   ├── hcl-onetest-gtm.html            ← Case study (add your content)
│   └── analyst-relations.html          ← Case study (add your content)
├── workflows/
│   ├── competitive-intelligence-workflow.html  ← Full AI workflow (complete)
│   ├── persona-workflow.html           ← Add your content
│   ├── positioning-workflow.html       ← Add your content
│   └── sales-enablement-workflow.html  ← Add your content
└── Ragasudha_PMM_Resume.pdf            ← Drop your resume PDF here
```

## How to deploy on GitHub Pages

1. Create a new GitHub repo named `yourusername.github.io`
   (e.g. `mragasudha.github.io`)

2. Upload all files in this folder to the root of that repo

3. Go to repo Settings → Pages → Source: Deploy from branch → main → / (root)

4. Your site will be live at `https://yourusername.github.io` within 2-3 minutes

## How to customize

### Update your name/info
- Open `index.html` and search for "Ragasudha" — update name, email, LinkedIn URL throughout

### Add your resume PDF
- Drop your PDF in the root folder named `Ragasudha_PMM_Resume.pdf`
- Or update the link in `index.html` (search for `Ragasudha_PMM_Resume.pdf`)

### Add case study pages
- Copy the structure from `workflows/competitive-intelligence-workflow.html`
- Fill in your real work content in the `work/` files
- Link them from `index.html` (already wired up)

### Add more workflow pages
- Copy `competitive-intelligence-workflow.html` as a template
- Fill in your actual prompts and process

## LinkedIn profile tip
Add your portfolio URL to your LinkedIn profile under:
Contact info → Website → Label it "PMM Portfolio"

This gives recruiters a one-click path from your profile to your work.
