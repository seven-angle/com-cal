# Interest Calculator

**[Live Preview / Use the Calculator Here](https://seven-angle.github.io/com-cal/)**

A blazing-fast, strictly client-side daily and flat interest calculator designed for high-precision financial tracking. It allows users to freely record credits and debits throughout a timeline and cleanly export a calculated statement.

## 🚀 Features

- **Daily vs Flat Calculation Modes:** Toggle between monthly calendar block logic (Flat) or strict daily gap mathematical accrual (Daily).
- **Dynamic Ledger Sorting:** Transactions are strictly auto-sorted by chronological date regardless of entry order.
- **Smart Date Assisting:** Setting a Start Date inherently defaults the End Date to the final day of that precise month, reducing calendar clicks.
- **Live Output Validation:** The system instantly recalculates daily permutations and runs balances (`Unit: XX`) directly within the ledger on every keystroke.
- **Print to PDF:** Fully optimized CSS print media queries. Clicking `Save as PDF` natively strips UI buttons and backgrounds to generate a clean, bank-style professional exported document without any bulky external libraries.
- **Leap Year / Localized Formatting:** Accounts for strict Date Object mathematics (28/29/30/31 day months) seamlessly. Displays all numerical values utilizing the Indian metric format (`xx,xx,xxx`).

## 🛠 Tech Stack

This application is built entirely framework-free to guarantee maximum speed, minimal bundle sizes, and the ability to run universally offline.

- **HTML5 & CSS3:** Semantic structure with flexbox/grid responsive layouts.
- **Vanilla JavaScript (ES6+):** Complete manipulation of logic, DOM rendering, and event handling without React or Vue overhead.
- **Flatpickr:** The only external dependency, utilized to ensure robust, cross-browser manual date entry and calendar selection.
- **Vite:** Local development server offering fast Hot Module Replacement (HMR) and optimized, minified production builds.

## 💻 Running the Project Locally

1. Ensure [Node.js](https://nodejs.org/) is installed.
2. Clone this repository.
3. Run `npm install` to download dependencies (Flatpickr, Vite).
4. Run `npm run dev` to start the local development server.
5. Open the provided `localhost` URL in your browser!

### Building for Production / GitHub Pages
To generate a highly minified web version ready for instantaneous hosting on platforms like **GitHub Pages**, Vercel, or Netlify:

1. Run `npm run build`
2. Upload the contents of the generated `/dist` folder to your host of choice.
