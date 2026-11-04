INWARD — Website Prototype (Turkish)
====================================

This is a responsive, multi-page, client-side website prototype.

HOW TO OPEN
1. Extract the ZIP file.
2. Open index.html in a modern browser (Safari, Chrome, Firefox, Edge).
   If browser restrictions cause issues, run a local server from this folder:
       python3 -m http.server 8000
   Then open:
       http://localhost:8000

WHAT IS INCLUDED
- Separate routes/pages: home, test library, categories, category pages,
  test introduction, step-by-step quiz flow, individual results, session results,
  about, and privacy.
- WHO-5 using the official WHO Turkish form and scoring (18+ gate).
- A custom daily-life reflection based on five research domains. It is clearly
  identified as NOT the validated Turkish TYDQ-15 form.
- Four original entertainment/reflection quizzes with answer-based result profiles.
- Search and category filters, progress indicators, responsive layout, print results.
- No account system, backend, analytics, or remote storage. Answers remain in
  browser memory for the current open tab and disappear on refresh/close.

IMPORTANT RESEARCH / LICENSING NOTES
- WHO-5 Turkish form is attributed to WHO's published Turkish document. The WHO
  page lists CC BY-NC-SA 3.0. This build is therefore marked non-commercial.
  Review the license carefully before using it commercially or changing the form.
- Turkish WHO-5 validation evidence cited in the site is based on adults and older
  adults, so the test is gated to users aged 18+ in this prototype.
- The 2026 Turkish TYDQ-15 validation article included participants aged 14–47,
  but this site does not reproduce the validated Turkish item wording. The daily
  reflection test uses original simplified prompts inspired by the five domains
  and is explicitly NOT presented as a validated scale or clinical score.
- Entertainment quizzes are original preference summaries, not scientific tests.

BEFORE PUBLIC LAUNCH
A production release should be reviewed by a psychologist / psychometrician,
reviewed for accessibility and legal compliance, and tested on phones and desktop.
Any future account, server, analytics, or database feature would require a new
privacy and security design, especially because psychological responses can be
sensitive personal data.
