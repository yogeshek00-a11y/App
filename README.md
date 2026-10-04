# Connection — Tinder-style matching app MVP

A complete, runnable, mobile-friendly dating/matching web app. It intentionally uses plain HTML/CSS/JavaScript plus a small Node.js/Express backend, so there is no C++ toolchain or database server to install.

## Requirements
- Node.js 18 or newer
- Any modern browser

## Run
1. Open a terminal in this folder.
2. Run `npm install`.
3. Run `npm start`.
4. Open **http://localhost:3000**.

The app creates `data/db.json` automatically and seeds demo profiles.

### Demo accounts
- `aisha@connection.demo` / `demo123`
- `maya@connection.demo` / `demo123`
- `arjun@connection.demo` / `demo123`
- `riya@connection.demo` / `demo123`
- `kabir@connection.demo` / `demo123`
- `ananya@connection.demo` / `demo123`

Or create a new account from the registration screen.

## Included
- Registration/login with hashed passwords
- Session authentication
- Editable profile
- Age/gender/preference filtering
- Discover feed
- Like, pass and super-like actions
- Mutual-match detection
- Match list
- 1-to-1 messaging
- Persistent JSON storage
- Responsive mobile UI
- Demo data for immediate testing

## Important production note
This is a fully runnable MVP, not a production deployment. Before accepting real users, add HTTPS, secure persistent sessions/JWT, a real database, password hashing such as Argon2/bcrypt, rate limiting, CSRF protection, input validation, image upload/storage, moderation/report/block tools, age verification, privacy/consent flows, push notifications, email/phone verification, backups, logging, and a production deployment configuration.
