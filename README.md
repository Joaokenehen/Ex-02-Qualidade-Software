# Frontend Catalog - Atividade Prática de Qualidade de Software

Projeto de catálogo de produtos arquitetado visando acessibilidade (a11y), responsividade (mobile-first), performance e qualidade de código com testes automatizados.

## 🚀 Tecnologias Utilizadas
- **React + Vite** (Single Page Application)
- **Vitest + React Testing Library** (Testes Unitários e de Integração)
- **Playwright** (Testes End-to-End)
- **Storybook** (Documentação de Componentes)
- **axe-core** (Auditoria de Acessibilidade)

## 📦 Como rodar o projeto

**1. Instale as dependências:**
```bash
npm install
```

**2. Inicie o servidor de desenvolvimento:**
```bash
npm run dev
```
*(Acesse http://localhost:5173 no seu navegador)*

## 🧪 Como rodar os testes

**Testes Unitários e de Integração (Vitest):**
```bash
npm run test
```

**Testes End-to-End (Playwright):**
```bash
# Com a aplicação rodando (npm run dev) em uma aba, execute em outra:
npx playwright test
```

**Documentação Visual (Storybook):**
```bash
npm run storybook
```

## 📄 Documentações Adicionais
- Decisões de Arquitetura: [ARCHITECTURE.md](./frontend-catalog//ARCHITECTURE.md)
- Relatório de Performance: [PERFORMANCE.md](./frontend-catalog//PERFORMANCE.md)
