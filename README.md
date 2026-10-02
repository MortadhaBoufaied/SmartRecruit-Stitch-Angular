# SmartRecruit Stitch Angular Simulation v3

This project converts the supplied Stitch HTML concepts into a structured Angular 18 frontend simulation. It preserves the Stitch visual language: Inter and Plus Jakarta Sans typography, blue enterprise palette, compact information density, role switcher, explainable matching panels, recruiter Kanban, and platform-governance views.

## Run

```bash
npm install
npm start
```

Open `http://localhost:4200`.

## Main routes

- `/` public recruitment portal
- `/login` simulated authentication and role selection
- `/dashboard` candidate dashboard
- `/jobs` job discovery and detailed explainable matching
- `/workspace` recruiter dashboard
- `/pipeline` recruiter Kanban and candidate dossier
- `/admin` platform administrator governance
- `/applications`, `/interviews`, `/profile`, `/notifications`, `/support`, `/settings`

## Simulated services

Authentication, role switching, candidate profile, CV parsing, job search, recommendation and matching, saved jobs, applications, candidate pipeline, interviews, notifications, company verification, moderation, audit activity, support, account preferences, and platform governance.

All displayed records are fictional. Data is stored in the frontend service and can later be replaced with Angular HttpClient calls to Spring Boot APIs.
