<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a2980,100:26d0ce&height=180&section=header&text=R%C3%BAbem%20Vieira&fontSize=48&fontColor=ffffff&fontAlignY=35&desc=Desenvolvedor%20Fullstack%20%7C%20E-commerce&descAlignY=58&descSize=18&animation=fadeIn" alt="Rúbem Vieira" width="100%"/>

<a href="https://br.linkedin.com/in/rubemvieira/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=26D0CE&center=true&vCenter=true&width=520&lines=Python+%7C+Django+REST+%7C+PostgreSQL;React+%7C+Next.js+%7C+TypeScript;APIs%2C+integra%C3%A7%C3%B5es+e+infra+em+produ%C3%A7%C3%A3o" alt="Stack" />
</a>

<br/>

<a href="https://br.linkedin.com/in/rubemvieira/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:rubemvn17@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
<a href="https://instagram.com/rubem_vn"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram"/></a>
<img src="https://komarev.com/ghpvc/?username=rubemvn&label=Visitas+no+perfil&color=26d0ce&style=for-the-badge" alt="Visitas no perfil"/>

</div>

<br/>

## 🧑‍💻 Sobre mim

```yaml
nome:      Rúbem Vieira
cargo:     Desenvolvedor Fullstack
foco:      E-commerce de alto volume
backend:   Python · Django REST · Celery · PostgreSQL · Redis Cache
frontend:  React · Next.js · TypeScript · MUI
infra:     AWS · Docker · Kubernetes · ArgoCD
estudando: [PostgreSQL avançado, Kubernetes, DDD, DevOps]
formação:  ADS — Descomplica Digital
contato:   rubemvn17@gmail.com
```

Trabalho com plataformas de e-commerce **do backend à infraestrutura**: APIs e integrações críticas (frete, logística, pagamento, mensageria), pipelines assíncronos, consultas SQL de alto volume e interfaces de loja voltadas para conversão.

Gosto de problema de verdade — query lenta, incidente em produção, integração que quebra na borda. Prefiro solução simples e sustentável a arquitetura complexa sem necessidade.

<br/>

## 🛠️ Tech Stack

<table>
  <tr>
    <td align="right"><b>Backend</b></td>
    <td><img src="https://skillicons.dev/icons?i=py,django,kafka,nodejs&theme=dark" height="42" alt="Python, Django, Kafka, Node.js"/></td>
  </tr>
  <tr>
    <td align="right"><b>Frontend</b></td>
    <td><img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,mui,tailwind,html,css&theme=dark" height="42" alt="TypeScript, JavaScript, React, Next.js, MUI, Tailwind, HTML, CSS"/></td>
  </tr>
  <tr>
    <td align="right"><b>Dados</b></td>
    <td><img src="https://skillicons.dev/icons?i=postgres,redis&theme=dark" height="42" alt="PostgreSQL, Redis"/></td>
  </tr>
  <tr>
    <td align="right"><b>Cloud &amp; DevOps</b></td>
    <td><img src="https://skillicons.dev/icons?i=aws,docker,kubernetes,linux,git,github,bitbucket&theme=dark" height="42" alt="AWS, Docker, Kubernetes, Linux, Git, GitHub, Bitbucket"/></td>
  </tr>
</table>

<sub>
  <img src="https://img.shields.io/badge/Celery-37814A?style=flat-square&logo=celery&logoColor=white" alt="Celery"/>
  <img src="https://img.shields.io/badge/Django_REST-A30000?style=flat-square&logo=django&logoColor=white" alt="Django REST"/>
  <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=flat-square&logo=argo&logoColor=white" alt="Argo CD"/>
  <img src="https://img.shields.io/badge/Oracle_Commerce_Cloud-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle Commerce Cloud"/>
  <img src="https://img.shields.io/badge/Logfire-FF5F1F?style=flat-square&logo=pydantic&logoColor=white" alt="Logfire"/>
</sub>

<br/><br/>

## 💼 No que tenho trabalhado

<details open>
<summary><b>🔌 Integrações & APIs</b></summary>
<br/>

- API de **pré-postagem dos Correios (CWS)** — validação de valor declarado, serviços adicionais e regras por código de serviço
- Camada de **roteamento de notificações**: SendGrid (e-mail transacional) e Sinch (SMS / WhatsApp)
- Webhooks de WhatsApp com autenticação Bearer/Basic e depuração de controle de acesso

</details>

<details>
<summary><b>⚙️ Backend assíncrono</b></summary>
<br/>

- Tarefas **Celery** para processamento de pedidos e retentativas
- Mensageria com **Kafka** entre serviços de pedido, estoque e logística
- Jobs de monitoramento que consolidam métricas diárias e publicam alertas no **Slack**

</details>

<details>
<summary><b>🐘 PostgreSQL</b></summary>
<br/>

- Funções de **precificação de e-commerce** e correção de duplicidade em joins de promoção
- Diagnóstico de duplicados, alterações de schema e joins multi-tabela para popular novas colunas
- Queries de conferência (**dry-run**) sempre antes de qualquer escrita em produção

</details>

<details>
<summary><b>☁️ Infra & incidentes</b></summary>
<br/>

- Investigação de **HTTP 499 em massa** no Kubernetes: restart de pods por SIGTERM, `preStop` curto, memory request subdimensionado e probes grosseiras
- Pico de CPU em EC2 rastreado até serviços internos chamando endpoint depreciado em loop, confirmado por análise de log do nginx
- GitOps com CodeBuild · Kustomize · ArgoCD

</details>

<details>
<summary><b>🎨 Frontend & Oracle Commerce Cloud</b></summary>
<br/>

- Páginas institucionais com foco em **SEO** (canonical, title/meta únicos) e **acessibilidade** (hierarquia de headings, `aria-label`)
- Componentes React/MUI, animações de `ProductCard`, customização de DataGrid
- Templates de e-mail transacional em **FreeMarker** corrigidos em 42 locales

</details>

<br/>

## 📊 GitHub

<div align="center">

<!-- Badges estáticas: renderizadas pelo shields.io, nunca quebram -->
<img src="https://img.shields.io/github/followers/rubemvn?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1b27&color=26d0ce" alt="Seguidores"/>
<img src="https://img.shields.io/github/stars/rubemvn?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1b27&color=26d0ce" alt="Estrelas"/>

<br/><br/>

<!--
  Os cards abaixo usam as instâncias públicas dos projetos.
  Se ficarem quebrando por rate limit, faça o deploy da sua própria
  instância na Vercel e troque o domínio (instruções no repo de cada projeto).
-->
<a href="https://github.com/rubemvn">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=rubemvn&show_icons=true&theme=tokyonight&hide_border=true&cache_seconds=86400" alt="Estatísticas do GitHub de Rúbem Vieira"/>
</a>
<a href="https://github.com/rubemvn">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rubemvn&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&cache_seconds=86400" alt="Linguagens mais usadas"/>
</a>

<br/><br/>

<img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=rubemvn&theme=tokyo-night&hide_border=true&area=true&custom_title=Atividade%20nos%20%C3%BAltimos%2031%20dias" alt="Gráfico de atividade"/>

<br/><br/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Rubemvn/Rubemvn/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Rubemvn/Rubemvn/output/github-contribution-grid-snake.svg"/>
  <img width="95%" src="https://raw.githubusercontent.com/Rubemvn/Rubemvn/output/github-contribution-grid-snake.svg" alt="Cobrinha comendo as contribuições"/>
</picture>

</div>

<br/>

## 📌 Projetos em destaque

<table>
  <tr>
    <th align="left">Projeto</th>
    <th align="left">Descrição</th>
    <th align="left">Stack</th>
  </tr>
  <tr>
    <td><a href="https://github.com/rubemvn"><b>Controle Financeiro para Casais</b></a></td>
    <td>App de finanças compartilhadas: lançamentos recorrentes, categorias e exportação para planilha</td>
    <td><sub>Next.js · Django REST · PostgreSQL · R2</sub></td>
  </tr>
  <tr>
    <td><a href="https://github.com/rubemvn"><b>Monitor de Pedidos</b></a></td>
    <td>Scheduler que consolida o volume diário de pedidos e publica o resumo no Slack</td>
    <td><sub>Python · PostgreSQL · Slack API</sub></td>
  </tr>
</table>

<br/>

<div align="center">

📫 **rubemvn17@gmail.com** — aberto a conversar sobre backend, e-commerce e infraestrutura.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:26d0ce,100:1a2980&height=120&section=footer" alt="" width="100%"/>

</div>
