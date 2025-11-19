Shiksha Sphere 🎓
"Delulu But Dedicated."

Shiksha Sphere is the digital neural network designed exclusively for RIT Roorkee students. It solves the fragmentation problem of campus life. Instead of checking WhatsApp for notes, a separate timer app for studying, and Excel sheets for attendance, everything is centralized here.

It is built with pure Vanilla JavaScript (ES6 Modules) and Tailwind CSS. No heavy frameworks, no build steps, no npm install hell. It just works.


🚀 Key Features

1. Neural Authentication

Domain Locking: Only users with an @ritroorkee.com email can access the sphere.

Hybrid System: Uses Firebase Authentication. If an account doesn't exist, it auto-registers you to save time during demos.

Session Memory: You stay logged in even if you refresh the page.


2. Shiksha Peer (Study Network)

Real-time Updates: Uses Firestore snapshots to show new study groups instantly without refreshing.

Smart Scheduling: Includes a "G-Cal" button that generates a pre-filled Google Calendar link with the exact date, time, and location of the study session.

Local Tracking: Saves your interested groups to a local sidebar schedule.


3. Shiksha Focus (Gamified Timer)

Growth Logic: A visual tree grows from a seed to a fully bloomed tree as your timer progresses.

Granular Animation: The SVG morphs in real-time based on the percentage of time completed.

Streak System: Tracks consecutive days of deep work.


4. Shiksha AI (Campus Bot)

RIT-Trained: Not just a generic wrapper. It knows specific RIT details like WiFi passwords, library hours, and hostel warden contacts.

Human Touch: Includes typing indicators and randomized responses to feel less robotic.


5. Identity Profile

Dual Identity: Keeps your real name (verified) private while letting you use a public @username.

Edit Mode: Fully functional edit profile system with local persistence.


🛠️ The Stack

We kept it lightweight and fast.

Frontend: HTML5, CSS3 (Tailwind via CDN).

Logic: Vanilla JavaScript (ES6 Modules).

Backend: Firebase (Authentication & Firestore Database).

VFX: Canvas API for the particle background & CSS Keyframes for glassmorphism.

📚 Resources & Documentation

If you want to understand how this was built, here are the exact resources used. These are not AI generators, but the actual docs:

Core Tech

Firebase Web Codelab - The official guide we followed to set up Auth and Database.

Tailwind CSS Cheat Sheet - Essential for finding utility classes quickly without memorizing them.

MDN Web Docs: Modules - Explains why we used <script type="module"> to import Firebase SDKs directly in the browser.

Special Effects
Canvas Confetti - The library used for the victory pop animation when a timer finishes.
CSS Glassmorphism Generator - Helpful for calculating the blur and transparency values for the UI cards.

Utilities
Google Calendar Link Generator - We reverse-engineered this URL structure to create the "Add to G-Cal" feature manually in JavaScript.

⚡ How to Run
Since this project uses CDN links, you don't need Node.js installed.
Clone the repo:

git clone [https://github.com/your-username/shiksha-sphere.git](https://github.com/your-username/shiksha-sphere.git)
