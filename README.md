# **Invigilator Duty Management System (Google Apps Script)**  

## **Overview**  
This is a **Google Apps Script-based web app** that helps manage invigilator duties during exams. It allows:  
✔️ **Invigilators** to check their assigned duties.  
✔️ **Admins** to handle duty swaps & approvals.  
✔️ **Automated emails & notifications** for better coordination.  

It uses **Google Sheets as a database** and has a **user-friendly web interface** with search, duty swap requests, and admin controls.  
**Live Google Sheet:** [Click Here](https://docs.google.com/spreadsheets/d/17AMgBBXAvW1QgupUGgG5kFMY2lrJRA6kcOM4dwlNnyQ/edit?usp=sharing)  

---

## **Features**  

### **Duty Search**  
🔹 Search duties using **Employee ID, Name, or Email.**  
🔹 View **duty details** with date, location, slots, and counts.  
🔹 **Mobile-friendly UI** for easy access.  

### **Duty Swap System**  
🔹 Invigilators can **request duty swaps** with reasons.  
🔹 **Admin panel** to approve/reject swaps.  
🔹 **Email alerts** for all updates.  

### **Notifications**  
🔹 **Email notifications** for swap requests, approvals & duty reminders.  
🔹 **Browser alerts** for upcoming duties (Today/Tomorrow).  

### **Admin Controls**  
🔹 View & manage all swap requests.  
🔹 Add new duties directly from the interface.  
🔹 Approve, reject, or delete swap requests.  

### **Data Handling**  
🔹 Uses **Google Sheets** as a database.  
🔹 **Caching & local storage** for better speed.  
🔹 **Error handling** for smooth performance.  

---

## **Tech Stack**  
✔️ **Google AppsScript (JavaScript-based)**  
✔️ **Google Sheets (as a database)**  
✔️ **HTML, CSS, JavaScript** (for UI)  
✔️ **Google Workspace Services:**  
   🔹 SpreadsheetApp (Google Sheets handling)  
   🔹 HtmlService (for web UI)  
   🔹 CacheService & PropertiesService (for performance)  

---

## **Database Structure (Google Sheets)**  
### **Main Data Sheet**  
Stores all duty schedules with **Employee ID, Name, Date, Slot, Location, etc.**  

### **Swap Requests Sheet**  
Logs all duty swap requests with **status (Pending, Approved, Rejected), requester info, reason, and timestamps.**  

### **Employee Directory (Optional)**  
Maintains **employee master data** for quick lookups.  

---

## **License**  
This project is licensed under the **MIT License** – feel free to use, modify, and contribute! 😊  

---
