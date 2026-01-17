DIGITAL BUSINESS CARD PRO
========================

What this is
------------
A clean, mobile-first digital business card you can host as a single webpage.
It includes:
- Light/Dark theme toggle
- Tap-to-call, email, website, WhatsApp, and social buttons
- Share button (Web Share API + clipboard fallback)
- QR code that automatically points to the card's live URL
- "Save Contact" button that downloads a vCard (.vcf) instantly
- Optional "Edit Mode" to customize details in the browser (no coding)
- Optional "Lock" so clients can't enter edit mode after you deliver

Files
-----
- index.html              (the card)
- assets/avatar.svg       (placeholder profile image)
- LICENSE.txt

Quick setup (no coding)
----------------------
1) Open index.html in a browser.
2) Click "Edit".
3) Fill your details.
4) Click "Save".
5) (Optional) Click "Lock" to disable Edit Mode.

Deploy (make it live)
---------------------
You need a public URL so the QR code works.
Choose any of these:

A) GitHub Pages (free)
  - Create a GitHub repo
  - Upload index.html + assets/
  - Settings -> Pages -> Deploy from main branch

B) Netlify (free)
  - Drag-and-drop the folder into Netlify

C) Vercel (free)
  - Create a new project and upload the folder

After deployment, open your card URL once on your phone and test:
- Share button
- Save Contact (.vcf)
- QR scan

Tip: Use your own photo
-----------------------
Replace assets/avatar.svg with your picture.
If you use a photo, name it avatar.jpg or avatar.png and update the image path in index.html.

Client delivery checklist
-------------------------
- Confirm name + title + phone + email
- Confirm links open correctly
- Confirm vCard downloads and saves properly
- Confirm QR code opens the live URL
- Lock edit mode if the client wants it

Support
-------
If you need multiple styles (hairdresser, realtor, developer, etc.) you can clone index.html
and change the theme colors + button set.
