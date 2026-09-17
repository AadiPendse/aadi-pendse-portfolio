# aadipendse.com

Personal portfolio site for Aadi Pendse — Computer Science student at Worcester Polytechnic Institute (WPI). The site showcases projects, experience, and technical skills, and serves as a central hub for Summer 2027 internship outreach.

**Live site:** [aadipendse.com](https://aadipendse.com/)

## Overview

This site includes:

- **About** — background in Computer Science and Applied Mathematics
- **Projects** — selected technical projects, including a distributed life-safety test system, a C-based RREF matrix solver, and a Python GPA calculator
- **Experience & Leadership** — WPI VEX Robotics Club and independent e-commerce work
- **Skills** — programming languages, tools, and core technical areas
- **Education** — WPI coursework and GPA
- **Resume** — downloadable PDF
- **Contact** — email and LinkedIn

## Tech Stack & Infrastructure

- **Hosting:** [Netlify](https://www.netlify.com/) — serves the site via serverless cloud infrastructure, with automatic builds and global CDN delivery
- **Version Control & Deployment:** [GitHub](https://github.com/) — the connected repository controls the deployed version; pushes to the main branch trigger a new Netlify build and deploy
- **Frontend:** HTML, CSS
- **Deployment model:** Static site, deployed serverlessly (no dedicated backend server to manage or maintain)

## Deployment Workflow

1. Changes are made locally and committed to the GitHub repository.
2. Pushing to the main branch triggers Netlify's build pipeline.
3. Netlify builds and deploys the updated site automatically.
4. The live site at aadipendse.com reflects the latest deployed commit.

## Local Development

```bash
# Clone the repository
git clone https://github.com/AadiPendse/aadi-pendse-portfolio
cd aadi-pendse-portfolio

# Open index.html directly in a browser, or serve locally:
python3 -m http.server 8000
# then visit http://localhost:8000/index.html
```

Then visit `http://localhost:8000` in your browser.

## Contact

- **Email:** [pendseaadi@gmail.com](mailto:pendseaadi@gmail.com)
- **Linkedin:** [linkedin.com/in/aadi-pendse-036588169](https://www.linkedin.com/in/aadi-pendse-036588169/)
