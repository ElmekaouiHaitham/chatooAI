# ChatooAI

ChatooAI is a multi WhatsApp chatbot platform for creating, connecting, and managing AI-powered WhatsApp bots from a web dashboard. It is designed for agencies, developers, resellers, and businesses that want to automate customer communication across multiple WhatsApp accounts.

## Live Project

- Website: [https://chatooai.vercel.app](https://chatooai.vercel.app)
- Frontend repository: [https://github.com/ElmekaouiHaitham/chatooai-frontend](https://github.com/ElmekaouiHaitham/chatooai-frontend)
- Backend repository: [https://github.com/ElmekaouiHaitham/chatooai-backend](https://github.com/ElmekaouiHaitham/chatooai-backend)

## Demo

<iframe width="560" height="315" src="https://www.youtube.com/embed/v2ytRQe4EOA" title="ChatooAI demo video" frameborder="0" allowfullscreen></iframe>

[Watch the demo on YouTube](https://www.youtube.com/watch?v=v2ytRQe4EOA)

## What ChatooAI Does

- Lets users create and configure AI WhatsApp bots.
- Connects bots to WhatsApp through QR-code login.
- Stores users, bots, plans, and usage data with Firebase.
- Uses a Node.js backend to manage WhatsApp sessions and AI replies.
- Provides dashboard, bot settings, billing, analytics, support, and admin screens.
- Supports a multi-bot architecture suitable for client, agency, and SaaS-style use cases.

## Project Structure

```text
frontend/chatooai-frontend   Next.js web dashboard
backend/chatooai-backend     Node.js, Express, Firebase, Baileys backend
```

## Repositories

### Frontend

The frontend is the browser application built with Next.js, React, TypeScript, Tailwind CSS, Firebase Auth, Firestore, and Chart.js. It contains the public site, dashboard, bot management UI, QR connection screen, billing/analytics pages, and admin views.

Read the frontend details in [frontend/chatooai-frontend/README.md](./frontend/chatooai-frontend/README.md).

### Backend

The backend is the service layer built with Node.js, Express, Firebase Admin, Firestore, Baileys, WebSockets, and OpenRouter. It handles protected API operations, WhatsApp sessions, QR broadcasts, bot state, plan checks, and AI replies.

Read the backend details in [backend/chatooai-backend/README.md](./backend/chatooai-backend/README.md).

## Contribute

ChatooAI is open for contribution. The best next steps are documented in each repository README so contributors can pick frontend or backend work without digging through the whole codebase first.
