# TripSplit

A mobile-first shared trip expense app built with Expo Router + React Native + TypeScript.

## Run

```bash
npm install
npx expo start
```

Then press `a` for Android, `i` for iOS, or scan the QR code with Expo Go.

## Included

- Trip list
- Create trip
- Trip dashboard
- Add expenses
- Equal splitting
- Net balance calculation
- Simplified settlement calculation
- Supabase/PostgreSQL schema in `supabase/schema.sql`

## Data

The included UI uses an in-memory React context so the app works immediately without credentials. Replace `lib/store.tsx` with Supabase persistence when authentication/database credentials are available.

## Supabase next step

1. Create a Supabase project.
2. Run `supabase/schema.sql` in SQL Editor.
3. Add Supabase JS client and environment variables.
4. Replace the local store with database queries and authenticated trip membership policies.
