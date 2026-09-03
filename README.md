# TripSplit

TripSplit is an Expo/React Native app for tracking shared trip expenses and calculating simple settlements.

## Included

- Trip creation
- Multiple trip participants
- Expense entry
- Select who paid
- Select who shares an expense
- Automatic equal splitting
- Balance calculation
- Simplified settlement suggestions
- Optional Supabase client
- Supabase database schema

## Run locally

Install Node.js, then:

```bash
npm install
npx expo start
```

Use Expo Go or an Android/iOS emulator.

## GitHub

Create a GitHub repository, then upload the contents of this folder.

If using Git:

```bash
git init
git add .
git commit -m "Initial TripSplit app"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

## Supabase

Copy `.env.example` to `.env` and add your Supabase URL and anonymous key.

The current UI uses local in-memory state so the app can run without a configured backend. The Supabase schema and client are included as the starting point for persistent cloud storage and authentication.

## App flow

Home -> Create Trip -> Trip Details -> Add Expense -> Balances / Settle Up.
