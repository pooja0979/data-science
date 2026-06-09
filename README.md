# Science Data Tracker

A collaborative assessment and marks-tracking platform for school science departments. It brings student records, assessments, and grade boundaries together in one place, with analytics across year groups, subjects, and classes — supporting Year 7–13 grading systems (KS3, IGCSE, and IB).

## Features

- **Dashboard** — at-a-glance metrics for student numbers, average performance, and assessment counts, with subject, year-group, and class breakdowns.
- **Performance analytics** — track individual progress, identify top performers and students needing support, and compare trends across subjects and groups.
- **Student records** — organised by year group and class, with individual performance histories and grade summaries.
- **Assessments & marks** — create assessments, record marks in bulk, and grade question-by-question.
- **Configurable grade boundaries** — per year group and per assessment, with KS3, IGCSE, and IB defaults.
- **Bulk import** — upload CSV or Excel files to populate students, classes, and marks in one step.
- **Backup & restore** — export and re-import your data per academic year.

## Tech stack

- React 19 + TypeScript
- Vite
- Tailwind CSS
- Recharts for data visualisation
- Firebase (Firestore) for data persistence

## Getting started

**Prerequisites:** Node.js

1. Install dependencies:
   ```bash
   npm install
   ```
2. Copy `.env.example` to `.env.local` and set the required values (Firebase configuration and `GEMINI_API_KEY`).
3. Start the development server:
   ```bash
   npm run dev
   ```

## Available scripts

- `npm run dev` — start the local development server
- `npm run build` — produce a production build
- `npm run preview` — preview the production build locally
- `npm run lint` — type-check the project with the TypeScript compiler
