# HotCheelee — Adult SocialFi & Companion Platform (18+ Kenya)

HotCheelee is an adults-only platform featuring Stripchat-style tip menus, interactive Lovense toy vibrations, 24h stories, 9:16 vertical Quickies reels, Facebook-style groups & marketplace, Messenger, and peer-to-peer predictions & finance in Kenyan Shillings (KSh).

## Architecture
- **Frontend**: Next.js 16 (App Router) + React 19 + Tailwind CSS with Theme Switching (Flame, Facebook Blue, Gittr Gold, Pink).
- **Backend**:
  - Python FastAPI (`python_backend/main.py`) with SQLAlchemy, Pydantic 18+ strict date of birth validation, and automated tests (`pytest`).
  - Next.js App Router API proxy routes providing high-performance server components and caching.
- **Database**: PostgreSQL with Drizzle ORM + SQLAlchemy models.
- **Currency**: Universal Kenyan Shillings (KSh) & HotCheelee Tokens (1 Token = 10 KSh).
- **Billing**: Manual M-Pesa Buy Goods Till: **8923411** (Creators: KSh 500/mo, Agencies: KSh 1,500/mo, 30 days active enforcement).

## Strict 18+ Age Policy & Disclaimer
HotCheelee strictly enforces an 18+ age requirement across registration, profile creation, and monetization. Underage access, child exploitation, grooming, trafficking, and non-consensual imagery are strictly forbidden and subject to instant termination and legal reporting.

## Running Tests
```bash
python3 -m pytest python_backend/test_backend.py -v
```

## Running Python Backend
```bash
python3 -m uvicorn python_backend.main:app --host 0.0.0.0 --port 8000
```
