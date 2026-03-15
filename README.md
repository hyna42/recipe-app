# Nuxtcipes

A modern recipe app built with Nuxt 4, Vue 3, and TypeScript. Browse recipes, view details, and get cooking instructions.

## Features

- Browse recipe collection with card layouts
- View detailed recipes (ingredients, instructions, cook time, calories, ratings)
- Responsive design with Tailwind CSS
- SEO optimized with server-side rendering
- TypeScript support for type safety

## Tech Stack

Nuxt 4, Vue 3, TypeScript, Tailwind CSS, Nuxt Icon, Nuxt Image, Google Fonts

## Project Structure

```
recipe-app/
├── app/
│   ├── components/     # Reusable components
│   ├── layouts/        # Page layouts
│   ├── pages/          # Application pages
│   └── types/          # TypeScript definitions
├── public/             # Static assets
├── server/             # Server-side code
├── nuxt.config.ts      # Nuxt configuration
├── package.json        # Dependencies and scripts
├── tailwind.config.ts  # Tailwind configuration
└── tsconfig.json       # TypeScript configuration
```

## Installation

```bash
git clone <repository-url>
cd recipe-app
npm install
```

## Development

Start development server:

```bash
npm run dev
```

Build for production:

```bash
npm run build
npm run preview
```

## API

Uses [DummyJSON Recipes API](https://dummyjson.com/docs/recipes) for recipe data.
