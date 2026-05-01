# Ridoword — Cyberboard & Community Node

Ridoword (Hellologi) is a high-performance, full-stack CMS and community platform built with a futuristic cyberpunk aesthetic. It features a robust SQL backend, real-time analytics, and a multi-role user system.

![Ridoword Interface](https://via.placeholder.com/800x450.png?text=Ridoword+Cyberpunk+UI)

## 🚀 Features

- **Full-Stack Architecture**: Express.js & MySQL integration with automated installation wizard.
- **Cyberpunk UI**: Advanced CSS-driven theme with glassmorphism, scanlines, and matrix-style terminal animations.
- **Dynamic Content**: Live RSS feeds, newsletter system, and markdown-rendered articles.
- **User Ecosystem**:
  - Secure registration & login (JWT + Bcrypt).
  - Rich user profiles with social links.
  - Role-based permissions (User, Moderator, Sysadmin).
  - Public profile pages (`/u/:username`).
- **Post Engine**: Members can write and submit posts with a real-time Markdown preview.
- **Admin Command Center**:
  - Dashboard with live visitor stats.
  - Content management (Posts, Categories, Tags).
  - User management (Edit roles, Activate/Deactivate, Delete).
  - Post approval queue.
  - Global site settings (Threat levels, Site name).

## 🛠️ Technology Stack

- **Frontend**: React (Vite), React Router, Lucide Icons.
- **Backend**: Node.js, Express.js.
- **Database**: MySQL (MariaDB).
- **Security**: JWT, BcryptJS, Protected Routes.
- **Styling**: Vanilla CSS (Cyberpunk Design System).

## 📥 Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/Rido59/Ridoword.git
   cd Ridoword
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```
   *Note: This starts both the Vite frontend and the Node.js backend concurrently.*

4. **Setup Database**:
   Open your browser to `http://localhost:5173`. If first run, you will be automatically redirected to the **Cyberpunk Installation Wizard**. Enter your MySQL credentials to bootstrap the system.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.
