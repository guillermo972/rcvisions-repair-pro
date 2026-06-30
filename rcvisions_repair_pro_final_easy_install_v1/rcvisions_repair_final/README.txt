RCvisions Repair Pro Final v1.0

EASY INSTALL
1. Make sure Node.js LTS is installed from nodejs.org.
2. Unzip this folder.
3. Double-click install.bat one time.
4. Double-click start.bat whenever you want to use the app.
5. Staff page opens at http://localhost:3000/staff.html
6. Customer page is http://localhost:3000

Default Staff PIN: 1234

EMAIL SETUP
1. Open Staff Dashboard > Settings.
2. Keep Email Mode on Test Mode first.
3. Create a repair ticket using your own email.
4. Click Send Email Update. In Test Mode, it saves the email preview to data/email-test-log.html.
5. For real Gmail sending:
   - Enable 2-Step Verification on the Gmail account.
   - Create a Google App Password for Mail.
   - In Settings, choose Live Gmail.
   - Email User: your Gmail address or Google Workspace email.
   - Email Pass: your 16-character Google App Password.
   - Email From: RCvisions Repairs <admin@rcvisions.com>
   - Public URL: use http://localhost:3000 for shop testing. Later use https://repair.rcvisions.com.
   - Save Settings.
6. Send a test update to yourself.

CUSTOMER STATUS
Customers visit the customer page and enter Ticket # plus phone number or last 4 digits.
For testing on the shop computer: http://localhost:3000
For real customer access from home, this app must be hosted online later.

NOTES
- Data is stored in the data folder as JSON files.
- Back up the data folder regularly.
- This version is made to be easy to run and test in the shop.
