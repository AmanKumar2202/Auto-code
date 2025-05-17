
# Auto-code

**Auto-code** is a modern, AI-powered, online IDE that supports code generation, execution, and collaboration across multiple languages. With support for theming, code sharing, profile tracking, and flexible pricing — it’s built to help developers code smarter and faster.

---

## 🚀 Key Features

- 💻 **Online IDE with Multi-language Support**: Write and run code in **10 different programming languages**.
- 🎨 **Customizable Coding Experience**: Choose from **5 VSCode themes** to personalize your interface.
- ✨ **Smart Output Handling**: Get intelligent success and error messages based on code execution.
- 💎 **Flexible Pricing Plans**: Choose between **Free and Pro** tiers for additional features.
- 🤝 **Community-driven Code Sharing**: Share your code snippets and discover others’.
- 🔍 **Advanced Filtering & Search**: Easily find your code history or shared snippets.
- 👤 **Personal Profiles**: Track your **execution history** and manage your shared content.
- 📊 **Statistics Dashboard**: View comprehensive stats on usage, performance, and history.
- ⚙️ **Customizable Font Size**: Adjust your editor to your reading and coding preference.
- 🔗 **Webhook Integration Support**: Connect to external tools via webhooks.
- 🌟 **Professional Deployment Guide**: Step-by-step walkthrough to deploy your own version.

---

## 🛠️ Tech Stack

| Layer            | Technology                      |
|------------------|----------------------------------|
| **Frontend**     | [Next.js 15](https://nextjs.org/) |
| **Backend**      | [Convex](https://www.convex.dev/) |
| **Authentication** | [Clerk](https://clerk.dev/)         |
| **Language**     | TypeScript                      |
| **Styling**      | Tailwind CSS                    |
| **Code Editor**  | Monaco Editor (VSCode-based)     |

---

## 📦 Installation

### 1. Clone the repository

```bash
git clone https://github.com/AmanKumar2202/Auto-code.git
cd Auto-code
```

### 2. Install dependencies

```bash
npm install
# or
yarn install
```

---

## 🧪 Running Locally

```bash
npm run dev
# or
yarn dev
```

Then, open [http://localhost:3000](http://localhost:3000) in your browser.

> **Note**: You may need to configure Convex and Clerk with your credentials. See `.env.example` for configuration details.

---

## 📁 Project Structure

```
Auto-code/
│
├── src/               # Main source code
│   ├── app/           # App routing and pages
│   ├── components/    # UI components
│   ├── lib/           # Utility functions
│   └── styles/        # Global and component styles
│
├── public/            # Static assets
├── convex/            # Convex backend functions
├── .env.example       # Example environment variables
├── next.config.js     # Next.js configuration
├── tailwind.config.ts # Tailwind CSS configuration
└── tsconfig.json      # TypeScript configuration
```

---

## 🙌 Acknowledgements

- [Next.js](https://nextjs.org/)
- [Convex](https://www.convex.dev/)
- [Clerk](https://clerk.dev/)
- [Monaco Editor](https://microsoft.github.io/monaco-editor/)
- [Tailwind CSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
