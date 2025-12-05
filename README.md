📍 NorthScrape Leads Dashboard

A lightweight, single-file browser application for managing sales leads, planning canvassing routes, and organizing cold calling lists.

Zero Setup. No Server Required. Just open the file in your browser.

🚀 Key Features

Offline Capable: All data is processed locally in your browser. No data is sent to external servers.

Persistent Session: Leads, notes, and statuses are automatically saved to localStorage. You can close the tab and return later without losing work.

Smart Routing: Select multiple leads to generate an optimized multi-stop route via Google Maps.

Lead Management:

📞 One-Click Dialing: Auto-formats numbers; click to dial on mobile.

📝 Notes System: Add persistent notes to any lead.

✅ Status Tracking: Mark leads as "Contacted" to filter them out.

Utilities: PDF Export, Bulk Copy Phone Numbers, Dark Mode.

📦 Quick Start

Download: Save the index.html file to your computer.

Open: Double-click the file to open it in Chrome, Edge, Firefox, or Safari.

Load Data: Drag and drop your CSV file onto the "Load Leads" box, or click "Load Demo Data" to try it out instantly.

📊 CSV Format Guide

To import your own list, your .csv file must have a header row.

Required Columns

Column Header

Description

Name

The business or contact name (Required).

Address

Full address. Critical for the Map and Route features.

Phone

Contact number. The app will auto-format this (e.g., 555-1234 → (555) 555-1234).

Example CSV Data

Copy this into a text file and save as leads.csv to test:

Name,Address,Phone
"Joe's Plumbing","123 Main St, Sudbury, ON","555-0199"
"Sudbury Electric","456 Elm St, Sudbury, ON","555-0123"
"North Hills HVAC","789 Pine Rd, Sudbury, ON","15559876543"


⌨️ Keyboard Shortcuts

Key

Action

/

Focus the Search bar

Esc

Clear Search / Close Modals

🛠️ Tech Stack

Core: HTML5, JavaScript (ES6+)

Styling: Tailwind CSS (CDN)

Icons: Lucide Icons

Libraries: PapaParse (CSV), jsPDF (Export)

🔒 Privacy Notice

This application is Client-Side Only. Your data is parsed in your browser's memory and stored in your browser's local storage. No lead data is transmitted to NorthScrape or any third-party server, ensuring your lists remain private.

Generated for NorthScrape Leads Dashboard
