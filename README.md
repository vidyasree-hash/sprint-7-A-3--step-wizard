Multi-Step Onboarding Wizard

> A modern, accessible, and fully validated 3-step user onboarding flow built with React, TypeScript, Zod & React Hook Form.

![React](https://img.shields.io/badge/React-19-blue?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-blue?style=flat-square)
![Vite](https://img.shields.io/badge/Vite-6.x-646CFF?style=flat-square)
![Validation](https://img.shields.io/badge/Validation-Zod-green?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

Live Demo: [your-bolt-link.vercel.app](#) | Built with [Bolt.new](https://bolt.new)

### 📸 Preview
> Add your screenshots / screen recording here
/public/preview.png

---

### 🚀 What it does

This project implements a complete onboarding flow covering all 3 phases of a modern SaaS sprint:

*1. Personal Info* - Name, Email, Phone
*2. Account Details* - Username, Password, Confirm Password, Account Type (Personal / Business)
*3. Review & Submit* - Final review of all data before submission

#### Key Features:
- *State Persistence:* All entered data persists across steps using lifted state via react-hook-form.
- *Real-time Validation:* Instant feedback as you type using Zod schemas.
- *Smart Navigation:* Next button stays disabled until current step is valid. Full Back/Next support.
- *UX Enhancements:* Show/Hide password toggle, Account Type selector, password
