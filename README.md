# CarePoint Hospital Management UI

A responsive React single-page application built for the Hospital Management UI assignment.

## Run locally

```bash
npm install
npm run dev
```

Then open the local URL shown by Vite.

## Included routes

- `/` — dashboard
- `/patients` and `/patients/:patientId`
- `/doctors` and `/doctors/:doctorId`
- `/appointments`
- `/departments`
- `/settings`
- any unknown path redirects to a 404 page

The app uses `BrowserRouter`, `NavLink` for active navigation, parameterized patient/doctor records, and a shared header/sidebar layout.
