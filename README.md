Splitter — Smart Expense Splitting App

Splitter is a full-stack, real-time expense splitting application designed to simplify group and individual expense management. It supports flexible split methods, automatic debt simplification, real-time updates, analytics, and AI-powered insights.


---

🚀 Features

➕ Add & Split Expenses

Add individual and group expenses

Multiple split options:

Equal split

Percentage-based split

Exact custom amounts


Supports multiple participants per expense



---

🔄 Debt Simplification

Automatic debt simplification algorithm

Calculates the most efficient settlement path

Reduces unnecessary transactions between users

Clear “who owes whom” breakdown



---

👥 Groups & Contacts

Browse and manage contacts

Create and manage expense groups

Add/remove members from groups

View group-wise balances and expenses



---

💳 Settlements & Payments

Record payments between users

Settle balances:

Individually

Within groups


Complete settlement history tracking

Multiple settlement options supported



---

⚡ Real-Time Updates

Built on a real-time database

Expense changes sync instantly across users

Live balance and settlement updates



---

📊 Interactive Dashboard

Monthly spending overview

Balance summary (you owe / you’re owed)

Visual charts for:

Spending patterns

Group expenses


Clean, easy-to-understand analytics



---

🤖 AI-Powered Insights

AI analyzes spending patterns

Personalized insights on spending behavior

Smart settlement reminders

Automated email notifications for pending dues



---

🎨 Modern Responsive UI

Built using Next.js

Styled with Chatng UI

Fully responsive (mobile, tablet, desktop)

Clean and intuitive user experience



---

🔐 Secure & Scalable Architecture

Authentication and protected routes

Secure API handling

Scalable backend design

Production-ready structure



---

🛠️ Tech Stack

Frontend

Next.js

React

Tailwind CSS

Chatng UI

Charting library for analytics


Backend

Next.js API routes

Server Actions

Business logic for splitting & settlements


Database

Real-time database (for instant sync)

Structured tables for users, groups, expenses, settlements


AI & Automation

AI for spending analysis

Email notification system

Smart reminders & insights


Tooling

TypeScript

ESLint

Prettier



---

⚙️ Setup & Installation

1️⃣ Clone the Repository

git clone https://github.com/your-username/splitter.git
cd splitter


---

2️⃣ Install Dependencies

npm install


---

3️⃣ Environment Variables

Create .env.local:

DATABASE_URL=your_database_url
NEXT_PUBLIC_APP_URL=http://localhost:3000

AI_API_KEY=your_ai_api_key
EMAIL_SERVICE_API_KEY=your_email_service_key


---

4️⃣ Run the App

npm run dev

App runs at:

http://localhost:3000


---

📈 Why This Project Stands Out

Real-world financial logic

Debt simplification algorithms

Real-time data synchronization

AI-powered insights & reminders

Strong full-stack + system design showcase



---

🔮 Future Enhancements

Multi-currency support

Expense scanning via receipts

Mobile app

Group analytics comparison

Export reports (PDF/CSV)



### Make sure to create a `.env` file with following variables -

```
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

CLERK_JWT_ISSUER_DOMAIN=

RESEND_API_KEY=

GEMINI_API_KEY=
```
