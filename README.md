
Project Banner
nextdotjs typescript tailwindcss appwrite
A HealthCare Management System
Build this project step by step with our detailed tutorial on JavaScript Mastery YouTube. Join the JSM family!
📋 Table of Contents
🤖 Introduction
⚙️ Tech Stack
🔋 Features
🤸 Quick Start
🕸️ Snippets (Code to Copy)
🔗 Assets
🚀 More
🚨 Tutorial
This repository contains the code corresponding to an in-depth tutorial available on our YouTube channel, JavaScript Mastery.

If you prefer visual learning, this is the perfect resource for you. Follow our tutorial to learn how to build projects like these step-by-step in a beginner-friendly manner!



🤖 Introduction
A healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors, featuring administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications, all built using Next.js.

If you're getting started and need assistance or face any bugs, join our active Discord community with over 34k+ members. It's a place where people help each other out.



⚙️ Tech Stack
Next.js
Appwrite
Typescript
TailwindCSS
ShadCN
Twilio
🔋 Features
👉 Register as a Patient: Users can sign up and create a personal profile as a patient.

👉 Book a New Appointment with Doctor: Patients can schedule appointments with doctors at their convenience and can book multiple appointments.

👉 Manage Appointments on Admin Side: Administrators can efficiently view and handle all scheduled appointments.

👉 Confirm/Schedule Appointment from Admin Side: Admins can confirm and set appointment times to ensure they are properly scheduled.

👉 Cancel Appointment from Admin Side: Administrators have the ability to cancel any appointment as needed.

👉 Send SMS on Appointment Confirmation: Patients receive SMS notifications to confirm their appointment details.

👉 Complete Responsiveness: The application works seamlessly on all device types and screen sizes.

👉 File Upload Using Appwrite Storage: Users can upload and store files securely within the app using Appwrite storage services.

👉 Manage and Track Application Performance Using Sentry: The application uses Sentry to monitor and track its performance and detect any errors.

and many more, including code architecture and reusability

🤸 Quick Start
Follow these steps to set up the project locally on your machine.

Prerequisites

Make sure you have the following installed on your machine:

Git
Node.js
npm (Node Package Manager)
Cloning the Repository

git clone https://github.com/adrianhajdin/healthcare.git
cd healthcare
Installation

Install the project dependencies using npm:

npm install
Set Up Environment Variables

Create a new file named .env.local in the root of your project and add the following content:

#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the Appwrite website.

Running the Project

npm run dev
Open http://localhost:3000 in your browser to view the project.

🕸️ Snippets
tailwind.config.ts
app/globals.css
types/index.d.ts
types/appwrite.types.ts
lib/utils.ts
lib/validation.ts
constants/index.ts
🔗 Assets
Public assets used in the project can be found here

🚀 More
Advance your skills with Next.js 14 Pro Course

Enjoyed creating this project? Dive deeper into our PRO courses for a richer learning adventure. They're packed with detailed explanations, cool features, and exercises to boost your skills. Give it a go!

Project Banner

Accelerate your professional journey with the Expert Training program

And if you're hungry for more than just a course and want to understand how we learn and tackle tech challenges, hop into our personalized masterclass. We cover best practices, different web skills, and offer mentorship to boost your confidence. Let's learn and grow together!

Project Banner
BY AR
