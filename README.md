# Converso AI Trainer

Converso AI Trainer is a real-time, AI-powered teaching platform that lets you build and personalize your own learning companions. Choose a name, subject, voice, and personality, and start interactive voice-based learning sessions that feel natural and engaging.

---
## 🚀 Features

- **Custom AI Companions:** Build personalized AI tutors by selecting subject, topic, voice (male/female), and conversation style.
- **Real-Time Voice Sessions:** Natural language voice conversations with your AI tutor.
- **Session Management:** Simple controls to start, connect, and end sessions.
- **Live Transcripts:** Real-time transcription and feedback during sessions.
- **Subject Variety:** Supports subjects like Maths, Science, Language, History, Coding, etc.
- **User Authentication:** Secure login and user management.
- **Modern UI:** Responsive, attractive interface using modern React and Next.js practices.

---
## ✨ Live Demo

[Converso_AI](https://conversoai-git-master-adamyas-projects-d49b2b0c.vercel.app/)
---
## 🛠️ Tech Stack & Services

### Frontend

- **Next.js:** React framework for server-side rendering, routing, and API integration.
- **React:** UI library for building interactive user interfaces.
- **TypeScript:** Strongly typed JavaScript for improved code quality and maintainability.
- **Tailwind CSS:** Utility-first CSS framework for rapid, modern UI styling.

### AI, Voice, and Language Services

- **OpenAI GPT-4:** Provides advanced conversational AI capabilities, powering your AI tutors’ responses and explanations.
- **11labs (ElevenLabs):** Industry-leading AI voice synthesis service; generates natural-sounding AI tutor voices.
- **Deepgram:** Fast, accurate speech-to-text API used for real-time transcription of user and AI speech.

### Authentication & User Management

- **Clerk:** Modern authentication and user management, providing secure sign-in, sign-up, and user session handling.

### Monitoring & Error Tracking

- **Sentry:** Real-time error tracking and performance monitoring to catch bugs and issues in production.

### Utilities, Forms, and State Management

- **react-hook-form:** Lightweight, flexible form management for React.
- **zod:** Schema validation for form inputs.
- **clsx & tailwind-merge:** Efficient class name merging for dynamic styling.
- **lottie-react:** For animated illustrations and visual feedback in the UI.
- **@hookform/resolvers:** Integrates Zod with react-hook-form for declarative form validation.
- **Next Image:** Optimized image component for faster loading.
- **@jsmastery/utils:** Utility functions for handling query strings and URL manipulation.

### Project Structure & Build Tools

- **Vercel (optional for deployment):** Recommended platform for deploying Next.js projects (if you deploy here, mention your URL).
- **Node.js & npm:** JavaScript runtime and package management for development and builds.

---

## 📦 Full List of Major Packages

```json
{
  "dependencies": [
    "next",
    "react",
    "react-dom",
    "typescript",
    "tailwindcss",
    "@clerk/nextjs",
    "@sentry/nextjs",
    "@hookform/resolvers",
    "react-hook-form",
    "zod",
    "clsx",
    "tailwind-merge",
    "lottie-react",
    "deepgram",
    "openai",
    "11labs",
    "@jsmastery/utils"
  ]
}
```
## 🔍 Service/Package Explanations
```bash

| Service/Package       | Purpose                                                                 |
|------------------------|-------------------------------------------------------------------------|
| **Next.js**            | Web framework for React, enabling SSR, API routes, and static generation |
| **React**              | Component-based UI library                                               |
| **TypeScript**         | Adds static typing to JavaScript for better maintainability             |
| **Tailwind CSS**       | Rapid UI development with utility-first CSS classes                     |
| **OpenAI GPT-4**       | Generates intelligent, context-aware tutor responses in real time       |
| **11labs**             | Synthesizes realistic AI-generated voices for companions                |
| **Deepgram**           | Provides live speech-to-text transcription for interactive sessions     |
| **Clerk**              | Handles authentication and session management securely                  |
| **Sentry**             | Error monitoring and logging for production                             |
| **react-hook-form**    | Easy and performant form management in React                            |
| **zod**                | Schema validation for form input and API data                           |
| **clsx & tailwind-merge** | Efficient merging of Tailwind class names                             |
| **lottie-react**       | Renders Lottie animations for rich UI feedback                          |
| **@jsmastery/utils**   | Utilities for managing query strings and URLs                           |
| **Vercel** *(optional)*| Seamless deployment and hosting for Next.js apps                        |

```
---
## 🏗️ Installation

```bash
git clone https://github.com/Adamya-Kumar/Converso_AI_Trainer.git
cd Converso_AI_Trainer
npm install
```

---

## ▶️ Running Locally

```bash
npm run dev
```

Open your browser and visit: [http://localhost:3000](http://localhost:3000)

---

## 🔑 Environment Variables

Create a `.env.local` file in your project root:

```env
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
```

> You'll need to sign up on these platforms to get your own API keys.

---

## 📝 Usage

1. **Sign In:** Securely authenticate with Clerk.
2. **Build a Companion:** Select your subject, topic, voice, and tone.
3. **Start a Session:** Use your voice to interact with the AI tutor.
4. **Review:** End your session and view transcripts for reference.
   
---
## 🙏 Credits

- [OpenAI](https://openai.com/)
- [Deepgram](https://deepgram.com/)
- [11labs](https://www.elevenlabs.io/)
- [Clerk](https://clerk.dev/)
- [Sentry](https://sentry.io/)

---

## 📄 License

**MIT** — feel free to use and modify this project.
