# 🏥 AI-Agent Doctor Appointment Scheduling System 🤖

An end-to-end AI-powered Doctor Appointment Scheduling system built using n8n, Agentic AI, and real-time calendar integration to automate patient booking, availability checking, and confirmation without manual intervention.

# 🚀 Project Overview

This project automates the complete doctor appointment workflow:

Patient initiates booking via chat

AI collects required details

System checks real-time doctor availability

Prevents double booking

Books confirmed slot

Logs appointment data

Sends confirmation email

Designed for scalable, real-world healthcare operations.

# 🧠 Key Features

Conversational AI appointment booking

Real-time doctor availability check

Google Calendar integration

Conflict prevention (no double bookings)

Automated appointment confirmation

Centralized appointment logging

Alternative slot suggestion

24/7 autonomous scheduling

Production-ready Agentic AI architecture

# 🛠️ Tech Stack

n8n – Workflow automation

Google Gemini model

Google Calendar API – Availability & booking

Google Sheets – Appointment logging

Gmail API – Confirmation emails

Agentic AI Design – Decision-based scheduling

# 🔄 Workflow Architecture
Step-by-Step Flow

1️⃣ Chat Trigger
Patient initiates appointment request.

2️⃣ AI Doctor Scheduler Agent
AI collects:

Patient Name

Contact Information

Preferred Doctor

Preferred Date

Preferred Time

3️⃣ Conversation Memory Handling
Maintains structured interaction.

4️⃣ Check Doctor Availability (Google Calendar)

Validates selected time slot

Prevents overlapping bookings

5️⃣ Decision Logic

If available → Proceed to booking

If not available → Suggest alternative slots

6️⃣ Create Appointment Event

Book slot in Google Calendar

7️⃣ Log Appointment Data
Store:

Patient Name

Doctor Name

Date & Time

Booking Status

Timestamp

8️⃣ Send Confirmation Email

Appointment details sent instantly

# 🗄️ Data Storage – Short Explanation

This system stores structured appointment records for tracking and reporting.

Patient Name – Full name of the patient

Email – Contact email

Phone – Contact number

Doctor Name – Selected doctor

Appointment Date – Scheduled date

Appointment Time – Scheduled time

Status – Confirmed / Rescheduled

Created At – Timestamp of booking

# ⚙️ How to Use

Import workflow JSON into n8n

Configure:

OpenAI credentials

Google Calendar credentials

Google Sheets / Database credentials

Gmail credentials

Activate the workflow

Start chat interaction

AI handles booking end-to-end

# 📈 Use Cases

Clinic Appointment Automation

Hospital Front-Desk Automation

Private Practitioner Scheduling

Telemedicine Slot Booking

Healthcare Workflow Digitization

# 💼 Business Impact

Reduces receptionist workload by 60–70%

Eliminates scheduling conflicts

Enables 24/7 booking availability

Improves patient satisfaction

Creates centralized appointment records

# 🔐 Conflict Prevention Strategy

Real-time calendar validation

Booking confirmation before saving

Alternative slot recommendation

Centralized logging

# 🏗 Production-Ready Architecture

Modular workflow design

Multi-doctor scalability

Expandable to multi-location setup

EMR / HIS integration ready

SMS / WhatsApp integration ready
