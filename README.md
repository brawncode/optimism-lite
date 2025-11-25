# Optimism Lite

> mini-hub for the **Superchain Eco** — education-first, Optimism-aligned guides, badge walkthroughs, and low-friction actions (daily check-in, onchain routines)

[![Deploy](https://therealsujitk-vercel-badge.vercel.app/?app=base-lite)](https://oplite.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](#license)

## What is it?

**Base Lite** is a tiny, fast web app that helps newcomers and builders:
- Understand the **Base** ecosystem with short, practical guides.
- Earn/track **badges** (with a clear “how/why/risks” section per badge).
- Keep a steady onchain cadence (planned: **Daily Check-in**).
- Nudge organic participation (governance, quests, social identity).
- (Planned) micro-rewards in **$wenaltszn** for streaks/ships.

It mirrors Celo Lite’s minimal UI/structure, adapted to **Base**:
- Transparent header, system **Light/Dark/Auto** theme.
- JS-only, no heavy CSS frameworks.
- Farcaster mini-app compatibility kept (meta + manifest).
- Clean separation for a future **Badges** section with per-badge guides.

## Live

- App: **https://optilite.vercel.app/**
- Discord (Base): **https://discord.gg/buildonbase**  
- X (Base): **https://x.com/base**

## Screens

<img src="./public/baseog.png" alt="Base Lite OG" width="720"/>

## Tech Stack

- **Next.js 14.2.32** — React framework for the frontend
- **React 18.3.1**
- **Wagmi 2.12.14** — Ethereum hooks for wallet connection
- **Viem 2.37.9** — fast and modern EVM client
- **@reown/appkit 1.7.18** — WalletConnect AppKit (Reown)
- **@reown/appkit-adapter-wagmi 1.7.18** — AppKit ↔ Wagmi integration
- **@tanstack/react-query 5.56.2** — query management and cache

### WalletConnect / Reown
The app integrates **Reown AppKit** for connection via WalletConnect, with `WagmiAdapter` for full compatibility with Wagmi & Viem.

### Deployment
- Node.js 20.x
- Hosted on **Vercel**

## Features

- ✅ Transparent header & Base-blue theme
- ✅ Reown AppKit integration
- ✅ Light/Dark/**Auto** theme toggle (remembered)
- ✅ Minimal wallet connect stub (AppKit slot ready)
- ✅ Footer shortcuts (Discord/X/Guild Base)
- ✅ **Daily Check-in** (one free, gas-sponsored action/day if possible)
- ✅ **Badges** section with compact guides (Base-aligned copy)
- ✅ **Creator/Builder Score** helper (Talent Protocol)
- ✅ Optional rewards in **$wenaltszn** for streaks/ships

## Local dev

```bash
npm i
npm run dev
# open http://localhost:3000
### 🛠️ System Monitor — 2025-11-25

- `[2025-11-25 07:02:13 UTC] Task #254 COMPLETED — uptime=99.055% — latency=73ms`
- `[2025-11-25 06:34:18 UTC] Task #508 COMPLETED — uptime=99.083% — latency=141ms`
- `[2025-11-25 05:55:37 UTC] Task #117 COMPLETED — uptime=99.052% — latency=96ms`
- `[2025-11-25 05:43:23 UTC] Task #554 COMPLETED — uptime=99.044% — latency=172ms`
- `[2025-11-25 05:20:04 UTC] Task #463 COMPLETED — uptime=99.062% — latency=43ms`

