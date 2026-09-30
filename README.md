<h1 align="center">Diego Bourguignon Rangel</h1>

<p align="center">
  <b>Software Developer</b>
</p>

<p align="center">
  Desenvolvedor de software com experiência em desenvolvimento web, automação de testes e qualidade de software.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/diegobrangel/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  &nbsp;
  <img src="https://komarev.com/ghpvc/?username=diegobrangel&style=for-the-badge&color=6366f1&label=VISITAS" alt="Visitas ao perfil"/>
</p>

---

## Sobre mim

Desenvolvedor de software com experiência em desenvolvimento web e qualidade de software, atuando principalmente com TypeScript, PHP, Python e automação de testes.

No dia a dia, trabalho na construção e evolução de sistemas, criação de testes automatizados e integração de qualidade ao fluxo de desenvolvimento.

Gosto de entender o problema antes de escrever código, buscar soluções simples de manter e construir software que realmente funcione em produção.

---

## Atualmente

🧩 Desenvolvimento de aplicações web  
🧪 Automação de testes e E2E  
⚙️ CI/CD e qualidade de software  
📚 Bacharelado em Sistemas de Informação  

---

## Tecnologias

**Linguagens**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Slim](https://img.shields.io/badge/Slim_Framework-74A045?style=for-the-badge&logo=php&logoColor=white)

**Testes**

![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![PHPUnit](https://img.shields.io/badge/PHPUnit-366488?style=for-the-badge&logo=php&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=for-the-badge&logo=selenium&logoColor=white)

**Dados & Infraestrutura**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Firebird](https://img.shields.io/badge/Firebird_SQL-F0A500?style=for-the-badge&logo=databricks&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitLab CI](https://img.shields.io/badge/GitLab_CI/CD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)

---

## 🚀 Projetos em destaque

### Athenas Online — Software de gestão contábil e fiscal

> Repositório privado · GitLab · Em produção · Projeto profissional

Sistema multi-tenant onde atuo como desenvolvedor. O sistema cobre gestão fiscal e operacional — da emissão de documentos fiscais (NF-e, CT-e, MDF-e) ao controle financeiro e de projetos — com múltiplos clientes isolados em um único ambiente.

**O que o sistema resolve:**
- Emissão e gerenciamento de NF-e, CT-e e MDF-e com integração direta à SEFAZ
- API REST com autenticação JWT e OAuth2 (Microsoft e Google)
- Filas de processamento assíncrono com Redis e workers dedicados
- Pipeline de CI/CD automatizado no GitLab com cobertura de testes e análise estática
- Geração de relatórios e documentos PDF
- Integração com Microsoft Graph (e-mail, calendário) e AWS S3

**Stack principal:** PHP 8 · Slim Framework · CakePHP · Firebird · Redis · Docker · GitLab CI/CD · PHPUnit · PHPStan

---

### Perfila — Sistema de gestão para fábrica de esquadrias de alumínio

> Repositório privado · Em produção

Sistema web desenvolvido para gerenciar o ciclo completo de uma fábrica de esquadrias de alumínio: do pedido de venda até a entrega na obra. Cobre produção, expedição, roteirização de entregas e acompanhamento por motoristas.

**O que o sistema resolve:**
- Controle de ordens de produção com algoritmo de corte por barra (otimização de aproveitamento de material)
- Planejamento e montagem de cargas com regras de ocupação mínima e restrições por faixa
- Roteirização de entregas com geocodificação automática via Nominatim e visualização em mapa (MapLibre GL)
- Rastreamento do status de cada entrega em tempo real
- Impressão de etiquetas e romaneios em PDF
- Controle de estoque e importação de pedidos via planilha
- RBAC completo: administrador, expedição, motorista, representante

**Stack principal:** Next.js · React · TypeScript · PostgreSQL · Prisma · Tailwind CSS · Docker · GitHub Actions

**Qualidade:** suíte de testes E2E com Playwright cobrindo os fluxos críticos (autenticação, cadastros, importação, algoritmos, carregamento e rotas), testes unitários com Vitest e CI/CD automatizado com deploy incremental.

---

### Gravity — Jogo mobile publicado na Play Store

> Dart · Flutter · [Ver na Play Store](https://play.google.com/store/apps/details?id=com.gravidade.app)

Runner infinito 2D com background parallax em que o personagem alterna o centro gravitacional para desviar de obstáculos que surgem tanto do chão quanto do teto. Desenvolvido do zero e publicado de forma independente na Google Play Store.

**Stack:** Dart · Flutter

---

## Contribuições

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/diegobrangel/diegobrangel/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/diegobrangel/diegobrangel/output/github-contribution-grid-snake.svg">
  <img alt="snake animation eating github contribution graph" src="https://raw.githubusercontent.com/diegobrangel/diegobrangel/output/github-contribution-grid-snake.svg">
</picture>
