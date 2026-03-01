# Project Retrospective: The Beginner's Barbell

**Date:** March 1, 2026  
**Project Manager / Developer:** Greg Gaines

## 1. What went well?
* **Scope Management:** Defining a strict scope early on (`scope.md`) kept the project highly focused. By explicitly excluding complex features like JavaScript and backend databases, I was able to dedicate my time to creating clean, semantic HTML and well-structured CSS.
* **Design & Styling:** Integrating simple fonts and free-to-use images significantly elevated the professional look of the site without adding technical complexity. 
* **The Planning Phase:** Breaking the project down into distinct phases (Content, HTML, CSS, Deployment) using the Work Breakdown Structure in my `plan.md` made the workload feel manageable and organized.

## 2. What went wrong?
* **Deployment Discrepancies:** The biggest hurdle occurred during the deployment phase to GitHub Pages. While my images loaded perfectly on my local computer, they initially broke when the site went live. I learned the hard way that local environments are often case-insensitive, while live web servers (like GitHub) are strictly case-sensitive regarding file names and folder paths.

## 3. What would I do differently next time?
* **Stricter Naming Conventions:** Moving forward, I will adopt a strict, all-lowercase naming convention for all files and folders (e.g., `images/` instead of `Images/`, and `squat.jpg` instead of `Squat.JPG`) from day one to prevent deployment errors.

* **Continuous Deployment / Early Testing:** Instead of waiting until the entire website is finished to upload and turn on GitHub Pages, I will upload a basic "skeleton" version of the site early in the process. This will allow me to test how files behave on the live server continuously, catching path errors before they pile up at the end of the project.
