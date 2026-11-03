# Pulse privacy policy

Last updated: 3 November 2026

Pulse is a shared home management app for kitchen inventory, grocery lists, household reminders and planned calendar, wardrobe and music features.

## What stays on your device

Inventory, grocery lists, reminders, preferences, cooking history and add-speed metrics are stored locally on your iPhone using Apple SwiftData.

If you join a household or turn on **Live updates**, inventory, grocery lists, reminders and household membership sync with our Supabase project so the people in that home can see them. Changes made offline upload when the connection returns. You can turn Live updates off and use **Sync now** instead.

## Accounts and households

Pulse starts with an anonymous guest account. You can create an email/password account in **Household → Create an account**.

When you have an account or share a household we store your email address and authentication metadata (handled by Supabase Auth), a display name, household membership and role, and the inventory, grocery lists and reminders for that household. People in the same household can see the household name, members' display names and shared content. They cannot see your password.

You can sign out or delete your account in the app. Deleting your account removes it and the cloud household; if the household is shared, ownership transfers to another member. Local data on this phone stays and becomes a new private home.

## Calendar, wardrobe and music

These modules are being introduced gradually. Before any calendar, location, clothing photo or music account data is collected, Pulse will ask for permission and this policy will be updated. Calendar availability is designed to share busy/free blocks only, never event titles. Clothing photos are not stored as photos; future wardrobe recognition will identify products and fetch catalogue images instead. Music account connections will be server-side and opt-in.

## Camera and photos

- Camera access is used only to scan barcodes. A manual barcode fallback works without it.
- Receipt photos are read on-device with Apple Vision. Receipt images are not uploaded.
- A feedback screenshot is uploaded only when you tap **Send feedback**.

## Feedback

If you send feedback, the app sends your summary, details, expected behaviour, attached screenshot, app version/build, device model, iOS version and locale. The report is stored in our Supabase project and a GitHub issue is created for the team. Screenshots use unguessable public-read URLs so GitHub can render them. TestFlight feedback is collected by Apple and shown to us in App Store Connect.

## What we do not do

- No advertising or cross-app tracking.
- No third-party analytics SDK in this build.
- No sale of personal data.
- No access to contacts, location or health data without a feature-specific prompt.

## Retention and deletion

Deleted inventory and grocery rows are soft-deleted so other household devices can remove their copies, then purged after 30 days. Feedback is kept while it is useful for fixing the product. Account and household data are kept until you delete the account or ask us to remove it. Email **webmaster.mrinal@gmail.com** to request deletion of a feedback report or any data you cannot remove in the app.

## Contact

**webmaster.mrinal@gmail.com**
