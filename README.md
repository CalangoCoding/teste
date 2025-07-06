# Plataforma de Estudos & Redação – ENEM, Fuvest, Unicamp

## Monorepo – Estrutura

```
apps/
  web/    # Frontend Next.js 14+
  api/    # Backend NestJS
packages/
  ui/     # Componentes compartilhados (shadcn/ui, Tailwind)
  config/ # Configurações compartilhadas
  eslint-config/ # Configuração de lint
```

## Instalação Rápida

```sh
git clone <repo-url>
cd <repo>
npm install
cp .env.example .env
npm run dev
```

- Acesse: http://localhost:3000
- O comando `npm run dev` sobe frontend, backend e banco de dados (Docker Compose) e abre o Chrome automaticamente.

## Principais Comandos

- `npm run dev` – Dev FE+BE+DB
- `npm run lint` – Lint + Prettier
- `npm run test` – Testes unitários e integração
- `npm run test:e2e` – Testes E2E (Playwright)
- `npm run migrate` – Migrações Prisma

## Documentação
- OpenAPI: http://localhost:3333/docs
- Figma: [Protótipos](#)

## Estrutura de Pastas
- apps/web: Next.js frontend
- apps/api: NestJS backend
- packages/ui: Componentes compartilhados
- packages/config: Configs compartilhadas
- packages/eslint-config: Lint compartilhado

## Stack
- Next.js 14+, TypeScript, TailwindCSS, shadcn/ui, lucide-react
- NestJS, Prisma, PostgreSQL, BullMQ, Redis
- Docker, GitHub Actions, Playwright, Jest, Supertest

---

> Para detalhes completos, consulte a documentação em `docs/`. 