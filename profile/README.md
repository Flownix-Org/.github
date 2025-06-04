# 🤖 Flownix: Visual Chatbot Builder for Social Media

Welcome to **Flownix** — a powerful, intuitive platform that empowers creators, businesses, and developers to design, manage, and export intelligent chatbots to their favorite social media channels with zero coding required.

## 🚀 What is Flownix?

**Flownix** is a web-based visual chatbot flow builder. With a simple drag-and-drop interface, users can design complex conversational experiences and deploy them across platforms like:

- Facebook Messenger
- Instagram DMs
- WhatsApp (via Business API)
- Telegram
- Discord
- Web Chat Widgets
- And more!

Whether you're a marketer, a customer support lead, or a solo founder, Flownix gives you the tools to automate communication, improve engagement, and scale interactions across social media.

---

## 🌟 Features

### 🔧 Drag-and-Drop Flow Builder
- Create chatbot conversations visually with reusable nodes and connectors.
- Conditional logic, branching paths, delays, buttons, and multimedia support.

### 📲 Social Media Integration
- Direct export and deployment to supported platforms.
- OAuth authentication for easy linking of Facebook/Instagram/Telegram accounts.

### 🧠 Fallback AI (Optional)
- Integrate OpenAI’s GPT to handle unknown user responses with natural-sounding fallback replies.

### 📊 Built-in Analytics
- Track open rates, message flows, click-through rates, and drop-offs in real time.

### 🗃️ Templates & Cloning
- Start faster with pre-built templates for lead generation, FAQs, surveys, and e-commerce.

### 🔐 User Management
- Role-based access control for teams.
- Secure login with Firebase Authentication.

---

## 🖼️ Screenshots

### 🌐 Landing Page
![Landing Page](profile/landing.png)

### 🧩 Drag-and-Drop Flow Builder
![Flow Builder](profile/webflow.png)

---

## 🛠️ Tech Stack

| Layer              | Tools                                 |
|--------------------|---------------------------------------|
| Frontend           | React.js, Tailwind CSS, Zustand       |
| Backend            | Firebase Functions, Firestore         |
| Auth & Hosting     | Firebase Authentication, Hosting      |
| Social Integrations| Facebook Graph API, Telegram Bot API, Webhooks |
| Fallback AI        | OpenAI (GPT-4 via API)                |

---

## 📦 Installation (For Local Development)

```bash
# Clone the repository
git clone https://github.com/flownix/chatbot-builder.git
cd chatbot-builder

# Install dependencies
npm install

# Start the development server
npm run dev
