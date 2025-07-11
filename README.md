# CHROME_EXTENSION_FOR_PRODUCTIVITY_MANAGEMENT

**COMPANY:** CODTECH IT SOLUTIONS

**NAME:** Jangala Hema kumar srinadh sai 

**INTERN ID:** CT08DM663

**DOMAIN:** Mern Stack Web Development

**DURATION:** 8 WEEKS

**MENTOR:** NEELA SANTOSH

---

**DESCRIPTION:**
During my internship, I was assigned **Task: to develop a Chrome Extension** that acts as a **Productivity Tracker**, aiming to **monitor user activity**, **block distracting websites**, and **generate daily productivity reports**. The extension integrates with a **MERN (MongoDB, Express, React, Node.js) stack backend** to store user preferences, sync data across devices, and generate insightful analytics. This task provided valuable experience in **browser extension development**, **full-stack architecture**, and **user-centric product design**.

---

### **What the Application Does:**

The **Productivity Tracker Chrome Extension** allows users to:

* **Track time spent** on different websites throughout the day
* **Block distracting websites** based on customizable preferences
* **Receive daily productivity reports** summarizing their web usage
* **Sync preferences and activity data** across multiple devices using the backend
* **Enable or disable tracking and blocking features** as needed

The goal is to simulate a real-world productivity enhancement tool similar to **StayFocusd, RescueTime, or Freedom**.

---

### **Main Features of the Extension:**

* **Website Usage Monitoring:** Records time spent on each visited site
* **Site Blocking:** Automatically blocks access to time-wasting websites
* **User Authentication & Preferences:** Stores custom settings per user
* **Daily Reports:** Summarizes total productive vs. non-productive time
* **Cross-Device Syncing:** Uses cloud backend to maintain user data consistency
* **Minimal UI** in Chrome Extension with pop-up options and settings panel

---

### **How I Built It:**

The project was split into two parts: the **Chrome extension frontend** and the **MERN backend server**.

#### **Chrome Extension (Frontend):**

* Built using **HTML, CSS, JavaScript**, and **React** (via Webpack build)
* Implemented **background scripts** to monitor browser activity
* Used **content scripts and Chrome APIs** to intercept URLs and track time
* Created a **popup dashboard UI** for displaying real-time usage and controls
* Integrated **options page** for users to customize their productivity settings
* Communicated with the **backend via REST API and token-based auth**

#### **Backend (MERN Stack):**

* **MongoDB** was used to store user activity logs and settings
* **Express.js** handled RESTful API routes
* **Node.js** served as the backend runtime environment
* **React.js (Admin Panel)** to visualize productivity reports (optional)
* **Authentication with JWT (JSON Web Tokens)** for secure user sessions
* **Daily report generation** via scheduled background tasks (e.g., using **node-cron**)

---

### **Features Implemented:**

* **Real-Time Monitoring:** Tracks site visits in the background
* **Custom Blocklist:** User-defined list of distracting websites
* **Authentication System:** Register/Login via backend
* **Daily Reports:** Pie charts and time logs of productivity stats
* **User Dashboard:** View history, manage blocklist, and update settings
* **Responsive Design:** Clean, functional UI inside the browser popup

---

### **Scalability & Future Enhancements:**

This system was built with scalability in mind and could be expanded to include:

* **Weekly and Monthly Analytics**
* **AI-based Site Categorization** (e.g., productive vs. unproductive)
* **Desktop Notifications** for time limits
* **Gamification Features** (e.g., productivity points)
* **Integration with Google Calendar or Notion**
* **Cloud syncing with encryption** for added privacy

---

### **Error Handling and Edge Cases:**

* Handled **network failures** gracefully when syncing data
* Prevented **duplicate tracking** from multiple tabs/windows
* Ensured users can't **bypass blocked sites via incognito mode**
* **Basic security measures** to protect user data and tokens
* Displayed **fallback messages in UI** if backend goes offline

---

### **Tools and Environment:**

* **Frontend (Extension):** HTML, CSS, JavaScript, React, Chrome Extension APIs
* **Backend:** Node.js, Express.js, MongoDB, JWT
* **Database:** MongoDB Atlas (Cloud)
* **Development Tools:** VS Code, Postman, Chrome DevTools, MongoDB Compass
* **Platform:** Local development and Google Chrome extension testing

---

### **What I Learned:**

This project helped me develop a deeper understanding of:

* **Chrome extension architecture** including background scripts and manifest files
* **User activity tracking** and **behavioral analytics**
* **Full-stack development** using the **MERN stack**
* **RESTful API integration** and **token-based authentication**
* How **real-time monitoring** and **site-blocking logic** work together
* Building **secure, scalable, and user-friendly tools**
* Importance of **UX in productivity tools** and **minimalism in UI design**

---

By completing this task, I gained practical skills in building **real-world browser extensions integrated with full-stack cloud systems**. It strengthened my ability to handle **cross-platform development** and gave me confidence to build **impactful productivity tools** that can scale to real users.

**OUTPUT:**



![Image](https://github.com/user-attachments/assets/7b25411b-5a86-45a1-af96-785ffe210b98)

![Image](https://github.com/user-attachments/assets/6d6ba683-e7c3-45e2-a0f3-10f3e970e487)
