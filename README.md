# 🚀 EdTech Admin Portal - Matrix Control

<div align="center">
  <img <img width="1470" alt="image" src="https://github.com/user-attachments/assets/0f7838e9-739b-4f43-b0cb-7475068b6d66" />

  <h3>Advanced Administration Portal for EdTech Platform Management</h3>
</div>

## 🌟 Overview

Matrix Control is a sophisticated admin portal designed for educational technology platforms. It provides a comprehensive set of tools to manage courses, batches, enrollments, teaching materials, MCQs, and demo sessions all from one centralized dashboard.

Built with a sleek, modern UI featuring a cosmic gradient design theme, Matrix Control offers intuitive navigation and secure admin-only access to your educational platform's backend operations.

## ✨ Features

- **📊 Analytics Dashboard** - Get real-time insights about your platform's performance
- **🎓 Course Management** - Create, edit, and organize your course catalog
- **👥 Batch Administration** - Manage class batches, schedules, and enrollments
- **📚 Learning Materials** - Upload and manage course materials and resources
- **🎬 Video Content** - Track video engagement and student progress
- **📝 MCQ Management** - Create and manage multiple-choice assessments
- **🔍 Demo Sessions** - Track and manage free session requests
- **🔐 Advanced Security** - Role-based access control with admin permissions
- **📱 Responsive Design** - Full functionality across devices

## 🛠️ Tech Stack

- **Frontend**
  - React 18
  - TypeScript
  - Vite
  - React Router DOM
  - React Query
  - shadcn/ui
  - Tailwind CSS
  - Recharts for data visualization
  - Lucide React icons

- **Backend & Database**
  - Supabase (Authentication, Database, Storage)
  - PostgreSQL with RLS policies
  - Edge Functions

## 🚀 Getting Started

### Prerequisites

- Node.js & npm (or Bun)
- Git

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/masterplan-admin-nexus.git

# Navigate to the project directory
cd masterplan-admin-nexus

# Install dependencies
npm install
# or
bun install

# Start the development server
npm run dev
# or
bun dev
```

### Environment Setup

Create a `.env` file in the root directory with your Supabase credentials:

```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

## 🌐 Deployment

Build the project for production:

```bash
npm run build
```

The build artifacts will be stored in the `dist/` directory.

## 🔒 Security

This admin portal implements several security measures:

- Secure authentication with Supabase Auth
- Admin role verification
- Input validation
- Audit logging for sensitive operations

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

Created by [Pranay Paunikar](https://github.com/pranaypaunikar)

---

<div align="center">
  <p>⚡ Powered by React, TypeScript, and Supabase</p>
</div>
