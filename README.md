# Group Bingo

A party bingo game. Friends write funny predictions about each other. Nobody sees the squares about themselves until the final reveal.

## Turn on shared play (one time)

1. Create a project at https://console.firebase.google.com
2. Build > Authentication > Sign-in method: enable **Email/Password**.
3. Build > Firestore Database: create a database (production mode).
4. Firestore > Rules: paste `firestore.rules`, then Publish.
5. Project settings > Your apps > Web app: copy the config into `firebase-config.js`.
6. Authentication > Settings > Authorized domains: add your `github.io` domain.

Until step 5 is done, the app runs in demo mode on one device.
