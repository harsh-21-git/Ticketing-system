
# 🛠️ Service Desk Ticketing System (React App)

A complete front-end simulation of a service desk ticketing system built using React.js. This project demonstrates ITSM workflows like ticket submission, issue triage, technician assignment, and resolution tracking. Ideal for IT Support Intern and Service Desk portfolios.

## 🔧 Features

- 🎫 Submit and log support tickets
- 📊 Track ticket status (New, In Progress, Escalated, Resolved, Closed)
- 👤 Assign technicians and add resolution notes
- 📤 Export submitted tickets to CSV
- ⚡ Instant feedback and form validation
- 🌐 Responsive UI with TailwindCSS

## 🧰 Tech Stack

- React.js (Create React App)
- TailwindCSS (custom styling)
- UUID (unique ticket IDs)
- Lucide-react (icons)
- JavaScript Blob API (CSV export)

## 🚀 How to Run

1. Clone or unzip the project folder:
   ```bash
   git clone https://github.com/yourusername/ticketing-system.git
   cd ticketing-system
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the app:
   ```bash
   npm start
   ```

4. Visit: `http://localhost:3000`

## 📁 Project Structure

```
ticketing-system/
├── public/
├── src/
│   ├── App.js
│   ├── index.js
│   ├── index.css
├── tailwind.config.js
├── postcss.config.js
├── package.json
└── README.md
```

## 📦 Exported CSV Example

Each ticket includes:
- Ticket ID
- Requestor
- Date
- Category
- Description
- Priority
- Status
- Technician
- Resolution

## 📜 License

Free for educational and portfolio use.
