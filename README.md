# MyTacTeam

SaaS hybride PWA pour staff, joueurs et analystes — gestion tactique, entraînements, matchs et statistiques.

Stack (MVP):
- Frontend: React + TypeScript + Vite + TailwindCSS + PWA
- Backend: NestJS (Node.js) + Prisma
- Database: PostgreSQL (via Supabase for MVP)
- Realtime: WebSockets + Redis
- Auth & Storage: Supabase (auth, storage)
- CI/CD: GitHub + Vercel (frontend) + Supabase/AWS for backend

MVP features:
- Espace staff / joueur
- Tableau de bord individuel et équipe
- Profil joueur avec stats
- Outil tactique (terrain interactif drag & drop)
- Gestion tâches & planning
- Rapports de match

Getting started (local):
1. Clone the repo
2. Copy .env.example to .env and fill variables (SUPABASE_URL, DATABASE_URL, etc.)
3. Install frontend dependencies and run:
   cd frontend && npm install && npm run dev
4. Install backend dependencies and run:
   cd backend && npm install && npm run start:dev

Roadmap:
- Integrations IA pour analyses et recommandations
- Application mobile native
- Migration infra complète vers AWS si nécessaire