# Ndhiwa Sub-County Children's Office - PROTECT System

## Project Overview

**Ndhiwa Sub-County Children's Office** is a comprehensive web application for managing child protection cases, reporting, and stakeholder coordination in compliance with the Children's Act 2022 and Data Protection Act 2019.

### Vision
An online platform that digitizes Sub-County Children's Office operations with three access tiers:
- **Public Tier**: View-only access to general information
- **Case Management Tier**: AI-powered grounded chat for case reporting and follow-ups
- **Stakeholder Portal**: Authenticated access for office staff and partners via messenger invitations

### Core Sections (Phase 1)
1. Dashboard - Case overview and activity
2. Cases - Case registry and management
3. Children's Registry - Database of vulnerable children
4. Duty Bearers - Partner organizations and officials
5. Public Reports - Community/Facebook reports
6. Probono Lawyers - Directory of pro-bono legal services
7. Stakeholders - Portal for staff and partners
8. PROTECT - Foundational truths and ecosystem

### Future Additions (Phase 2)
- Legal Advisory Folder (155 statutes)
- Psychosocial Counseling Folder

## Tech Stack

**Frontend:**
- React.js with Hooks
- Material-UI (MUI) for design
- Redux for state management
- Axios for API calls

**Backend:**
- Node.js with Express.js
- Firebase Cloud Functions (serverless)
- Supabase for database (PostgreSQL)
- Firebase Authentication

**Security:**
- SHA-256 encryption for data masking
- JWT tokens for authentication
- Local-first data storage
- Environment-based configuration

**Deployment:**
- Firebase Hosting (frontend)
- Cloud Functions (backend)
- GitHub Actions (CI/CD)

## Firebase Project

- **Project ID:** protect-48d71
- **Console:** https://console.firebase.google.com/u/4/project/protect-48d71/overview
- **Plan:** Blaze (pay-as-you-go)

## Quick Start

### Prerequisites
- Node.js v18+
- npm or yarn
- Firebase CLI
- Git

### Installation

```bash
# Clone repository
git clone https://github.com/protect-webapp/Ndhiwa_Webapp.git
cd Ndhiwa_Webapp

# Setup Frontend
cd frontend
npm install
cp .env.example .env.local

# Setup Backend (new terminal)
cd backend/functions
npm install
cp .env.example .env
```

### Local Development

```bash
# Terminal 1: Firebase Emulator
firebase emulators:start

# Terminal 2: Frontend
cd frontend
npm start

# Terminal 3: Backend
cd backend/functions
npm run serve
```

## Next Steps

1. ✅ **Repository Structure Created**
2. ⏳ **Configure Firebase credentials**
3. ⏳ **Setup Supabase database**
4. ⏳ **Deploy to Firebase Hosting**
5. ⏳ **Add Legal Advisory Folder (155 statutes)**
6. ⏳ **Add Psychosocial Counseling Folder**

## Support

For issues or questions, please open an issue on GitHub.
