# Event Management Platform 🎉

A full-stack event management platform that allows users to create, manage, and view events. The platform supports real-time updates, user authentication, and responsive design. It is deployed on free-tier hosting services for easy access.

---

## 🛠 Features

### Frontend:
1. **User Authentication**:
   - Register and login functionality.
   - "Guest Login" option for limited access.

2. **Event Dashboard**:
   - Displays a list of upcoming and past events.
   - Filter events by category and date.

3. **Event Creation**:
   - Form to create events with details like:
     - Event name.
     - Description.
     - Date and time.
     - Categories and more.

4. **Real-Time Attendee List**:
   - Updates the number of attendees for events in real-time.

5. **Responsive Design**:
   - Seamlessly adapts to mobile, tablet, and desktop devices.

### Backend:
1. **Authentication API**:
   - Secure JWT-based authentication for user sessions.

2. **Event Management API**:
   - CRUD operations for events.
   - Ownership restrictions for event creators.

3. **Real-Time Updates**:
   - Powered by WebSockets using `Socket.IO`.

4. **Database**:
   - Efficient storage of user and event data using MongoDB Atlas.

---

## 🚀 Deployment Details

### Frontend:
- **Hosting**: Deployed on Firebase Hosting.
- **Live URL**: [Event Management Platform](https://event-management-system-16761.web.app)

### Backend:
- **Hosting**: Deployed on [Render](https://render.com) (or [Railway](https://railway.app)).
- **Live URL**: [Backend Deployment Link](#) *(Replace with actual URL)*.

### Database:
- **Service**: MongoDB Atlas (Free Tier).

### Image Hosting:
- **Service**: Cloudinary Free Tier.

---

## 🔧 Tech Stack

### Frontend:
- **Framework**: React.js
- **Styling**: Tailwind CSS
- **Real-Time Communication**: Socket.IO Client

### Backend:
- **Runtime**: Node.js
- **Framework**: Express.js
- **Authentication**: JWT
- **Real-Time Communication**: Socket.IO

### Database:
- **Service**: MongoDB Atlas

### Hosting:
- **Frontend**: Firebase Hosting
- **Backend**: Render or Railway.app

### Image Hosting:
- **Service**: Cloudinary

---

## ⚙️ How to Run Locally

### Prerequisites:
1. Node.js installed.
2. MongoDB Atlas account setup.
3. Cloudinary account setup.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository-name.git
