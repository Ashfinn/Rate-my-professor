# Rate-My-Professor

A modern web application that helps students discover, rate, and review professors to make informed decisions about their education.

![Rate-My-Professor](https://img.shields.io/badge/Version-1.0.0-purple) ![Next.js](https://img.shields.io/badge/Next.js-14.0.0-black) ![React](https://img.shields.io/badge/React-18.0.0-blue) ![TypeScript](https://img.shields.io/badge/TypeScript-5.0.0-blue)

## ✨ Features

- **Professor Ratings & Reviews**: Share experiences and read feedback from other students
- **Intelligent Search**: Find professors by name, department, or course
- **Chatbot Assistant**: Get instant help navigating the platform
- **Responsive Design**: Seamless experience across desktop and mobile devices
- **FAQ Section**: Quick answers to common questions
- **Dark/Light Mode**: Customizable viewing experience

## 🛠️ Technologies Used

- **Framework**: Next.js 14 with App Router
- **Language**: TypeScript
- **Styling**: Tailwind CSS with DaisyUI components
- **UI Components**: Material-UI
- **Deployment**: Vercel (recommended)

## 🚀 Getting Started

### Prerequisites

- Node.js 18.x or later
- npm, yarn, or pnpm package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/rate-my-professor.git
   cd rate-my-professor
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to view the application

## 📁 Project Structure

```
rate-my-professor/
├── app/
│   ├── api/                 # API routes
│   ├── components/          # Reusable React components
│   ├── styles/             # Global styles
│   ├── layout.tsx          # Root layout component
│   └── page.tsx            # Home page
├── public/
│   ├── hero-bg.jpg         # Hero section background
│   └── favicon.ico         # Website favicon
├── tailwind.config.js      # Tailwind configuration
├── tsconfig.json           # TypeScript configuration
└── package.json            # Project dependencies
```

## 🎨 Customization

### Theme Colors

Modify the `tailwind.config.js` file to customize the color scheme:

```js
daisyui: {
  themes: [
    {
      mytheme: {
        primary: '#6A1B9A',    // Main purple color
        secondary: '#FFFFFF',  // White
        accent: '#6A1B9A',     // Accent purple
        neutral: '#3D4451',    // Text color
        'base-100': '#FFFFFF', // Background color
      },
    },
  ],
},
```

### Adding New Components

1. Create new components in the `app/components/` directory
2. Import and use them in the appropriate pages
3. Style using Tailwind CSS classes or custom CSS

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the project
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines

- Follow TypeScript best practices
- Ensure responsive design works on all screen sizes
- Test changes thoroughly before submitting
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Credits

- **Ashfinn** - Designed and developed the frontend
- **0xfatima** - Created the chatbot assistant functionality

---

⭐ Star us on GitHub if you find this project helpful!
