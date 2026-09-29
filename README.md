# Jarvis AI Employee — Vercel Static App

## Pages
- `/` — Jarvis AI Employee landing page
- `/contact` — simple Jarvis contact form
- `/thank-you` — thank-you page

## Assets
All five landing-page image assets are stored in `/assets/` and the landing page references them with relative paths.

## Current form behavior
The contact form validates required fields in the browser and redirects to `/thank-you`.
No CRM/email/database API is connected yet.

## Deploy
1. Upload this folder to a Git repository.
2. Import the repository into Vercel.
3. Framework preset: Other / static.
4. Build command: leave empty.
5. Output directory: leave empty.
6. Deploy.

No server-side runtime is required for the current version.
