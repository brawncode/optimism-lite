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
### 🛠️ System Monitor — 2026-01-30

- `[2026-01-30 18:43:42 UTC] Task #394 COMPLETED — uptime=99.001% — latency=195ms`
- `[2026-01-30 17:56:20 UTC] Task #317 COMPLETED — uptime=99.039% — latency=107ms`
- `[2026-01-30 17:19:44 UTC] Task #544 COMPLETED — uptime=99.023% — latency=182ms`
- `[2026-01-30 16:40:00 UTC] Task #804 COMPLETED — uptime=99.068% — latency=71ms`
- `[2026-01-30 15:55:57 UTC] Task #959 COMPLETED — uptime=99.004% — latency=189ms`

