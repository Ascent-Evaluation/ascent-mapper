# Ascent Mapper privacy statement

Last updated: November 12, 2026

## In short

Your models stay on your computer. The app goes online only to find studies, which needs you to sign in with your email address and organization. We keep those and a record of your searches, never your models, and we don't sell data, show ads or track you.

## What stays on your computer

Your models, data and files stay on your computer (in the web version, in your browser), and the app works offline. When you sign in, the app also keeps your email address, organization and a sign-in key there, with the key encrypted by your computer's keychain. Signing out removes them.

## What the app sends

- **Finding studies** sends a text description of your model to Ascent's server: the names of the program, pathways, stages, nodes and stakeholders; the assumptions on each link; policy developments; citations already in your library; and your paragraph about the program. It never sends your data series, numbers, scenarios or files.
- **Checking for new studies** (monthly, or when you click Check now) sends the IDs of studies already found and the saved search terms.
- **Signing in** sends your email address, the emailed code and your organization. After that, the app sends a sign-in key with each request.
- **Updates**: on a Mac the app checks GitHub for updates; on Windows the Microsoft Store handles them.

All connections are encrypted, and like any internet request they include your internet address.

## What we keep

We use this only to sign you in and to limit how many searches each person runs.

- **Your account**: email address, organization, when you joined and last signed in, and any search limit we set for you. Kept until you delete your account.
- **Your searches**: when each ran, how it ended, its estimated cost and how many studies it kept. Kept until you delete your account.
- **Short-lived data**: your model's description and results stay in the server's memory while a search runs and for up to 6 hours after. Sign-in codes (10 minutes), daily counts (24 hours) and sign-in keys (until you sign out, or 180 days unused) are stored only as one-way hashes.
- **Search cache and logs**: public study records and their ratings, with no text from your model, kept to speed up later searches; and a log line per search (its ID, duration and cost), kept as long as our host keeps logs.

Deleting your account removes your account, sign-ins and search record. Daily backups of the server can hold deleted data for up to 5 days; we never restore from them.

## Who else handles it

Anthropic (Claude) reads your model's description during a search to plan it and rate studies. OpenAlex and ERIC (U.S. Department of Education) receive search terms built from it, sent from our server, never from your computer. Resend sends sign-in emails. Fly.io hosts our server. GitHub, the Microsoft Store and Netlify (the online demo) deliver the app.

## Your choices

- Use the app without signing in. Everything except finding studies works offline.
- Sign out or delete your account from the circle at the bottom of the left rail.
- Ask us for a copy of your information, or to correct it. We'll answer within 30 days.
- Before you search, remove names or other details about individual people (participants, students, staff) from your model.

## Security, children and changes

Sign-in keys and codes are stored as hashes, the server's disk is encrypted, and all connections use HTTPS. The app is for adults; we don't knowingly create accounts for anyone under 13. If this statement changes, we'll update its date and say so in the release notes.

## Contact

For questions or requests, write to lsmith@ascentevaluation.org.
