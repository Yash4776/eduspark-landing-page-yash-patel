# StudyNest: Responsive Landing Page (Figma UI/UX)

**Student name:** _[Your name]_
**Course:** UI/UX using Figma, IPS
**Figma file link:** _[Paste your Figma link here, set to "Anyone with the link can view"]_

---

## 1. Product Idea

**StudyNest** is a fictional study-planning and focus app for college students. It helps them organize assignments, build weekly study schedules, track exam deadlines, and stay focused with built-in study timers.

## 2. Target Audience

- College and university students (ages 17-24)
- Students who struggle to balance classes, assignments, and exams
- Mobile-first users who want a clean, distraction-free tool

## 3. Design System

### Color Styles

| Style Name | Hex | Usage |
|---|---|---|
| Primary | `#4F46E5` | Buttons, links, logo |
| Primary Dark | `#3730A3` | Button hover, footer |
| Secondary | `#F59E0B` | Accents, icons, highlights |
| Background | `#F8FAFC` | Page background |
| Surface | `#FFFFFF` | Cards, header |
| Text Dark | `#0F172A` | Headings |
| Text Muted | `#64748B` | Body text, descriptions |

### Typography Styles (Font: Poppins for headings, Inter for body)

| Style Name | Font | Size / Weight |
|---|---|---|
| H1 | Poppins | 56 px / Bold |
| H2 | Poppins | 36 px / SemiBold |
| H3 | Poppins | 22 px / SemiBold |
| Body | Inter | 18 px / Regular |
| Button | Inter | 16 px / SemiBold |
| Caption | Inter | 14 px / Regular |

### Spacing

Spacing follows an 8 px grid: 8, 16, 24, 32, 64, 96. Page sections have 96 px vertical padding and 120 px side padding on desktop.

## 4. Page Structure (Desktop frame: 1440 x 1024)

1. **Header** (Auto Layout, horizontal): logo (left), links Home / Features / Pricing / Contact (center), "Get Started" button (right).
2. **Hero** (Auto Layout, horizontal): left side has the H1 "Plan smarter. Study calmer.", a short description, and the "Start Free" primary button. The right side has an app illustration.
3. **Features** (Auto Layout, horizontal, 3 cards): Smart Planner, Deadline Reminders, Focus Timer. Each has an icon, title, and short text.
4. **Footer** (Auto Layout): logo, links (About, Privacy, Terms, Contact), and the copyright line.

## 5. Reusable Components

1. **Button / Primary**: with variants for Default and Hover.
2. **Feature Card**: icon, title, description. Used 3 times as instances.
3. **Nav Bar (Header)**: logo, links, and CTA button.
4. **Footer**: reused as a single instance.

## 6. Design Explanation

StudyNest is designed for busy college students who need a quick, stress-free way to plan their studies. The indigo primary color suggests focus and trust, while the amber accent adds energy to icons and highlights without overwhelming the page. Poppins gives headings a friendly, modern look, and Inter keeps body text readable at small sizes.

The layout follows a simple top-to-bottom flow: the header offers an immediate call-to-action, the hero explains the value in one headline and one button, and the three feature cards give quick proof of usefulness. Generous white space and a consistent 8 px spacing system keep the page clean and easy to scan. Auto Layout is used throughout, so spacing and alignment stay consistent and the layout adapts easily when content changes or the frame is resized for tablet and mobile screens.

## 7. Files in this Repository

- `README.md`: project description and design explanation
- `landing-page.png`: exported desktop design
- `components.png`: screenshot of the reusable components
- `styles.png`: screenshot of color and text styles
