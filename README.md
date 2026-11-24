# 🔄 FlowSync

Criação do website institucional da **FlowSync**, uma startup SaaS fictícia de gestão de projetos e colaboração em equipa, com o objetivo de apresentar a plataforma a pequenas empresas, agências, equipas remotas, startups e freelancers, transmitir credibilidade e converter visitantes em utilizadores através de chamadas à ação claras.

> Projeto desenvolvido no âmbito da UFCD **10790 – Projeto de programação** (IEFP).

🔗 **Aceder ao Website:** [https://flowsync.exemplo.com](https://flowsync.exemplo.com)

---

## 💡 Conceito

A FlowSync é uma plataforma SaaS (*Software as a Service*) que ajuda equipas a organizar projetos, colaborar em tempo real e acompanhar o progresso do trabalho numa única plataforma.

> *"Organiza projetos, equipa e comunicação num único espaço."*

---

## 🎯 Objetivos do Projeto

* **Divulgação:** Dar a conhecer a plataforma, as suas funcionalidades e a missão da marca.
* **Credibilidade:** Reforçar a confiança com secção "Sobre", processo de trabalho, testemunhos e logótipos de equipas que usam o produto.
* **Conversão:** Levar o visitante a experimentar a plataforma através de CTAs em todas as páginas (*Experimentar Gratuitamente*, *Começar Agora*).
* **Informação Útil:** Disponibilizar contactos, formulário de pedido de informações e localização.

---

## 👥 Público-alvo

* Pequenas empresas
* Agências de marketing
* Equipas remotas
* Startups
* Freelancers

---

## 🗂️ Estrutura do Site

| Página | Descrição |
| --- | --- |
| **Home** | Hero com CTA, secção "Como podemos ajudar a tua equipa?" com 6 cards de funcionalidades, equipas que usam o FlowSync, testemunho e CTA final. |
| **Sobre** | Quem somos, missão, o que fazemos, processo em 6 passos (Planear → Melhorar) e "Porque escolher o FlowSync?". |
| **Funcionalidades** | Gestão de projetos, Quadros Kanban, Gestão de equipas, Automações, Relatórios e Integrações (Slack, Google Drive, Microsoft Teams, Zoom). |
| **Contactos** | Formulário de contacto, mapa (Google Maps com consentimento), morada, email e telefone. |

---

## 🎨 Identidade Visual

| Elemento | Valor |
| --- | --- |
| Cor primária (azul) | `#2563EB` |
| Cor secundária (azul escuro) | `#1E293B` |
| Cor de destaque (verde) | `#22C55E` |
| Fundo | `#F8FAFC` |
| Tipografia dos títulos | **Poppins** (Google Fonts) |
| Tipografia do texto | **Inter** (Google Fonts) |

---

## 💻 Tech Stack

Tecnologias e ferramentas utilizadas no desenvolvimento deste projeto:

![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![Astra](https://img.shields.io/badge/Astra_Theme-0274E6?style=for-the-badge&logo=wordpress&logoColor=white)
![Elementor](https://img.shields.io/badge/Elementor-92003B?style=for-the-badge&logo=elementor&logoColor=white)
![SureForms](https://img.shields.io/badge/SureForms-F0510F?style=for-the-badge&logoColor=white)
![SureRank](https://img.shields.io/badge/SureRank-1E293B?style=for-the-badge&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Google Fonts](https://img.shields.io/badge/Google_Fonts-4285F4?style=for-the-badge&logo=googlefonts&logoColor=white)

* **WordPress + tema Astra:** base do site e sistema de design.
* **Elementor:** construção visual das páginas.
* **SureForms:** formulário de contacto (as entradas são geridas no painel do WordPress).
* **SureRank:** otimização SEO.
* **Google Fonts:** Poppins e Inter.
* **Imagens:** bancos gratuitos [Pexels](https://www.pexels.com) e [Unsplash](https://unsplash.com).

---

## 🚀 Como executar o projeto localmente

Como o projeto é construído em WordPress (e não com `npm`), a execução local faz-se com um ambiente PHP + MySQL. Se quiseres correr o projeto no teu computador, segue estes passos:

1. **Instalar um ambiente local de WordPress**, como [LocalWP](https://localwp.com), XAMPP ou WAMP, e criar um novo site.

2. **Clonar o repositório** para uma pasta temporária:

```
git clone https://github.com/utilizador/flowsync.git
```

3. **Copiar os ficheiros do projeto** (pasta `wp-content`: temas, plugins e *uploads*) para a instalação local do WordPress.

4. **Importar a base de dados** (ficheiro `.sql` ou pacote de migração incluído no repositório) através do phpMyAdmin ou da ferramenta de importação do teu ambiente.

5. **Iniciar o site** pelo painel do ambiente local e aceder a `http://flowsync.local` (ou ao endereço indicado) e a `/wp-admin` para a área de administração.

> ⚠️ **Nota:** nunca publiques credenciais de administração no repositório. Define o utilizador e a palavra-passe no teu ambiente local.

---

## 📸 Pré-visualização

| Página | Captura |
| --- | --- |
| Home | `docs/screenshots/home.png` |
| Sobre | `docs/screenshots/sobre.png` |
| Funcionalidades | `docs/screenshots/funcionalidades.png` |
| Contactos | `docs/screenshots/contactos.png` |

---

## 🧠 Case Study

**Problema:** as equipas usam múltiplas ferramentas e têm dificuldade em centralizar a informação.

**Objetivo:** criar uma *landing page* institucional para uma startup SaaS focada em colaboração e gestão de projetos.

**Processo:**

* Pesquisa de websites SaaS
* Definição da arquitetura de informação
* Criação da identidade visual
* Implementação em WordPress com Astra

**Competências demonstradas:** UX Design, UI Design, Responsive Design, WordPress, Astra Theme, Design System e Arquitetura de Informação.

---

## 👩‍💻 Autoria

Desenvolvido por **Mariana Correia**
