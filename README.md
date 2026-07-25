# Nio Storybook

A component development playground built with **Next.js**, **TypeScript**, and **Tailwind CSS**, using **Storybook** to build and document UI components in isolation.

## What this is

A practice project focused on **component-driven development**: building reusable UI components with clear props/types, then documenting and previewing each one independently in Storybook (instead of only seeing them inside a full page).

## Tech Stack

- **Next.js 15** (React 19, App Router)
- **TypeScript**
- **Tailwind CSS**
- **Storybook 8**

## Featured Component: `Card`

A reusable card component supporting:
- **Light / Dark variants**
- Image, title, and label props
- Composable with other components (uses a shared `Button` component)

```tsx
<Card
  variant="light"
  image="https://placehold.co/600x400"
  title="Light Theme"
  label="Lorem ipsum dolor sit amet, consectetur adipiscing elit."
/>
```

Organized following **Atomic Design** naming conventions (`Molecule/Card`) to keep the component library structured as it grows.

## Getting Started

```bash
npm install

# Run the Next.js app
npm run dev

# Run Storybook (component explorer)
npm run storybook
```

- App: [http://localhost:3000](http://localhost:3000)
- Storybook: [http://localhost:6006](http://localhost:6006)

## What I practiced here

- Building typed, reusable React components with TypeScript
- Styling with Tailwind CSS
- Documenting components with Storybook stories and controls
- Structuring a component library using Atomic Design principles
