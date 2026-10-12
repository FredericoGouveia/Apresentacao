<div align="center">

# Frederico Gouveia

**Desenvolvedor em formação** · IA local, backend e web

CTESP em Desenvolvimento Web e Multimédia @ IPCA · antes, Gestão e Programação de Sistemas Informáticos @ OFICINA

<a href="https://github.com/Ybt2"><img src="https://img.shields.io/badge/GitHub-Ybt2-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Ybt2"></a>
<a href="https://www.linkedin.com/in/frederico-gouveia-62b67632b"><img src="https://img.shields.io/badge/LinkedIn-Frederico_Gouveia-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>

</div>

---

## Olá, sou o Fred

Sou da zona de Braga de momento ando no **CTESP de Desenvolvimento Web e Multimédia no UPCA**, depois de acabar o curso profissional de **Gestão e Programação de Sistemas Informáticos na OFICINA - Escola Profissional** (média final de 17/20). Pelo caminho fiz dois estágios.

O que gosto mesmo: **backend, IA local/self-hosted e automação**. Prefiro montar um pipeline open source que controlo por completo.

- A construir neste momento: ferramentas de IA local-first e pequenas automações
- Áreas de foco: pipelines RAG, tooling de LLM, APIs REST, scraping
- Idiomas: Português (nativo) · Inglês (fluência de trabalho)
  
---

## Projeto em destaque: ReCallBook

<a href="https://github.com/Ybt2/ReCallBook"><img src="https://img.shields.io/badge/Repo_oficial-Ybt2%2FReCallBook-2ea44f?style=for-the-badge&logo=github&logoColor=white" alt="Repositório do ReCallBook"></a>
<img src="https://img.shields.io/github/stars/Ybt2/ReCallBook?style=for-the-badge&color=yellow" alt="Stars">

> **O teu assistente de estudo local com RAG.** Carrega PDFs, imagens e ficheiros de texto e depois conversa com eles, gera quizzes e flashcards, tudo a correr 100% na tua máquina.

Um **clone open source do NotebookLM, focado em privacidade e agnóstico de modelo**, construído de raiz como projeto final de curso (**PAP**), onde tirei **20/20**.

**Porque é que existe:** pessoas podem trabalhar com material confidencial (clínico, jurídico, interno) e mandá-lo para um LLM na nuvem está fora de questão. O ReCallBook mantém o pipeline todo local e mesmo assim entrega o que interessa: respostas com fontes citadas, streaming, autenticação multi-utilizador e interface multilingue.

| O que faz | Como |
| --- | --- |
| Conversar com os teus documentos | Recuperação RAG + fontes citadas, em streaming via SSE com indicadores de fase |
| Ingestão de documentos | PDFs (incluindo extração de imagens incorporadas com `pdfjs-dist` + `sharp`), JPEG/PNG/SVG, texto e markdown, até 50 MB |
| Recuperação de melhor qualidade | Embeddings `bge-m3` + reranker cross-encoder `jina-reranker-v2` em processo |
| Material de estudo | Quizzes de escolha múltipla (fácil/médio/difícil) gerados automaticamente, com pontuação, e flashcards |
| Multi-utilizador | Autenticação JWT, hashing de passwords com bcrypt, verificação de propriedade e rate limiting |
| Corre em hardware modesto | Qualquer modelo que o `Ollama` sirva, do `llama3.2:3b` em 8 GB de RAM ao `gpt-oss:20b` numa GPU de 12 GB |
| Instalação em qualquer lado | Instaladores Bash e PowerShell com deteção de dependências, ou instalação como serviço nativo em Linux e Windows |

**Stack:** Vue 3 + Pinia + Tailwind · Node.js 22 + Express 5 + LangChain.js · MySQL 8 · Qdrant · Ollama (`bge-m3` + qualquer modelo de chat/visão) · HuggingFace Transformers · JWT · Docker Compose · Jest + Supertest

---

## Outras coisas que construí

| Projeto | O que é | Stack | Link |
| --- | --- | --- | --- |
| **Telegram Vinted Scraper** | Bot de Telegram que pesquisa no Vinted a pedido (`/vinted <termo>`) e responde com foto, título, preço, marca, estado e link direto. Restrito a IDs de utilizadores autorizados, com registo de atividade | Python · python-telegram-bot · vinted-scraper · httpx | [repo](https://github.com/Ybt2/telegram_vinted_scrapper) |
| **number_recognition** | Reconhecedor de dígitos manuscritos: uma CNN treinada com o MNIST que lê dígitos a partir de imagens externas, com uma janela de desenho ao vivo | Python · TensorFlow · OpenCV | [repo](https://github.com/Ybt2/number_recognition) |

---

## Tecnologias com que trabalho

**Linguagens**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

**Frontend**

![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Blazor](https://img.shields.io/badge/Blazor-512BD4?style=flat-square&logo=blazor&logoColor=white)

**Backend e dados**

![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express_5-000000?style=flat-square&logo=express&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square&logo=qdrant&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**IA e automação**

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain.js-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)

**Ferramentas e deploy**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=flat-square&logo=netlify&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=flat-square&logo=xampp&logoColor=white)

---

## Experiência

**Estagiário · Domoweb** (Vila Nova de Famalicão) · Set 2025 - Dez 2025
Desenvolvimento de software à medida para clientes empresariais. Trabalhei em entregas reais dentro de uma equipa pequena.

**Estagiário · Domoweb** · Fev 2025
Primeiro contacto com a stack e com o fluxo de trabalho da empresa.

**Mini-estágio · Avidsoft** (Vila Nova de Famalicão) · Mar 2024
Serviços de IT, cibersegurança e soluções cloud: helpdesk e noções de infraestrutura.

---

## Formação e certificações

**UPCA** · CTESP em Desenvolvimento Web e Multimédia (nível 5) · 2026 - em curso
**OFICINA - Escola Profissional** · Gestão e Programação de Sistemas Informáticos · 2023 - 2026 · média final **17/20**

- **PAP (projeto final): ReCallBook** · **20/20**
- **Crash Course on Python** · Google, via Coursera · Jan 2024 · [credencial](https://coursera.org/account/accomplishments/records/98XU8DWB5YY9)
- **Intro to Machine Learning** · Kaggle
- **Pandas** · Kaggle

---

## GitHub

<div align="center">

<a href="https://github.com/Ybt2"><img src="https://github-readme-stats.vercel.app/api?username=Ybt2&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&theme=dark" alt="Estatísticas do GitHub do Ybt2" height="165"></a>

</div>

---

</div>
