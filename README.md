# 🗂️ Task Tracker – Power Apps Application

A fully functional **Task Tracker** application built using **Microsoft Power Apps**, designed to help users create, manage, and track daily tasks with automated reminders using **Power Automate**.

This project demonstrates:
- Canvas app design
- Task management UI
- SharePoint/Excel backend (if used)
- Daily reminder automation using Power Automate
- No-code/low-code application development skills

---

## ✨ Features

### 📝 **1. Add, Edit, and Delete Tasks**
- Create tasks with priority, due date, and category
- Update task status: Pending → In Progress → Completed
- Delete tasks that are no longer needed

### 📅 **2. Daily Reminder Notifications (Power Automate)**
A custom Power Automate flow sends **daily reminders** to make sure no task is missed.

  Automation includes:
- Scheduled daily trigger  
- Filtering incomplete tasks  
- Sending notifications or email reminders  
- Personalized task summaries

### 🎨 **3. Clean & Simple User Interface**
- Clear task list layout  
- Buttons for adding new tasks  
- Filters for completed / pending tasks  
- Mobile-friendly UI

### 🔍 **4. Task Filters and Sorting**
- Filter by status, priority, deadline  
- Sort by due date or importance  
- View tasks in a structured format

---

## 🖥️ Screenshots

_Add your screenshots in the `/images` folder and reference them here._

For example:

### 📌 Home Screen
![Task Tracker Home]([images/home.png](https://github.com/DishaDhake/Task-Tracker-App/blob/main/IMG_1451.PNG)

### 📝 Add Task Screen
![Add Task](images/add_task.png)

### 📬 Daily Reminder Flow
![Power Automate Flow](images/flow.png)

---

## 🔧 Technologies Used

| Technology | Purpose |
|-----------|---------|
| **Power Apps (Canvas App)** | UI development & logic |
| **Power Automate** | Daily reminder automation |
| **SharePoint / Excel / Dataverse** | Backend data storage |
| **Microsoft 365** | Integration & connectivity |

---

## 🔁 Power Automate Flow – Overview

Your daily reminder flow includes:

1. **Trigger**: Recurrence (every day)
2. **Step**: Get items from your Task List
3. **Filter**: Only tasks where Status = “Pending”
4. **Action**:
   - Send email notification  
   - OR push mobile notification (Power Apps / Power Automate app)  
5. **Outcome**:
   - User receives daily reminder of incomplete tasks

This shows your understanding of:
- Automation  
- Condition-based logic  
- Trigger scheduling  
- Notification systems  

---

## 🚀 How to Use the App (If Someone Downloads It)

1. Download the screenshots or documentation from this GitHub repo  
2. Recreate the UI in Power Apps (optional)  
3. Or request the creator for the exported app package (optional)  
4. (If applicable) Import the Power Automate flow  
5. Update data connections  
6. Run the app

> Note: This project is shared for **portfolio and learning purposes**, so only screenshots and documentation are included.

---

## 📘 Purpose of This Project

This Power App was built to:
- Improve personal productivity  
- Learn Power Apps UI design  
- Practice building automation workflows  
- Showcase no-code development skills on GitHub  
- Demonstrate end-to-end application design  
- Strengthen business analytics + automation portfolio  

---

## 📈 Future Enhancements

- Add push notifications for overdue tasks  
- Add category-based dashboards  
- Integrate Power BI charts  
- Add user authentication  
- Add attachment and notes to tasks  

---

## 👩‍💻 Created By
**Disha Dhake**  
Power Apps • Power Automate • Business Analytics  
