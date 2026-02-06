# Portfolio Website - Prompts & Requirements Notes

> **STANDARD REQUIREMENT**: All prompts given by the user must be logged in this file. Any future prompts related to this portfolio website should also be added here for reference.

---

## Session Date: February 7, 2026

### Prompt 1: UI/UX Skill Creation
**User Request:**
> Create a skill only for UI UX design which can use HTML 5 and CSS Framework like Tailwind CSS.

**Action Taken:**
- Created `.claude/skills/ui-ux-design.md` - UI/UX design skill definition
- Created `.claude/settings.json` - Registered skill as `/ui-ux`

**Skill Covers:**
- HTML5 semantic structure
- Tailwind CSS best practices
- Responsive design (mobile-first)
- Accessibility (WCAG 2.1)
- Common UI patterns (navigation, cards, buttons, forms)

---

### Prompt 2: Portfolio Website Creation
**User Request:**
> www.linkedin.com/in/kashish-mehta7 So, this is my LinkedIn profile, you can extract all the information about me from here, so that you can create a portfolio website for me and also, I request you to use multiple pages, not single page website. First do this and letme know and use UI UX skill for this which we have just created it.

**Note:** LinkedIn blocked automated access. User was asked to provide information alternatively.

---

### Prompt 3: Resume Reference
**User Request:**
> Okay Letme share you my resume, so that you can take reference of all the fields and if you can enhance any field then do it by your own. Here is the pdf file in this path: E:\Projects\portfolioWebsite

**Action Taken:**
- Read PDF file: `KashishLinkedInProfile.pdf`
- Extracted all professional information
- Created multi-page portfolio website

**Information Extracted from Resume:**

#### Personal Details:
- **Name:** Kashish Mehta
- **Title:** Software Engineer at NielsenIQ
- **Location:** Pune, Maharashtra, India
- **Phone:** 9773712342
- **Email:** kashmehta007@gmail.com
- **LinkedIn:** www.linkedin.com/in/kashish-mehta7

#### Top Skills:
- Data Structures
- Java
- Spring Boot

#### Summary:
A skilled Software Engineer with more than 3 years of experience, specializing in Java, Spring Boot, and API development. Adept at implementing robust solutions using Data Structures and Algorithms to optimize performance and resolve complex issues. Proven track record of enhancing system integrity and efficiency through meticulous coding practices and Spring Security measures.

**Tech Stack:** DSA | Java | Spring Boot | PostgreSQL | Git | Linux | Machine Learning | MongoDB

#### Work Experience:

1. **NielsenIQ** - Software Engineer (October 2022 - Present, 3 years 5 months)
   - Location: Pune
   - Crafted multiple APIs, streamlining the upload and processing of currency data across various modules
   - Implemented robust Spring Security measures to fortify transactional data integrity
   - Played a key role in identifying and resolving system bugs, ensuring uninterrupted functionality and user satisfaction

2. **ACS Solutions** - Software Engineer (April 2021 - October 2022, 1 year 7 months)
   - Location: Noida, Uttar Pradesh, India
   - Elevated the myStore Mobile App, utilizing Python
   - Led the integration of features for visualizing Barter Application reports and implemented a country-wise rollout
   - Conducted data extraction, cleaning, and processing, followed by in-depth data analysis, presenting actionable insights
   - Developed a machine learning solution to predict post-discharge hospitalization likelihood, aiding therapists in determining appropriate patient care levels

3. **DataTrained** - Data Science Intern (March 2021, 1 month)
   - Location: Noida, Uttar Pradesh, India

#### Education:

1. **Liverpool John Moores University**
   - Degree: Master of Science (MS), Data Science
   - Duration: June 2020 - May 2022

2. **International Institute of Information Technology Bangalore (IIIT-B)**
   - Degree: PGDM, Data Science
   - Duration: 2020 - 2021

3. **Kurukshetra University**
   - Degree: Bachelor of Commerce (B.Com), Business/Commerce, General
   - Duration: 2014 - 2017

---

### Prompt 4: Notes Requirement (STANDARD)
**User Request:**
> As of now profile looks good to me, if any change in future then I will update it, for a reference store all the prompts which I have given to you for creating this portfolio website make a notes for this, so that in near future If I have my updated resume then you can see and update the website accordingly, and make sure all prompts should be there as well as any prompt which I will give you further also you need to add it in notes, make this standard requirement.

**Action Taken:**
- Created this notes file: `.claude/PORTFOLIO_NOTES.md`
- Documented all prompts from the session
- Stored complete extracted information for future reference

**STANDARD REQUIREMENT ESTABLISHED:**
- All future prompts related to this portfolio must be added to this notes file
- When resume is updated, refer to this file for context and update the website accordingly

---

## Files Created

| File | Purpose |
|------|---------|
| `index.html` | Home/Landing page |
| `about.html` | About me page with bio and timeline |
| `experience.html` | Work experience details |
| `education.html` | Education background |
| `skills.html` | Technical skills and proficiency |
| `contact.html` | Contact form and information |
| `.claude/skills/ui-ux-design.md` | UI/UX design skill definition |
| `.claude/settings.json` | Claude Code settings with skill registration |
| `.claude/PORTFOLIO_NOTES.md` | This notes file |

---

## Design Specifications

- **CSS Framework:** Tailwind CSS (via CDN)
- **Font:** Inter (Google Fonts)
- **Primary Color:** #2563EB (Blue)
- **Secondary Color:** #0F172A (Dark)
- **Design Approach:** Mobile-first, responsive
- **Features:** Sticky navigation, mobile hamburger menu, card hover effects, skill progress bars

---

## Future Updates Log

> Add future prompts and changes below this line:

---

### Prompt 5: GitHub Projects Integration (COMPLETED)
**User Request:**
> Okay now I want to add 1 most important feature i.e. I will share you my GitHub link where all repositeries are there, so add it that and also if in near future if I add any new project to GitHub then it should automatically synchronize and for each project try to understand and add a details of it as well like what project does and what tech skills it is using.

**GitHub Profile:** https://github.com/dskashishmehta

**Requirements:**
- Create a Projects page that fetches repositories from GitHub
- Auto-synchronize when new projects are added to GitHub
- For each project, display:
  - Project name
  - Description of what the project does
  - Technologies/languages used
  - Link to GitHub repository

**Status:** COMPLETED

**Action Taken:**
- Created `projects.html` - Dynamic projects page with GitHub API integration
- Updated navigation across all pages to include Projects link
- Features implemented:
  - **Auto-sync**: Fetches repositories from GitHub API on page load
  - **Project Details**: Shows name, description, language, stars, forks, last updated
  - **Custom Descriptions**: Enhanced descriptions for known repositories
  - **Tech Stack Tags**: Technology tags for each project
  - **Filter System**: Filter by All / Original / Forked projects
  - **Statistics**: Shows total repos, original count, fork count, languages used
  - **Loading Skeleton**: Smooth loading animation while fetching data
  - **Error Handling**: Graceful error handling with retry option
  - **Language Colors**: Visual language indicators matching GitHub's colors

**Repositories Found:**
1. portfolioWebsite - Portfolio dynamic website (HTML5, Tailwind CSS, JavaScript)
2. GFG-DEVOPS-COURSE - DevOps course materials (DevOps, Docker, CI/CD)
3. ProductService - Java microservice for product management (Java, Spring Boot)
4. EmailService - Email notification service (Java, Spring Boot) [Forked]
5. Project-Module-Apr-2023 - Project module (Java, Spring) [Forked]
6. GitLearnMar24 - Git learning repository (Git, Version Control)
7. java-tutorial-for-beginners - Java tutorial with 500+ examples [Forked]

---

### Prompt 6: JavaScript Skill Creation
**User Request:**
> Add a new claude skill for JavaScript.

**Action Taken:**
- Created `.claude/skills/javascript.md` - JavaScript skill definition
- Updated `.claude/settings.json` - Registered skill as `/javascript`

**Skill Covers:**
- Modern JavaScript (ES6+)
- DOM manipulation
- Asynchronous programming (Promises, async/await)
- Array & Object methods
- Fetch API patterns
- Event handling
- Modules (import/export)
- Error handling
- Performance tips (debounce, throttle)

---

### Prompt 7: Clickable Project Titles
**User Request:**
> I have seen projects page, there if I click on card project titles then it should open that project.

**Action Taken:**
- Updated `projects.html` - Made project titles clickable
- Wrapped project title and icon in an anchor tag linking to GitHub repository
- Added hover effects (color change to primary blue) for better UX
- Title, icon, and folder all highlight on hover

---

## Files Created

| File | Purpose |
|------|---------|
| `index.html` | Home/Landing page |
| `about.html` | About me page with bio and timeline |
| `experience.html` | Work experience details |
| `education.html` | Education background |
| `skills.html` | Technical skills and proficiency |
| `contact.html` | Contact form and information |
| `projects.html` | Dynamic GitHub projects page with auto-sync |
| `.claude/skills/ui-ux-design.md` | UI/UX design skill definition |
| `.claude/skills/javascript.md` | JavaScript skill definition |
| `.claude/settings.json` | Claude Code settings with skill registration |
| `.claude/PORTFOLIO_NOTES.md` | This notes file |

---

## GitHub Integration Details

- **GitHub Username:** dskashishmehta
- **API Endpoint:** `https://api.github.com/users/dskashishmehta/repos`
- **Auto-Sync:** Projects page fetches latest data on every page load
- **No Backend Required:** Pure client-side implementation using Fetch API

---

*Last Updated: February 7, 2026*
