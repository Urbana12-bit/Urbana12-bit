# Urbana Starter (Expo + React Native + TypeScript)

This is the Urbana mobile starter project. It includes a first home/explore experience, category shortcuts, bottom navigation, and a Supabase client placeholder.

## Important
- This ZIP contains source code; it is not an installable APK.
- Do not put a Supabase `service_role` key in this app. Mobile apps must use only the anon/publishable key, with Row Level Security policies protecting data.
- The app does not yet query or write Urbana data. We will connect the existing Supabase project after opening the project in a supported development workspace.

## Run on a computer
1. Install Node.js (LTS).
2. Extract this ZIP and open a terminal in the `urbana-starter` folder.
3. Run `npm install`.
4. Run `npx expo start`.
5. Open the QR code with Expo Go.

## Supabase setup
1. Copy `.env.example` to `.env`.
2. Fill in `EXPO_PUBLIC_SUPABASE_URL` and `EXPO_PUBLIC_SUPABASE_ANON_KEY` from the existing Urbana Supabase project's API settings.
3. Never add the `service_role` secret to a mobile app.

## Phone-only note
If you are working only from Android, keep the ZIP saved. We can use a browser-based coding workspace to edit and run the Expo project; the ZIP alone cannot run as an app on the phone.
