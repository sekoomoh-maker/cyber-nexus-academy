# CYBER NEXUS Academy — Frontend v1

## What's included
- Responsive cyberpunk-style landing page
- Five learning paths with curriculum outlines
- Arabic / English language toggle and RTL/LTR layout
- Course detail view
- Sign-up / login UI preview
- Basic accessibility labels and responsive mobile layout

## Important
This is the first frontend version. Authentication is intentionally not active yet.
Do not put Supabase service-role keys or other secret keys in browser code.

## Next integration steps
1. Create/confirm Supabase project.
2. Configure `site_url` and redirect URLs after deployment.
3. Use Supabase anon/publishable key only in the browser.
4. Create database tables and Row Level Security policies for profiles, courses, modules, lessons, quizzes, progress, and certificates.
5. Set the academy owner role securely through trusted admin/backend tooling; never allow a public signup to set `admin` or `owner`.
6. Implement real email confirmation, password reset, Google OAuth, protected admin dashboard, and server-validated quiz results.
7. Replace "Coming soon" status only after lesson content is actually ready and reviewed.

## Deploy to GitHub Pages
- Upload `index.html` to the root of the repository.
- In GitHub repository Settings > Pages, choose deploy from branch and select the default branch / root.
- After the URL is live, update Supabase Site URL and redirect URLs to that exact HTTPS origin.

The Google Fonts import is optional; the site uses fallbacks if it cannot load.
