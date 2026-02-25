# 🏥 Hospital Booking AI Agent 🤖
AI-Powered Doctor Appointment Scheduling System

An end-to-end Agentic AI workflow built in n8n that automates doctor appointment scheduling using conversational AI, real-time calendar validation, and automated confirmation.

Designed for clinics, hospitals, and private practitioners to eliminate manual booking processes and prevent scheduling conflicts.

# 🚀 Project Overview

This system automates the complete appointment lifecycle:

- 💬 Patient initiates booking via chat
- 🧠 AI collects required details
- 📅 System checks real-time doctor availability
- ❌ Prevents double booking
- ✅ Books confirmed slot
- 📊 Logs appointment data
- 📧 Sends instant confirmation

Fully automated. No receptionist intervention required.

# ✨ Key Features

- Conversational AI appointment booking
- Real-time availability validation (Google Calendar)
- Automatic conflict detection
- Intelligent alternative slot suggestion
- Google Sheets appointment logging
- Instant confirmation email (Gmail API)
- Memory-enabled multi-step conversation
- 24/7 autonomous scheduling

# 🏗 Tech Stack

- n8n – Workflow automation
- Google Gemini Model – Conversational AI
- Google Calendar API – Slot validation & booking
- Google Sheets API – Appointment logging
- Gmail API – Confirmation email automation
- Agent AI Architecture – Decision-driven scheduling

# 🔄 Workflow Architecture
1️⃣ Chat Trigger

Patient initiates conversation.

2️⃣ AI Doctor Scheduler Agent

AI collects:

1. Patient Name
2. Email / Phone
3. Preferred Doctor
4. Preferred Date
5. Preferred Time

Booking Action (Book / Check / Modify / Cancel)

3️⃣ Conversation Memory

Maintains structured multi-step interaction to avoid losing context.

4️⃣ Availability Check (Google Calendar)

Validates selected time slot

Detects overlapping bookings

Ensures real-time accuracy

5️⃣ Decision Logic

If slot available → Proceed to booking

If unavailable → Suggest alternative time slots

6️⃣ Create Appointment Event

Books event in Google Calendar

Updates doctor schedule instantly

7️⃣ Log Appointment (Google Sheets)

Stores:
- Patient Name
- Doctor Name
- Appointment Date
- Appointment Time
- Status
- Timestamp

Provides centralized tracking and reporting.

8️⃣ Send Confirmation Email

Sends appointment details to patient

Provides confirmation and summary

# 🗄 Data Structure
Field	Description
- Patient Name	Full name of patient
- Email	Contact email
- Phone	Contact number
- Doctor Name	Selected doctor
- Appointment Date	Scheduled date 
- Appointment Time	Scheduled time
- Status	Confirmed / Rescheduled
- Created At	Booking timestamp

# 🔐 Conflict Prevention Strategy

- Real-time calendar validation
- Slot verification before booking
- Alternative time suggestion
- Centralized logging
- Eliminates double bookings and scheduling overlaps.

# ⚙️ How to Use
1️⃣ Import Workflow

Import the workflow JSON into n8n.

2️⃣ Configure Credentials

Set up:

- Google Gemini API
- Google Calendar credentials
- Google Sheets credentials
- Gmail credentials

3️⃣ Activate Workflow

Enable the workflow in n8n.

4️⃣ Start Chat

Initiate booking conversation — the AI handles everything automatically.

# 📈 Use Cases

- Clinic Appointment Automation
- Hospital Scheduling Systems
- Private Practitioner Management
- Telemedicine Slot Booking
- Healthcare Workflow Digitization

# 💼 Business Impact

- 60–70% reduction in manual scheduling workload
- Zero double bookings
- 24/7 automated appointment booking
- Faster patient response time
- Centralized reporting & audit trail

# 🏗 Production-Ready Design

- Modular workflow structure
- Multi-doctor scalability
- Expandable to multi-location support
- EMR / HIS integration ready
- SMS / WhatsApp integration ready
- Cloud-deployable architecture

# 📌 Repository Contents

- workflow.json – n8n workflow export
- README.md – Project documentation

# 🎯 Summary

- This AI Agent replaces traditional receptionist-based scheduling with an intelligent, real-time, automated system.
- Built using Agent AI principles, this workflow demonstrates scalable healthcare automation using n8n and Google APIs.
