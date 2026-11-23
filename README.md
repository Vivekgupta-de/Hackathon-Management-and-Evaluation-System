# Hackathon-Management-and-Evaluation-System
1. Clone the repository
bash
git clone https://github.com/YOUR-USERNAME/hackathon-system.git
cd hackathon-system
2. Install dependencies
bash
npm install
3. Create your .env file

Copy .env.example to .env.

Windows:

bash
copy .env.example .env

Mac / Linux:

bash
cp .env.example .env

Open .env and set at least JWT_SECRET to a long random string, and change ADMIN_PASSWORD.

4. Start the server
bash
npm start

Open http://localhost:3000 in your browser.

For auto-restart while developing:

bash
npm run dev
Default Admin Login

On first run, an admin account is created from your .env values.

Field	Default
Email	admin@hackathon.com
Password	Admin@123
