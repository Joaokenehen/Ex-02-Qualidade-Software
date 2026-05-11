# Frontend Catalog - Atividade Prática de Qualidade de Software

Este é um projeto de catálogo de produtos desenvolvido como uma atividade prática, com foco em arquitetura deliberada, acessibilidade (a11y), responsividade (mobile-first), performance e qualidade de código através de testes automatizados.

## 🚀 Tecnologias Utilizadas

- **React + Vite** (Single Page Application)
- **Vitest + React Testing Library** (Testes Unitários e de Integração)
- **Playwright** (Testes End-to-End)
- **Storybook** (Documentação de Componentes)
- **axe-core** (Auditoria de Acessibilidade)
- **ESLint + Prettier** (Qualidade e Padronização de Código)

## 📦 Primeiros Passos

### Pré-requisitos

- Node.js (versão 18.x ou superior)
- npm ou pnpm

### Instalação

1. Clone o repositório e navegue até o diretório:
```bash
git clone <URL_DO_REPOSITORIO>
cd frontend-catalog
```

2. Instale as dependências:
\`\`\`bash
npm install
\`\`\`

## ⚙️ Scripts Disponíveis

**Iniciar o servidor de desenvolvimento:**
\`\`\`bash
npm run dev
\`\`\`
A aplicação estará disponível em `http://localhost:5173`.

**Rodar os testes unitários e de integração:**
\`\`\`bash
npm run test
\`\`\`

**Rodar os testes End-to-End (E2E):**
\`\`\`bash
# Certifique-se que a aplicação está rodando (npm run dev) em um terminal,
# e então execute o seguinte comando em outro:
npx playwright test
\`\`\`

**Visualizar a documentação de componentes no Storybook:**
\`\`\`bash
npm run storybook
\`\`\`

**Gerar a build de produção:**
```bash
npm run build
```

## 📄 Documentação do Projeto

- **Decisões de Arquitetura**: Detalha a escolha da arquitetura SPA, os motivos técnicos e os trade-offs considerados.
- **Relatório de Performance**: Apresenta as otimizações de performance aplicadas e os resultados obtidos no Lighthouse.

