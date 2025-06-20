🍔 Food Panda (Mockup)

This is a mockup React single-page application (SPA) designed for food ordering, developed under the folder `food panda(Moke up)`.

---

## 🚀 Getting Started

### 📦 Install Dependencies

Make sure you have Node.js installed. Then run:

```bash
npm install
🧪 Run Locally
Start the development server:

bash
Copy
Edit
npm start
The app will run at: http://localhost:3000/

🛠 Build for Production
Build the app for deployment:

bash
Copy
Edit
npm run build
This creates a build/ folder with an optimized production build.

🌐 Deploy on Netlify
⚠️ Prevent "Page not found" Errors (SPA Routing Fix)
To avoid 404 errors on routes like /login or /dashboard, add a _redirects file for Netlify to handle routing properly.

✅ Steps:
Inside the public/ folder, create a file named:

nginx
Copy
Edit
_redirects
Add this line inside _redirects:

bash
Copy
Edit
/*    /index.html   200
Save and commit:

bash
Copy
Edit
git add public/_redirects
git commit -m "Add Netlify SPA redirect fix"
git push
Deploy the project to Netlify using either Git or drag-and-drop of the build/ folder to Netlify Drop.

📁 Folder Structure
pgsql
Copy
Edit
food panda(Moke up)/
├── public/
│   └── _redirects          <-- Required for Netlify SPA support
├── src/
├── package.json
├── README.md               <-- This file
