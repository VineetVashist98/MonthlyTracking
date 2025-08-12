# 📅 Ticket Log Tracker

A simple **browser-based ticket logging tool** with a monthly calendar view, color-coded ticket entries, Excel summary import/export, and local data persistence.  
Perfect for quickly tracking work done on different tickets across days in a month.

---

## ✨ Features

- **Interactive Calendar**  
  View ticket logs for the current month and navigate between months.

- **Click-to-Log**  
  Click a date in the calendar to auto-fill it in the log form.

- **Color-Coded Tickets**  
  Each ticket ID is assigned one of 20 distinct colors for easy visual grouping.

- **Excel Summary Export**  
  Download a `.xlsx` file containing all ticket summaries with:
  - Ticket ID
  - Total Hours
  - Dates Worked  
  File name format: `DD_MON_YYYY.xlsx`

- **Excel Summary Import**  
  Upload a summary file and instantly render its data in the calendar and summary table.

- **LocalStorage Persistence**  
  Your ticket logs stay saved even after refreshing the browser.

- **Clear & Refresh Button**  
  Wipe all saved logs and reload the app.

---

## 📂 File Structure
ticket-log-tracker/
│
├── index.html # Main application HTML, CSS, and JavaScript
├── README.md # Project documentation

## Excel Summary Format
**Exported file structure**

| TicketID | TotalHours | DatesWorked            |
| -------- | ---------- | ---------------------- |
| ABC-123  | 5          | 2025-08-10, 2025-08-11 |
| XYZ-456  | 3          | 2025-08-12             |


## Built With
HTML5, CSS3, Vanilla JavaScript
SheetJS/xlsx – For Excel file handling
LocalStorage – For persistent ticket logs

