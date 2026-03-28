# Emily Summer Trip Dashboard

## Overview
Interactive travel dashboard for Emily's 22-day European summer trip (Jun 3-25, 2026). Password-protected, hosted on GitHub Pages. Midnight Aurora dark theme matching the Melissa summer-trip dashboard style.

## Repository
- **Path**: `/Users/aaxis/Documents/GitHub/emily-summer`
- **Remote**: `https://github.com/djctwo/emily-summer` (public, branch: main)
- **Live URL**: `https://djctwo.github.io/emily-summer/`
- **Password**: SHA-256 hashed (`emilysummer123!@#`), sessionStorage persistence
- **Launcher**: `~/Applications/Dashboards/Emily Summer.app`

## Traveler
- **Emily Elizabeth Cleary**, 15 years old, from Las Vegas
- **Dad (Doug)** lives in Kaiserslautern, Germany — works weekdays, free weekends
- **Interests**: museums, shopping, beach, city, food tours, adventure, riding trains

## Trip Structure
- **Jun 3**: Travel LAS→BOS→FRA (JetBlue B6478 + Condor DE2039, booking 15635316-02)
- **Jun 4-5**: Arrival & KL settling in
- **Jun 6-7**: Weekend 1 — Paris by TGV (suggested)
- **Jun 8-13**: Explorer week (KL solo activities + Rhine Valley day trip Sat)
- **Jun 14-18**: Athens, Greece (SKY express, confirmation FX4K8A, Acropolis Muses apartment booking 5392664665)
- **Jun 19**: Recovery day
- **Jun 20-22**: Düsseldorf (Japantown, Spanish restaurants, sightseeing; Bad Bunny concert Sun night NOT shown)
- **Jun 23-24**: Final KL days
- **Jun 25**: Departure FRA→LAS direct (Condor DE2062, seat 20A)

## Dashboard Structure
- **File**: `index.html` — single-file HTML, ~1600 lines
- **Theme**: Midnight Aurora (blue/purple/cyan gradients, frosted glass panels, backdrop blur) — matches summer-trip dashboard
- **Tabs**: Itinerary, Athens, Düsseldorf, Weekend Trips, KL Solo Guide, Travel Info
- **Stats row**: 22 Days / 3 Countries / 6 Flights / 4 Cities / 1 Island Cruise
- **Map**: Leaflet.js with dark tiles, markers for all destinations + day trip ideas
- **Countdown timer**: Days until Jun 3 departure

## Key Design Decisions
- No prices shown anywhere (user requirement)
- Bad Bunny concert (Jun 21 Sun night in Düsseldorf) NOT mentioned (Emily not attending)
- Solo weekdays: KL-only activities (no solo day trips outside KL — she's 15)
- Athens tab: 20 Wikimedia Commons images + Google Images links on all 27 attraction names
- Weekend Trips tab: 10 train-accessible destinations from KL (Paris, Amsterdam, Heidelberg, Cologne, Strasbourg, Rhine Valley, Luxembourg, Bruges, Black Forest, Swiss Alps)
- Password gate: SHA-256 via Web Crypto API, sessionStorage persistence

## Conventions
- Update CLAUDE.md and Session_History continuously throughout sessions
- All session notes in `Session_History/`
- No prices in any content
