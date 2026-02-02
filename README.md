# Golden Loaf Bakery Website

A modern, responsive website for Golden Loaf Bakery built with Next.js 14. This website showcases the bakery's menu, gallery, team, and contact information.

## Features

- 🍞 **Home Page** - Hero section with featured items and customer testimonials
- 📖 **About Page** - Story of the bakery, team members, and values
- 🍰 **Menu Page** - Display of bakery items and offerings
- 📸 **Gallery** - Photo gallery showcasing bakery products
- 📧 **Contact Page** - Contact information and form

## Tech Stack

- **Framework**: Next.js 14.2.6
- **Language**: TypeScript
- **Styling**: CSS Modules
- **Icons**: React Icons
- **Image Optimization**: Next.js Image component with Sharp

## Getting Started

### Prerequisites

- Node.js 18+ installed
- npm, yarn, pnpm, or bun

### Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/golden-loaf.git
cd golden-loaf
```

2. Install dependencies:
```bash
npm install
# or
yarn install
# or
pnpm install
```

3. Run the development server:
```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## Project Structure

```
golden-loaf/
├── public/
│   └── images/          # Image assets
├── src/
│   └── app/
│       ├── about/       # About page
│       ├── contact/     # Contact page
│       ├── gallery/     # Gallery page
│       ├── menu/        # Menu page
│       ├── layout.tsx   # Root layout
│       ├── page.tsx     # Home page
│       └── globals.css  # Global styles
├── package.json
└── README.md
```

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
