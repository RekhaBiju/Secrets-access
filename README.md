
A simple Node.js + Express.js web app that grants access to a **secret page** only when the correct password is entered!  
This project demonstrates how **middleware** and **authorization logic** work in Express.  

Features
- Password-protected page using Express middleware  
- Checks user input through POST request  
- Redirects users based on password correctness  
- Clean and beginner-friendly structure  

Tech Stack
- **Backend:** Node.js, Express.js  
- **Middleware:** body-parser  
- **Frontend:** HTML  

How It Works
1. User visits the homepage (`index.html`) and enters a password.  
2. Middleware (`passwordCheck`) checks whether the password matches the correct one.  
3. If the password is correct (`ILoveProgramming`), the user is granted access to `secret.html`.  
4. If not, they are redirected back to the homepage.  

Run Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/RekhaBiju/secret-access-project.git
2. Install dependencies: npm install express body-parser

3. Run the app: node index.js

4. Open your browser and visit: http://localhost:3000


