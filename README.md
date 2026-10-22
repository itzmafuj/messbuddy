🍛 Mess Buddy - Meal & Expense Manager
Mess Buddy is a real-time, responsive web application designed to simplify the daily management of shared living spaces like Messes and Paying Guests (PGs). It tracks daily meals, bazar (market) expenses, deposits, and individual member dues, ensuring zero confusion and complete financial transparency.

✨ Key Features
📊 Smart Dashboard: Instantly view total costs, available balance, dynamically calculated rate-per-meal, and individual member dues or extra balances.

🍽️ Meal Tracking: Log daily meals for each member. Supports "minimum billable meals" logic for fair cost distribution.

🛒 Expense (Bazar) Logging: Record daily market expenses with dates and notes.

💳 Deposit & Payment System: Track member deposits. Includes integrated UPI QR code generation for quick due settlements directly to the Mess Admin's bank account.

📄 One-Click PDF Reports: Generate detailed monthly reports (Bill Summary, Daily Meals, Expenses, and Deposits) using jsPDF.

🔐 Secure & Role-Based Access:

Master Admin: Can manage all messes, push OTA updates, manage global announcements, and view activity logs.

Mess Admin: Can add/remove members, log meals/expenses, and generate join codes.

Viewer (User): Can view their own stats, submit payment requests, and raise support tickets.

🌍 Multilingual Support: Seamlessly switch between English, Bengali (বাংলা), and Hindi (हिन्दी).

🎫 Ticketing & Support: Built-in support ticket system for members to report issues directly to the admins.

🔔 Push Notifications: Firebase Cloud Messaging (FCM) integration for real-time alerts.

📱 PWA / Mobile-First UI: Beautiful, app-like interface featuring glassmorphism, smooth animations, and dynamic themes (Khata/Ledger and Fintech styles).

🛠️ Tech Stack
Frontend: HTML5, CSS3, Vanilla JavaScript (ES6+)

Backend / Database: Firebase Realtime Database

Authentication: Firebase Auth (Google Sign-In, Email/Password)

Hosting / Notifications: Firebase Cloud Messaging (FCM)

Libraries: jsPDF & jsPDF-AutoTable (for report generation), QRServer API (for UPI QR codes).

🚀 How It Works
Create a Mess: The Master Admin approves new mess registrations.

Invite Members: Mess Admins generate a secure, 5-minute temporary "Join Code" or invite members via Gmail.

Log Daily Data: The Admin inputs the daily meal counts and bazar costs.

Auto-Calculation: Mess Buddy automatically calculates the Rate Per Meal based on total expenses and billable meals, instantly updating everyone's dues/balances.

Settle Up: Members scan the UPI QR code to pay their dues, which the Admin then approves to update the ledger.

⚙️ Local Setup & Deployment
Clone the repository:

Bash
git clone [ttps://github.com/yourusername/mess-buddy.git](https://github.com/itzmafuj/messbuddy)
Open index.html in your code editor.

Replace the firebaseConfig object inside the <script type="module"> tag with your own Firebase project credentials. Ensure you have enabled:

Firebase Realtime Database

Firebase Authentication (Email/Password & Google)

Firebase Cloud Messaging (if using push notifications)

Serve the file locally using a live server (e.g., VS Code Live Server extension) or deploy it to Firebase Hosting / Vercel / Netlify.

👨‍💻 Developer & Credits
Developed and maintained by Mfzx.Build (Mafuj Hossain).

Contact: WhatsApp Support

Social: Instagram @mfzx.build

