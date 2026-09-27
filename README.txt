SKY BLUE LOGISTIC — COMPLETE WEBSITE

Includes:
- Public shipment tracking page
- Private admin login
- Admin shipment creation, editing and deletion
- Tracking event history
- JSON file database (data.json is created automatically)
- Responsive design

RUN LOCALLY:
1. Install Node.js 18+.
2. Open this folder in a terminal.
3. Run: npm start
4. Open: http://localhost:3000
5. Admin: http://localhost:3000/admin

DEMO ADMIN:
Username: admin
Password: ChangeMe123!

IMPORTANT FOR PRODUCTION:
Change ADMIN_USER and ADMIN_PASS environment variables. For a real public deployment, use HTTPS, a proper database, hashed passwords, backups, rate limiting and secure session storage. The included JSON database is suitable for a small demo/development deployment, not high-volume production.

Example production start:
ADMIN_USER=youradmin ADMIN_PASS='yourstrongpassword' npm start
