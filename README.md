# KhizChat — by Muhammad Khizar

Chat, voice/video calls, status, DP, reactions, reply — installable app (PWA).
Backend: Firebase (Auth + Firestore). Hosting: Vercel (static, no build).

## Files
index.html · manifest.webmanifest · sw.js · icon-192.png · icon-512.png · firestore.rules

## Deploy
1. Saari files GitHub repository ke root mein upload karein (folder nahi, seedhi files).
2. Vercel → Import repository → Deploy (kuch change nahi).
3. Firebase → Authentication → Settings → Authorized domains → apna .vercel.app add karein.
4. Firestore rules: firestore.rules ka text paste karke Publish karein (pehle wali hi chalti hain).
