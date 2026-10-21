# 🦷 BrightSmile Dental – AI Receptionist Agent

An AI receptionist for a dental clinic, built on [Agentplace](https://agentplace.io). It answers patient questions, helps them choose a service, books appointments step by step, and safely escalates urgent cases.

> **Demo project:** BrightSmile Dental is a fictional clinic created to showcase the agent. No real bookings or SMS are made.

## 🔗 Try it live

👉 **[Chat with the agent]([[PASTE AGENT LINK]](https://ij215hssi3ik.run.agentplace.io/))**

Try asking: *"How much is whitening?"*, *"I want to book"*, or *"My tooth is killing me"*.

## ✨ What it does

- **Answers questions** about services, prices, hours, location and insurance, using only the clinic's knowledge base
- **Helps choose a service** by asking 1–2 simple questions
- **Books appointments** by collecting name → phone → service → preferred time one at a time, then confirming the details
- **Handles urgent cases** by giving the emergency line for severe pain and directing life-threatening symptoms to 911 / ER
- **Stays safe** by never giving diagnoses or medication advice and never inventing prices
- **Replies in the patient's language** (e.g. Spanish)
- **Redirects off-topic questions** politely back to the clinic

## 📸 Screenshots

| Welcome | Booking flow | Urgent case |
|---------|-------------|-------------|
| ![Welcome](screenshots/welcome.png) | ![Booking](screenshots/booking.png) | ![Urgent](screenshots/urgent.png) |

## 📁 Repository contents

| File | Description |
|------|-------------|
| [`prompt.md`](prompt.md) | The instructions used to build the agent |
| [`knowledge-base.md`](knowledge-base.md) | Clinic info: services, prices, hours, FAQ |
| [`test-cases.md`](test-cases.md) | 12 test cases, issues found and how they were fixed |

## 🧪 Testing

The agent was tested against 12 scenarios covering pricing, booking, emergencies, medical-advice refusal, off-topic questions and language switching. Issues found during testing were fixed and retested. See [`test-cases.md`](test-cases.md).

## 🚀 Next steps for production

- Connect a real calendar for live availability
- Send SMS confirmations
- Log bookings to a CRM
- Add reminders and rescheduling

## 👤 Built by

**Ahmed Wasti**, full stack developer and AI agent builder
[GitHub](https://github.com/Ahmed654-at)
