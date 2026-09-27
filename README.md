# Experience
```
experience/
├── app/                              ← React Router App
│   ├── components/
│   │   ├── avatar/
│   │   ├── banner/
│   │   ├── button/
│   │   ├── card/
│   │   ├── db-card/
│   │   ├── dropdown/
│   │   ├── input/
│   │   ├── label/
│   │   ├── layouts/
│   │   ├── loader/
│   │   ├── menu-bar/
│   │   ├── modal/
│   │   ├── modals/
│   │   ├── orbit-site/
│   │   ├── select/
│   │   ├── slot/
│   │   ├── toggle/
│   │   ├── tooltip/
│   │   └── ChatInput.tsx
│   ├── hooks/
│   ├── lib/
│   ├── providers/
│   ├── routes/
│   │   ├── auth/                     ← Route authentication
│   │   ├── channel.tsx               ← Channel/chat Page
│   │   └── overview.tsx              ← Overview Page
│   ├── types/
│   ├── utils/
│   ├── app.css
│   ├── entry.server.tsx
│   ├── root.tsx
│   └── routes.ts
│
├── build/                            ← Output build (client + server)
├── public/
│   ├── assets/
│   └── favicon.ico
├── workers/
│   └── app.ts                        ← Entry Cloudflare Worker
│
├── Dockerfile
├── package.json
├── package-lock.json
├── react-router.config.ts
├── tsconfig.json
├── tsconfig.cloudflare.json
├── tsconfig.node.json
├── vite.config.ts
├── worker-configuration.d.ts
└── wrangler.json
```
