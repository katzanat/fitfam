# FitFam

A 10-week family workout app for Shira and Yonatan: daily workouts with animated figures, check-offs, points, levels and a family view.

- Live: https://fitfam-six.vercel.app (Hebrew at `/he/`)
- `index.html` is English and `he/index.html` is Hebrew. Both carry the same JavaScript, so a change to the logic goes into both files.
- Progress is saved on the device and synced through Supabase (project `fitfam`) by the `fitfam_get` / `fitfam_put` functions. No logins.
- Every push to `main` deploys to production on Vercel.
