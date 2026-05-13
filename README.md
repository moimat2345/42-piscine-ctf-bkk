# 42 Piscine CTF — Bangkok edition 🌴

A mini-hackathon CTF platform built for the **42 Bangkok piscine**.
Coalition vs coalition, ~90 minutes of flag hunting, 200+ challenges
across 5 difficulty tiers (beginner → impossible).

**Live**: https://mini-hackaton-delta.vercel.app

> The actual source code lives in a private repo. This public repo exists so contest participants can find the easter-egg flag they're looking for.

## 👋 Who built this

Built by **matnusko** for the 42 Bangkok piscine of May 2026.

## 🎁 Easter egg

If you found your way here via the footer of the CTF site, you're already thinking like a real CTFer. Real ones always check who built the thing they're playing on, and read what's there.

Here's your reward — submit it on `/challenges` for the **`who_built_this`** challenge:

```
flag{forked_from_the_source}
```

_(Beginner-tier challenge — every member of your coalition can submit it independently for 25 pts each.)_

## Stack (high-level)

- Next.js 15 (App Router) + React 19
- Prisma + Neon Postgres
- NextAuth v5 with custom 42 OAuth provider + invite-token Credentials provider
- Tailwind v4 + custom CTF aesthetic (mono, scanlines, phosphor green, coalition colors)
- Deployed on Vercel

## Credits

Designed and shipped by matnusko, with assistance from Claude (Anthropic) for code generation and challenge content.
