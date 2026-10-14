Combined Login + Home Page

This project uses ONE HTML file. After successful sign-in, the login view is replaced by the home page without navigating to another file. This avoids local HTML navigation problems.

How to test:
1. Open combined-login.html in a browser.
2. Choose Create Account and register with a name, email, password of at least 8 characters, and matching confirmation.
3. Sign in using the same email and password.
4. The home page should appear within the same tab.
5. Click Sign Out to return to the login form.

Demo-only security warning:
Account details and passwords are stored in browser localStorage for practice only. Do not use a real password. Production authentication requires a secure backend and proper password hashing.
