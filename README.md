<h1 align="left">Olá, me chamo João Vitor Küster 👋</h1>

### Dados · Engenharia de Dados · Desenvolvimento Full Stack · Itajaí, SC

- 📊 Trabalho com dados e engenharia de dados: extração automatizada, integração de APIs, bancos de dados e BI
- 💻 Hoje também desenvolvo aplicações web completas para visualização de dados, do banco ao front-end
- 🎓 Estudante de Engenharia de Software na UniCesumar
- 🤖 Uso IA no dia a dia de desenvolvimento, com agentes no Claude Code

## 🛠️ Ferramentas

**Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-663399?style=for-the-badge&logo=css&logoColor=white)

**Back-end e dados**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Alembic](https://img.shields.io/badge/Alembic-6BA81E?style=for-the-badge)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=for-the-badge&logo=playwright&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

**Front-end**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

**Qualidade e DevOps**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)

**BI, design e IA**

![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Fabric](https://img.shields.io/badge/Microsoft_Fabric-0F7C6C?style=for-the-badge)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white)

## 🚧 Projetos em desenvolvimento

> Projetos profissionais em repositórios privados. Aqui estão só o que cada um faz, as tecnologias e em que fase está.

### 📈 Plataforma web de visualização de dados
`🟡 Em desenvolvimento` · FastAPI · SQLAlchemy · Alembic · PostgreSQL · React · TypeScript · Vite · Tailwind CSS · GitHub Actions

Sistema web interno que reúne os dashboards da operação num só lugar, com controle de quem acessa cada um. Monólito modular, com back-end em camadas (domínio, casos de uso, infraestrutura e API).

- ✅ **Pronto:** login com sessão segura, bloqueio após tentativas erradas e recuperação de senha por e-mail; gestão de usuários e de acesso por workspace; log de acessos; tema claro e escuro; interface bilíngue (i18n)
- ✅ **Qualidade:** CI no GitHub Actions com lint (Ruff e ESLint), checagem de tipos (mypy e TypeScript) e testes automatizados (pytest e Vitest); design system criado no Figma
- 🔜 **Próximas etapas:** pipeline de dados para o banco analítico, API de métricas com filtros e os primeiros dashboards de acompanhamento de pedidos, num roadmap de 8 sprints

### 🤖 Automação de extração de dados (web scraping)
`🟢 Funcional` · Python · Playwright · PostgreSQL · Docker · pytest

Extrai dados de um sistema web que não tem API para consulta em massa. Faz login uma única vez, percorre as telas em três etapas encadeadas e grava tudo direto no PostgreSQL.

- Consulta em janelas de período e lê todas as páginas da grade
- Tentativas automáticas, com novo login se a sessão cair, sem derrubar a fila inteira
- Gravação idempotente (upsert): roda quantas vezes precisar sem duplicar dados
- Integração com a API do Lark Base, com autenticação OAuth

### 🗄️ Versionamento do banco de dados
`🔄 Contínuo` · PostgreSQL · SQL · Git

Toda a estrutura do banco em código: tabelas, views, procedures, functions, triggers, migrações e permissões de acesso. Cada mudança tem histórico e revisão no Git, os scripts podem ser reexecutados com segurança e tudo é testado em homologação antes de ir para produção.

## 📂 Projetos públicos

| Projeto | O que faz | Ferramentas |
|---|---|---|
| [Pipeline de dados (ETL)](https://github.com/Kusterjv/Pipeline_dados_curso_alura) | Unifica os dados de duas empresas após uma fusão: extrai arquivos JSON e CSV, trata e carrega tudo numa base única | Python, Jupyter, WSL |
| [Dashboards em Power BI](https://github.com/Kusterjv/dashboards-powerbi) | Painéis de visualização de dados feitos na formação da Data Science Academy | Power BI |
| [Projetos em Python](https://github.com/Kusterjv/analises-python) | Notebooks e scripts de análise e ciência de dados | Python, Jupyter |

## 📫 Contato

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/jo%C3%A3o-vitor-k%C3%BCster-127b67235)
[![E-mail](https://img.shields.io/badge/E--mail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kusterjv@gmail.com)
