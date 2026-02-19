# nuChat (Archived)

**nuChat** was a private, secure, real-time chat platform built with a **privacy-first mindset**, focused on simplicity, transparency, and full user control—especially for use on shared university lab PCs.

> 🔒 **Project Status:** Archived / Development stopped  
> 🗓 **Active Period:** Nov 2025 – Feb 2026  
> 🔗 **Live Project (archived):** [https://thenuchat.com](https://thenuchat.com) | [https://thenuchat.netlify.app/](https://thenuchat.netlify.app/)  

> ⚠ Note: The live links may no longer be active as the project has been sunset.

---

## Overview

nuChat explored how real-time communication could work **without requiring email addresses, phone numbers, or persistent personal identifiers** on shared computers.

Users could create accounts using **only a username and password**, with full control over their data, including permanent deletion.

---

## Vision

To explore a communication platform where:
- Privacy is the default
- Users fully control their identity and data
- No tracking or hidden data retention exists
- Real-time communication remains fast and simple

---

## Core Principles

- No email, no phone number  
- No tracking  
- No hidden data retention  
- Permanent deletion means permanent  
- User-first design and control  

---

## Version 1 (MVP) – Implemented Features

### Account System
- Username-based registration
- Password authentication
- Optional gender selection
- No email or phone number required

### Friend System
- Search users by username or system-generated unique ID
- Send, accept, reject, and remove friends

### Chat
- Private one-to-one real-time chat
- Public chat with **3 open rooms** for instant conversations

### Privacy & Control
- Permanent account deletion with full data removal
- Zero tracking
- No hidden data storage

---

## Version 2 – Implemented Enhancements

### Group Chat (Role-Based Control)

**Owner**
- Add and remove members
- Promote and demote admins
- Transfer ownership
- Delete group

**Admins**
- Add and remove members

**All Members**
- Can leave groups at any time

### Privacy Improvements
- Only **Owners and Admins** could view group details
- Groups automatically deleted if members dropped below **3**

### Existing Features Retained
- Friend system
- Private chats
- Public chat rooms

---

## What I Learned

- Designing and operating real-time messaging and presence systems
- Managing online/offline state using Redis
- Balancing privacy guarantees with usability
- Shipping multiple iterations from MVP to feature-complete versions
- Learning that **distribution, timing, and retention matter more than feature depth**

---

## Repository Status

- This repository is **archived**
- Source code is intentionally not published
- Maintained as a **case study and learning reference**

---

## Philosophy

nuChat was built to **serve users**, not to extract value from them.

No surveillance.  
No data harvesting.  
No compromise.

---

## Author

Built as an independent project to explore privacy-first system design, real-time architecture, and early-stage product decision-making.