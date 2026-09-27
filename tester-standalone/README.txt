CEO — how to put this online
=============================

WHY: right now the app runs inside a frame on claude.ai. Safari throws away
framed storage when the tab closes, which is why testers lose their log.
On its own web address the same code saves permanently. Nothing in the app
needs changing — only where it is served from.

FASTEST — Netlify Drop, about two minutes
-----------------------------------------
1. Unzip this folder.
2. Go to  app.netlify.com/drop
3. Drag the WHOLE unzipped folder onto that page (the folder, not the files).
4. You get a live address straight away, e.g. sunny-cat-1234.netlify.app
5. Make a free account to keep it and rename it to something you like.

BEST LONG TERM — GitHub Pages, about ten minutes
------------------------------------------------
1. Make a free GitHub account.
2. New repository -> Public -> name it e.g. "ceo" -> Create.
3. "Add file" -> "Upload files" -> drag in everything from this folder
   (index.html, the icons, manifest.webmanifest) -> Commit.
4. Settings -> Pages -> Source: "Deploy from a branch",
   Branch: main, folder: / (root) -> Save.
5. A minute later it is live at  <your-username>.github.io/ceo
6. To update later, upload a new index.html over the old one.

Both are free and neither needs a credit card.

AFTER IT IS LIVE
----------------
- Send testers the new address, not the claude.ai link.
- On iPhone: open in Safari -> Share -> Add to Home Screen.
  It gets your icon and opens without browser chrome.
- The storage warning in Setup disappears, because it no longer applies.
- Data now survives closing the app, restarting the phone, everything
  short of clearing site data.

WORTH KNOWING
-------------
- Storage is per device. One tester on two phones gets two separate logs.
  Real cross-device sync needs a backend; Export/Import covers it for now.
- Testers' existing data is already gone. It was never actually saved.
  They start fresh on the new address, and it sticks from then on.
- A custom domain is optional, roughly 40-60 SAR a year for a .com.
  The free subdomain works exactly as well.
