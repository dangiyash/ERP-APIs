While going through the buzz I discovered that the ERP makers left the APIs to be accesible by anyone, so I used them. and detailed them for you so you can also use them directly and easily.
Anything ahead is AI written:

## 🤡 Why Does This Even Work?

Because the legendary MANIT devs left their APIs wide open to the world with CORS: `*`.Privacy? Security? Never heard of her.

Welcome to the **No-Frame Student Info Portal**! This is a dashboard for students who like their web apps like their chai: strong, simple, and with zero frameworks.

## 🔥 API Endpoints (a.k.a. The Open Buffet)

All requests go to: `https://erpapi.manit.ac.in/api/`

- **POST `/login`** — Authenticate with `{ username, password }` and get a JWT token. No secret sauce required.
- **POST `/student_profile_check`** — Fetch your profile with `{ studentuid }`. Because why not?
- **POST `/fetch_semester`** — Get semester info with `{ studentuid, program }`. Open to all, no RSVP needed.
- **POST `/student_result`** — Your results, grades, and CGPA, all for the taking.
- **POST `/check-fees-status`** — Want to know if you paid your fees? So does everyone else!

## 🏗️ Project Structure

- `index.html` — The whole app. No React, no Vue, just vibes.
- `style.css` — So pretty, your eyes will thank you.
- `config.js` — It's there. Does nothing. Like a government office on Sunday.
- `vercel.json` — For those who like to deploy and chill.

## 🦾 How To Use

1. Open `index.html` in your browser (or deploy it, if you're fancy).
2. Enter your roll number and password. (Don't worry, we don't save anything. We're not that evil.)
3. Enjoy your data, courtesy of the most generous CORS policy in academia.

## ⚠️ Notes

- No frameworks were harmed (or used) in the making of this project.
- All your API are belong to us. Thanks, MANIT devs!
- If you're a MANIT dev reading this: maybe lock it down? Or don't. We're having fun.

---


