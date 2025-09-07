RonTra - Static demo site (Firebase frontend)
Files:
- index.html (main)
- create/index.html (community listing + create)
- settings/index.html (profile/settings)
- community.html (community detail page, opened after creation)
- assets/css/style.css (styles)
- assets/js/firebase-config.js (your firebaseConfig exported)
- assets/js/firebase-init.js (initializes firebase app and exports auth, db, storage)

How to use:
1. Upload this project to GitHub (root). GitHub Pages will serve index.html at the root.
2. Make sure Firebase project has Firestore, Authentication and Storage enabled.
3. Update firebase-config.js if you want different Firebase keys.
4. Configure Firestore security rules for production (production rules recommended).
5. Open the site and sign in (Google or email/password) to create communities, upload banners, etc.

Note:
- This is a starter/demo. Server-side rules, validations and more advanced membership handling are required for production.
- The code uses Firebase JS SDK v10 modules (CDN).

