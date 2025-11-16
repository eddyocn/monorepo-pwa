📱 PWA + API + Testes + Docker + CI/CD — Monorepo

Este projeto é um PWA completo, integrado com uma API Node.js, organizado em monorepo, containerizado com Docker, testado com Playwright, e utilizando CI/CD com GitHub Actions para build, testes e deploy automático no GitHub Pages.

Projeto desenvolvido para avaliação do módulo de Progressive Web Apps.

📁 Estrutura do Projeto monorepo-pwa/ ├── apps/ │ ├── web/ → PWA feito com Vite │ └── api/ → API Node.js com Express ├── docker-compose.yml └── .github/workflows/ci.yml

🚀 Tecnologias Utilizadas

⚡ Vite (frontend)

📱 PWA com Service Worker + Manifest

🔌 Node.js + Express (API)

🐳 Docker e Docker Compose

🎭 Playwright (testes E2E)

🔄 GitHub Actions (CI/CD completo)

🌐 GitHub Pages (deploy automático)

🐳 Como Rodar com Docker docker compose up --build

Serviços rodando:

🌐 Web (PWA): http://localhost:8080

🔌 API: http://localhost:3000

🧪 Testes E2E (Playwright)

Para rodar os testes manualmente:

cd apps/web npx playwright test

Os testes verificam: ✔ Carregamento do PWA ✔ Título da página contendo "Bootcamp"

🔄 CI/CD — GitHub Actions

O pipeline executa automaticamente ao fazer push no branch main:

Instala dependências do Web e API

Instala os browsers do Playwright

Sobe o servidor de desenvolvimento

Executa os testes E2E

Gera o build do PWA

Publica no GitHub Pages

Salva artefatos para avaliação

🔗 Links da Entrega (Requisitos do Trabalho) 📦 Repositório Monorepo

👉 https://github.com/eddyocn/monorepo-pwa

🌐 PWA publicado (GitHub Pages)
<img width="1863" height="971" alt="Captura de tela 2025-11-16 200342" src="https://github.com/user-attachments/assets/be5169b6-5362-4322-9e2d-6713849282ba" />
👉 https://eddyocn.github.io/monorepo-pwa

🔄 Última Execução do CI (build + testes + deploy)

👉 https://github.com/eddyocn/monorepo-pwa/actions/runs/19413318999

📁 Artefatos gerados pelo CI

✔ github-pages.zip — build final publicado

✔ playwright-report/ — relatório dos testes E2E

✔ Build final: apps/web/dist

Sugestão: grave instalando o PWA pelo navegador e utilizando o fluxo principal.

👨‍💻 Autor

Eduardo Cabral Nunes
