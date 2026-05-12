# AI City Digital Twin (City Twin)

A Next.js (App Router) web app scaffold for building an interactive city “digital twin” experience: 3D visualization + UI dashboards (work in progress).

## What’s in this repo

- `city-twin/` — the Next.js app
- `vercel.json` — Vercel config that deploys the `city-twin/` app from the repo root

## Tech stack

- Next.js 14 + React 18 + TypeScript
- Tailwind CSS
- Three.js via React Three Fiber / Drei (+ postprocessing)
- Recharts (charts), Framer Motion (animations), Lucide (icons)

## Local development

```bash
cd city-twin
npm ci
npm run dev
```

Then open `http://localhost:3000`.

## Useful scripts

```bash
cd city-twin
npm run lint
npm run build
npm run start
```

## Deployment

This repo is set up to deploy on Vercel from the repository root using `vercel.json`, with the build rooted in `city-twin/`.

