# Optimism Lite

> mini-hub for the **Superchain Eco** — education-first, Optimism-aligned guides, badge walkthroughs, and low-friction actions (daily check-in, onchain routines)

[![Deploy](https://therealsujitk-vercel-badge.vercel.app/?app=base-lite)](https://oplite.vercel.app/)
[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](#license)

## What is it?

**Base Lite** is a tiny, fast web app that helps newcomers and builders:
- Understand the **Optimism** ecosystem with short, practical guides.
- Earn/track **badges** (with a clear “how/why/risks” section per badge).
- Keep a steady onchain cadence (planned: **Daily Check-in**).
- Nudge organic participation (governance, quests, social identity).
- (Planned) micro-rewards in **$wenaltszn** for streaks/ships.

## Live

- App: **https://optilite.vercel.app/**
- Discord (Base): **https://discord.gg/optimism**  
- X (Base): **https://x.com/optimism**

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
### 🛠️ System Monitor — 2025-12-02

- `[2025-12-02 21:49:49 UTC] Task #555 COMPLETED — uptime=99.089% — latency=80ms`
- `[2025-12-02 21:36:00 UTC] Task #894 COMPLETED — uptime=99.030% — latency=70ms`
- `[2025-12-02 21:22:56 UTC] Task #219 COMPLETED — uptime=99.075% — latency=92ms`
- `[2025-12-02 20:55:18 UTC] Task #219 COMPLETED — uptime=99.066% — latency=89ms`
- `[2025-12-02 20:25:09 UTC] Task #745 COMPLETED — uptime=99.074% — latency=113ms`

