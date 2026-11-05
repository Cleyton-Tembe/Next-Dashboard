# Next Dashboard

Painel de administração (dashboard) em Next.js com gráficos interactivos, tabelas com pesquisa e animações: visão geral, produtos, utilizadores, vendas, encomendas, análise e definições.

> **Âmbito do projecto:** este é um projecto de estudo. Fi-lo para me familiarizar com o Next.js (App Router), o Recharts para gráficos e o Framer Motion para animações, e para pôr em prática a construção de uma interface de administração completa e responsiva. Os dados são fictícios e estão no próprio código, sem base de dados. Não é um produto final.

## Demo

🔗 **[Ver demo](COLOCA_AQUI_O_LINK_DA_DEMO)**

## Funcionalidades

- **Barra lateral recolhível**, com ícones coloridos para cada secção
- **Cartões de estatísticas** animados em todas as páginas
- **7 páginas:**
  - **Overview:** vendas ao longo do tempo, distribuição por categoria e vendas por canal
  - **Products:** tabela de produtos com pesquisa e tendência de vendas
  - **Users:** tabela de utilizadores com pesquisa, crescimento de utilizadores, mapa de calor da actividade e dados demográficos
  - **Sales:** evolução das vendas, vendas por categoria e tendência diária
  - **Orders:** tabela de encomendas com pesquisa, encomendas diárias e distribuição por estado
  - **Analytics:** receita contra objectivo, desempenho por canal e por produto, retenção de utilizadores, segmentação de clientes e sugestões ("AI-Powered Insights")
  - **Settings:** perfil, notificações com interruptores, segurança, contas ligadas e "zona de perigo"
- Gráficos de linhas, barras, área, circulares e de radar, com tooltips
- Animações de entrada com Framer Motion
- Tema escuro e layout responsivo

Os utilizadores de exemplo são personagens de Tekken (Jin Kazama, Kazuya Mishima…).

## Tecnologias

- **Next.js 15** (App Router) · **React 18** · **TypeScript**
- **Recharts** (gráficos)
- **Framer Motion** (animações)
- **Tailwind CSS 4**
- **Lucide React** (ícones)

## Como correr localmente

### Pré-requisitos

- **Node.js 18.18 ou superior**

Não precisas de base de dados nem de variáveis de ambiente.

### Passos

```bash
git clone https://github.com/Cleyton-Tembe/Next-Dashboard.git
cd Next-Dashboard
npm install
npm run dev
```

Abre `http://localhost:3000`.

## Autor

**Cleyton Tembe** — [GitHub](https://github.com/Cleyton-Tembe)
