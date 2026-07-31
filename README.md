# theekshana.github.io

A personal portfolio website built as coursework for **System Analysis and Design (SAD)**, showcasing my education, skills, projects and experience for internship/employment applications.

**Live site:** _(coming soon — will be added after deployment)_
**Author:** [Theekshana Thathsara Mallawaarachchi] — [theekshanathathsara1.com]

---

## Project Status
🟡 **In Progress** — Planning & Analysis phase complete (Week 1, Day 1)

---

## 1. Problem Statement

I currently have no centralized, professional platform to present my skills, education and project work to potential employers. A traditional CV alone doesn't show practical, verifiable evidence of my abilities, and my work is scattered across different platforms with no single link to share.

## 2. Objectives

- Create a mobile-responsive personal portfolio website within the 3-week project timeline.
- Showcase at least 3 real projects with clear problem, contribution, tools used and links.
- Enable visitors to view or download my CV in under 2 clicks.
- Provide direct, working links to my LinkedIn and GitHub profiles.
- Deploy the site on a free, publicly accessible platform (GitHub Pages).

## 3. Stakeholders

| Stakeholder | Role |
|---|---|
| Me (Owner/Developer) | Builds, maintains and updates the portfolio |
| Employers / Recruiters | Primary users — view my profile to assess fit for roles |
| Academic Evaluators | Secondary users — assess the site against SAD coursework criteria |

## 4. Scope

**In scope:**
- Static, single-page portfolio (Home, About, Education, Skills, Projects, Experience, CV, Contact)
- Mobile-responsive design
- Downloadable CV in PDF format
- Links to LinkedIn, GitHub and email

**Out of scope:**
- Backend/database functionality
- User login or authentication
- Blog/CMS features
- Payment or e-commerce functionality

## 5. Constraints

- 2–3 week development timeline (coursework deadline)
- No backend allowed per assignment requirements
- Must be hosted on a free platform
- Must remain publicly accessible during evaluation

## 6. Requirements

### Functional Requirements
- FR1: The system shall display the user's name, title and introduction on the Home page.
- FR2: The system shall allow visitors to navigate to all sections via a menu.
- FR3: The system shall allow visitors to view or download the CV as a PDF.
- FR4: The system shall display at least 3 projects with problem, contribution, tools used and links.
- FR5: The system shall provide clickable links to LinkedIn and GitHub.
- FR6: The system shall display education, skills and experience information clearly.

### Non-Functional Requirements
- NFR1: The website shall load within 3 seconds on a standard broadband connection.
- NFR2: The website shall be responsive across mobile, tablet and desktop screen widths.
- NFR3: The website shall be accessible (readable font sizes, sufficient color contrast).
- NFR4: The website shall be hosted on a free, publicly accessible platform with high uptime.

## 7. Planned Tech Stack

- HTML5, CSS3, JavaScript
- Bootstrap (styling)
- GitHub Pages (deployment)

## 8. Roadmap

- [x] Week 1, Day 1: Problem statement, objectives, stakeholders, scope, constraints, requirements
- [ ] Week 1: Use-case diagram, activity diagram, site map, wireframes
- [ ] Week 2: Build and style the site
- [ ] Week 3: Test, deploy, finalize SAD report

---
## 9. Use-Case Diagram & Descriptions

**Actors:** Visitor/Recruiter (primary)

**Use cases modeled:** View Home Page, View Profile Info (About/Education/Skills), View Projects, View/Download CV, Navigate via Menu, View Contact Links.

![Use-Case Diagram](./Src/drawIOusecase.png)

### Brief Use-Case Descriptions

| Use Case | Description |
|---|---|
| **View Home Page** | The visitor lands on the site and sees the name, title and short introduction. *Precondition:* site is deployed. *Postcondition:* visitor understands who the portfolio belongs to. |
| **View Profile Info** | The visitor browses About, Education and Skills to learn the owner's background. *Precondition:* content is published. *Postcondition:* visitor has a clear picture of qualifications. |
| **View Projects** | The visitor reviews at least three projects with problem, contribution, tools and links. *Precondition:* projects are added with screenshots/links. *Postcondition:* visitor can judge practical ability. |
| **View/Download CV** | The visitor opens the CV section and can view it inline or download the PDF. *Precondition:* CV file is uploaded. *Postcondition:* CV is displayed or downloaded. |
| **Navigate via Menu** | The visitor uses the navigation bar to jump between sections at any time. *Precondition:* nav menu is present on every view. *Postcondition:* visitor reaches the intended section. |
| **View Contact Links** | The visitor finds a professional email and links to LinkedIn/GitHub. *Precondition:* links are valid. *Postcondition:* visitor can reach out or view external profiles. |

## 10. Activity Diagram — "Visitor Finds and Downloads CV"

Models the key flow of a recruiter locating and retrieving the CV:

**Start → Visitor lands on Home → Clicks navigation menu → Selects "CV" section → Page loads CV preview → Decision: "View inline or download?" → (View path: displays CV inline / Download path: downloads PDF file) → End**

This flow was chosen because retrieving the CV is the single most important action a recruiter takes on the site, making it the clearest candidate for activity modeling.

![Activity Diagram](./Src/drawIoactivity_diagram.png)

## 11. Roadmap (updated)

- [x] Week 1, Day 1: Problem statement, objectives, stakeholders, scope, constraints, requirements
- [x] Week 1, Day 4–5: Use-case diagram + descriptions, activity diagram
- [ ] Week 1, Day 6: Site map & wireframes
- [ ] Week 2: Build and style the site
- [ ] Week 3: Test, deploy, finalize SAD report

*This README will be updated as the project progresses through each SAD stage.*