# Insolvency Case-Management CRM: Cloud Edition

A case-management CRM I designed and built for a law office that handles debt-relief cases. The office uses it every day.

This repository holds the compiled web build. The source is private because this is a client project.

## Highlights

- **Clients and case files**: debts, payments, tasks, calendar and reports
- **Leads screen** fed by my [WhatsApp AI customer-service bot](https://github.com/SharonElimelech/whatsapp-ai-service-bot), with lead summaries the office can edit
- **WhatsApp inbox**: replies from a person, a per-client switch that mutes the bot, imported chat history, and one-click "summarize to case"
- **Payment reminders**: automatic WhatsApp reminders, with a preview before anything is sent
- **Documents** stored in Google Drive, plus PDF export
- **Hebrew / RTL** interface

## Stack

React · TypeScript · Vite · Tailwind CSS · Supabase (PostgreSQL) · Google Drive API

## Desktop edition

The project started as an offline-first desktop app built with Electron, React, TypeScript and SQLite (WebAssembly). It has automatic backups, multi-PC sync and a one-click Windows installer.

---

Built by [Sharon Elimelech](https://sharon-elimelech.vercel.app), Full-Stack & AI Engineer.
