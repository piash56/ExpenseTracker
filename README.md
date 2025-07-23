# Expense Tracker

![Logo](public/placeholder-logo.svg)

## Overview

**Expense Tracker** is a modern web application to help you manage and visualize your daily expenses. Track your spending, categorize transactions, and gain insights into your financial habits with a beautiful, responsive UI.

## Features

- Add, view, and delete expenses
- Categorize expenses (Food, Transport, Shopping, Bills, Entertainment, etc.)
- Visualize expense distribution by category
- Responsive design with glassmorphism and dark mode support
- Search and filter expenses
- Built with modern React, Next.js, and Tailwind CSS

## Tech Stack

- [Next.js 15](https://nextjs.org/) (App Router, TypeScript)
- [React 19](https://react.dev/)
- [Tailwind CSS](https://tailwindcss.com/) & [tailwindcss-animate](https://github.com/joe-bell/tailwindcss-animate)
- [Radix UI](https://www.radix-ui.com/) components
- [Lucide Icons](https://lucide.dev/)
- [Zod](https://zod.dev/) for validation
- [React Hook Form](https://react-hook-form.com/)
- [date-fns](https://date-fns.org/) for date utilities

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18 or higher recommended)
- [pnpm](https://pnpm.io/) (or npm/yarn)

### Installation

1. **Clone the repository:**
   ```bash
   git clone <your-repo-url>
   cd expense-tracker
   ```
2. **Install dependencies:**
   ```bash
   pnpm install
   # or
   npm install
   # or
   yarn install
   ```
3. **Run the development server:**
   ```bash
   pnpm dev
   # or
   npm run dev
   # or
   yarn dev
   ```
4. Open [http://localhost:3000](http://localhost:3000) in your browser.

### Build for Production

```bash
pnpm build && pnpm start
# or
npm run build && npm start
# or
yarn build && yarn start
```

## Project Structure

- `app/` - Next.js app directory (routing, layout, global styles)
- `components/` - Reusable UI components
- `hooks/` - Custom React hooks
- `lib/` - Utility functions
- `public/` - Static assets (logo, images)
- `styles/` - Additional global styles

## Customization

- **Theming:** Uses [next-themes](https://github.com/pacocoursey/next-themes) for dark/light mode.
- **Styling:** Tailwind CSS with custom glassmorphism effects.
- **Icons:** Easily swap or add icons using [Lucide React](https://lucide.dev/).

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License.

---

_Your Daily Life Expense Store_
