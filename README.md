# Meta Memory — Rialo Edition

A tiny, fast memory game with the **Rialo** vibe (soft cream + ink black).
Memorize the order, then click cards in the same sequence. Speed + accuracy = score.
Proof over promises, but with pixels.
## Features
- 🧠 Progressive difficulty (sequence grows each round)
- ⚡ Par-time bonus: play fast, score higher
- 💾 Local high score (no backend required)
- 🎨 Minimal UI, Tailwind-ready, brandable palette
- 📦 Single-file React component (drop-in)

## Tech Stack
- React 18 + (optional) Next.js 14
- framer-motion (micro animations)
- Tailwind CSS (styling, optional)

## Quickstart

```bash
# 1) create a Next.js app (or use your existing one)
npx create-next-app memmeta --ts
cd memmeta

# 2) install dependency
npm i framer-motion

# 3) (optional) Tailwind
# https://tailwindcss.com/docs/guides/nextjs

# 4) add the component
# copy RIALO_MetaMemory component into /app/page.tsx (App Router) or /pages/index.tsx
npm run dev
