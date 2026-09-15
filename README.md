# Skip + Codex · Workspace Experimental

Workspace para experimentar a construção de aplicações Skip com assistência do Codex.

## Objetivo

O repositório serve como laboratório técnico para validar uma stack moderna de frontend, integração com PocketBase/Skip Cloud e fluxos de desenvolvimento assistido por IA.

## Stack

`React 19` · `TypeScript` · `Vite` · `Tailwind CSS` · `shadcn/ui` · `PocketBase`

## Executar localmente

```bash
pnpm install
cp .env.example .env
pnpm dev
```

Configure `VITE_POCKETBASE_URL` para uma instância própria.

## Comandos

```bash
pnpm dev
pnpm build
pnpm lint
pnpm format
pnpm preview
```

## Estrutura

```text
src/             aplicação React
public/          arquivos públicos
pocketbase/      backend e migrações
.env.example     contrato de configuração
```

## Status

Laboratório/experimento. O código pode mudar rapidamente e não deve ser tratado como produto de produção sem revisão de segurança, dados e regras de acesso.
