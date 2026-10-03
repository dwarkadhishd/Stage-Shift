# Stage & Shift

A responsive campus portal for event discovery and volunteer coordination. It bridges the gap between event organizers and student volunteers, designed with a modular frontend architecture ready for full-stack backend integration.

## Tech Stack & Rationale
* **HTML5 & CSS3:** Semantic markup with custom styling and visual filters.
* **Bootstrap 5.3:** Selected for rapid, mobile-first prototyping and a standards-compliant grid. The markup is deliberately clean and decoupled, making it easy to migrate to a component-driven framework (like React) in the future.

## Core Features (Frontend v1.0)
* **Dynamic Event Showcase:** Modular UI cards pre-structured for REST API data.
* **Volunteer Value Grid:** Clean layout highlighting real-world student benefits (Leadership, Networking).
* **Responsive UI:** Custom hero section, scalable SVG icons, and a production-ready footer.

## Future Backend Roadmap
* **REST API Integration:** Fetch real-time event data and process volunteer sign-ups.
* **Database & Logic:** Track shift capacities and automatically disable full registration slots.
* **Coordinator Dashboard:** Secure admin panel for placement officers to manage rosters.

## Quick Start
```bash
git clone [https://github.com/your-username/stage-and-shift.git](https://github.com/your-username/stage-and-shift.git)
cd stage-and-shift
# Open index.html in any web browser