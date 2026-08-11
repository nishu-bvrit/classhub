# ClassHub

ClassHub is a private online community for one college class. Students can discuss projects and hackathons, vote in polls, get birthday reminders, and join invite-only activity groups.

## Current prototype

The first front-end prototype includes:

- Sign-in screen
- Class directory with student profiles
- Public and private channels
- Poll interaction
- Birthday reminder
- Responsive layout for mobile and desktop

## Run it

Open `index.html` in a browser. No installation is needed for this first prototype.

## Team workflow

1. Create a branch for each feature, e.g. `feature/polls`.
2. Make focused commits with clear messages.
3. Push the branch and open a pull request on GitHub.
4. Have at least one teammate review before merging to `main`.

See [PROJECT_PLAN.md](PROJECT_PLAN.md) for suggested first tasks.

## Proposed stack

- Front end: React + Vite (next phase)
- Backend: Supabase (authentication, database, real-time messages, file storage)
- Deployment: Vercel or Netlify

> The current sign-in is demonstration-only. Do not use it for real accounts until Supabase authentication and security rules are configured.
