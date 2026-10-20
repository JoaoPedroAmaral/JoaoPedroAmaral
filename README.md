<div align="center">

# João Pedro Amaral Rosa

**Desenvolvedor Fullstack** · Brasília, DF

[PORTFÓLIO](https://portifolio-9txm.onrender.com/)

[![ServiceNow CSA](https://img.shields.io/badge/ServiceNow-Certified%20System%20Administrator-62D84E?style=for-the-badge&logo=servicenow&logoColor=white)](https://www.servicenow.com)
[![Scrum](https://img.shields.io/badge/Scrum-Fundamentals%20Certified-0052CC?style=for-the-badge&logo=scrumalliance&logoColor=white)](#)

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaopedroamaralrosa)
[![Gmail](https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:joaopedro251900@gmail.com)

</div>

---

Desenvolvo aplicações de ponta a ponta — Java e Spring Boot no back-end, React e Vue.js no front-end. Trabalho com construção e consumo de APIs REST, bancos relacionais e integração entre sistemas. Atuo em tecnologia desde 2022, com passagem por sistemas corporativos críticos e, hoje, desenvolvimento de produto em time ágil.

![snake animation](https://raw.githubusercontent.com/cassimahmedattia/cassimahmedattia/output/snake.svg)

---

## Stack

<div align="center" >
  <img src="https://skillicons.dev/icons?i=java,spring,maven,js,ts,react,nextjs,vue,nodejs,express,mongodb,postgres,mysql,python,tailwind,bootstrap,html,css,git&perline=10" />
</div>

---

**Back-end** — Java, Spring Boot, Spring Framework, Node.js, Express, APIs REST, Maven, JWT

**Front-end** — React, React Native, Next.js, Vue.js, Tailwind CSS, TanStack Query

**Dados** — PostgreSQL, MySQL, Oracle, MongoDB, IndexedDB

**Ferramentas** — Git, GitHub, GitLab, CI/CD

---

## ServiceNow

Certificado como **System Administrator (CSA)** e formado pelo programa **Chain Academy**, com trilhas em administração da plataforma, scripting, Flow Designer, UI Builder e inteligência artificial.

- Aplicações em escopo próprio — modelagem de tabelas, dicionário de dados, choice lists, ACLs e menus
- Scripted REST API com validação de contrato e retorno padronizado em JSON
- Integrações de saída via REST Message, encapsuladas em Script Include e acionadas por Business Rule assíncrona
- Import Sets e Transform Maps com coalesce para importação sem duplicidade
- Widgets do Service Portal em JavaScript, HTML e CSS
- Automações em Flow Designer e páginas em UI Builder

---

## Projeto em destaque

### [Cofre de Gastos](https://github.com/JoaoPedroAmaral/Cofre-de-gastos)

Gerenciador de finanças pessoais que monta painel de gastos a partir do extrato do próprio banco. Importa OFX, CSV, XLSX e PDF de fatura, com detecção de formato pelo conteúdo, mapeamento manual de colunas para layouts desconhecidos, remoção de lançamentos duplicados em reimportações e identificação de transferências entre contas próprias para que não contem como despesa.

A decisão central do projeto é arquitetural: **nenhum dado sai do navegador**. Os arquivos são lidos em memória, o que é armazenado fica cifrado em AES-256-GCM com chave derivada por PBKDF2 no IndexedDB, e a Content Security Policy bloqueia requisições de rede com `connect-src 'none'`. O service worker permite uso offline e instalação como aplicativo.

Construído em JavaScript puro com módulos ES nativos, sem framework e sem etapa de build.

`JavaScript` `Web Crypto API` `IndexedDB` `Service Worker` `pdf.js` `SheetJS`

---

<div align="center">

<img src="https://streak-stats.demolab.com?user=JoaoPedroAmaral&theme=merko&background=161b22&stroke=393f48&border=161b22&exclude_days=Sun%2CSat" />

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JoaoPedroAmaral&layout=compact&theme=merko&bg_color=161b22&border_color=393f48&langs_count=8" />

</div>
