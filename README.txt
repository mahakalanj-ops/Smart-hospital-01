SMART HOSPITAL - PROFESSIONAL THEME
====================================
Files included:
- index.html: public home page
- admin.html: admin dashboard/login
- patients.html: patient portal/register-login page
- appointment.html: patient appointment dashboard
- billing.html: e-billing
- records.html: hospital records
- patient-reports.html: patient reports
- hospital-dashboard.html: older standalone dashboard page

What changed:
- Added a consistent navy/teal visual theme, responsive spacing, cards, tables,
  form controls, and button styling.
- Existing HTML and Firebase JavaScript logic were preserved; this is a visual
  styling pass, not a backend/security rewrite.

How to use:
1. Extract this ZIP.
2. Open the extracted folder in VS Code.
3. Run index.html with Live Server.
4. Keep all HTML files in the same folder so existing relative links continue
   to work.

Important:
- No doctor.html was included in the uploaded files.
- Firebase credentials in client-side HTML are not private security controls.
  Configure Firebase Authentication and Firestore Security Rules carefully.
- Do not use this demo for real patient medical records until access controls,
  validation, backups, privacy, and applicable legal requirements are reviewed.
