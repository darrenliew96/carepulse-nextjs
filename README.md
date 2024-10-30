# 🏥 Patient Management and Appointment Booking System
A web-based application that allows patients to register, book appointments with doctors, and receive SMS notifications upon confirmation. Admins can efficiently manage appointments and ensure smooth operations. The system also ensures optimal performance tracking and secure file storage.

## 🚀 Features

#### 1. Patient Registration & Profile Management
- Users can sign up and create a personal profile as a patient.
- Maintain personal information for easy future interactions.

### 2. Appointment Booking System

##### Patient-Side:
- Schedule multiple appointments with doctors.
- Flexible booking to suit patient convenience.

##### Admin-Side:
- View and manage all appointments in the system.
- Confirm and set appointment times for patients.
- Cancel appointments when necessary.

### 3. Appointment Notifications via SMS
- Automatic SMS notifications are sent to patients when appointments are confirmed.
- Keeps patients informed and reduces no-shows.


## ⚙️ Management Features

#### 4. File Upload Using Appwrite Storage
- Secure and seamless file uploads.
- Appwrite integration ensures data safety and easy management.

#### 5. Performance Tracking with Sentry
- Real-time monitoring of application performance.
- Detects errors and tracks issues to improve the systems reliability.




## 📱 User Experience & Design

#### Responsive Design:
- Works smoothly across all device types and screen sizes (desktop, tablet, mobile).
- Ensures a seamless experience for all users.
- Code Architecture & Reusability:

#### Modular and scalable code design.
- Promotes component reusability for efficient development and maintenance.


##  Quick Start

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/quanliew28/carepulse-nextjs.git
cd carepulse
```

**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Set Up Environment Variables**

Create a new file named `.env.local` in the root of your project and add the following content:

```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite website](https://appwrite.io/).

**Running the Project**

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser to view the project.
