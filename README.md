# Patient Records Dashboard

A simple React + Vite + TailwindCSS project implementing a Patient Records Dashboard for Jarurat Care.

## Features
- Landing page with header and navigation.
- Patients page: fetches mock data from `public/patients.json`.
- Responsive card/grid layout showing Name, Age, Contact.
- Search bar to filter patients by name.
- View Details modal for each patient.
- Add New Patient form (local state only).
- Loading and error states when fetching API.

## Setup (locally)
1. Install dependencies:
```bash
npm install
```
2. Run the dev server:
```bash
npm run dev
```
3. Open the URL shown by Vite (usually `http://localhost:5173`).

## Notes
- The app fetches `patients.json` from the `public` folder so no backend is required.
- Ready for deployment on Vercel/Netlify.

