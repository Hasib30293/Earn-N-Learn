# Skill Share Campus

Skill Share Campus is a full-stack campus collaboration and marketplace platform where students can share skills, find paid opportunities, exchange study materials, and collaborate through real-time messaging. It combines a social campus hub with practical work tools such as application tracking, project and task management, and wallet/escrow features to help students learn, earn, and work together in one place.

## Demo

[![Watch the demo](https://img.youtube.com/vi/jBf_TcsDPIE/maxresdefault.jpg)](https://youtu.be/jBf_TcsDPIE)

**Click the image above to watch the demo video**

Or watch directly: [https://youtu.be/jBf_TcsDPIE](https://youtu.be/jBf_TcsDPIE)

## Key Features

- Campus marketplace for skills, jobs, and academic materials
- Campus hub with posts, discussions, and polls
- Real-time direct and group messaging
- My Work dashboard for applications, invoices, and projects
- Project collaboration with task and time management
- Wallet tools including transactions, savings goals, and escrow flows

## Tech Stack

- React + TypeScript + Vite
- Tailwind CSS + shadcn/ui
- Express + MySQL
- Socket.IO for real-time communication

## Setup Instructions

```bash
# Clone the repository
git clone https://github.com/yourusername/skill-share-campus.git

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env

# Run database migrations
npm run migrate

# Start development server
npm run dev
