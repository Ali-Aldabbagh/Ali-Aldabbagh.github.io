# Ali Aldabbagh, Ph.D. — Personal Website
 
**Live site:** https://ali-aldabbagh.github.io
 
Personal research page covering my work in autonomous systems, LiDAR perception, multi-sensor fusion, and deep learning, along with my projects and datasets.
 
- **Publications:** [Google Scholar](https://scholar.google.com/citations?user=85PzhhkAAAAJ)
- **Contact:** ali.h.aldabbagh@gmail.com
---
 
## Updating the site
 
Everything is in `index.html`. The site is plain HTML with no build step.
 
### Add a link to a project or dataset
Near the bottom of `index.html` you'll find the `PROJECTS` and `DATASETS` lists. Paste a URL into any link:
 
```js
links: { Code: "https://github.com/Ali-Aldabbagh/your-repo", Paper: "", Video: "" }
```
 
Empty links show "Link coming soon". To add a new project, copy an existing `{ ... }` block and edit its text.
 
### Add a profile photo
Put a square photo named `profile.jpg` in this folder. It appears automatically.
 
### Publish changes
From `C:\Users\hp\Documents\git_Ali`:
 
```
git add -A
git commit -m "Update site"
git push
```
 
The live site refreshes within 1–2 minutes.
 
## Tips for datasets and citations
- Upload large datasets to [Zenodo](https://zenodo.org) to get a citable DOI, then link it in `DATASETS`.
- Add a `CITATION.cff` file to each code repo so GitHub shows a "Cite this repository" button.
