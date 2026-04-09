# 📊 Portfólio de Data Analytics — Fabrício Silva

> **Analista de Dados | Supply Chain & Suprimentos**  
> Transformando gargalos operacionais em eficiência através de automação, visualização de dados e inteligência analítica.

---

## 🔗 Demonstração ao Vivo

O portfólio está publicado e acessível ao público via **GitHub Pages**:

**👉 [Acessar o Portfólio Online](https://fabricio-o-s.github.io/Portfolio_Data_Analytics/)**

---

## 📋 Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Estrutura de Arquivos](#estrutura-de-arquivos)
- [Projetos em Destaque](#projetos-em-destaque)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Como Rodar Localmente](#como-rodar-localmente)
- [Como Publicar no GitHub Pages](#como-publicar-no-github-pages)
- [Conceitos Aprendidos](#conceitos-aprendidos)
- [Próximos Passos](#próximos-passos)
- [Contato](#contato)

---

## 📖 Sobre o Projeto

Este repositório contém o **portfólio profissional de Data Analytics** do Fabrício Silva — um site estático construído em HTML5 e CSS3 usando o template **Editorial do HTML5 UP** como base.

O portfólio foi desenvolvido com foco em **aprendizado progressivo**: partindo de um template base e customizando cada seção para representar projetos reais de Supply Chain, Compras e Logística.

### 🎯 Objetivo

Apresentar de forma clara, organizada e profissional os projetos desenvolvidos nas áreas de:
- 🐍 **Python / Pandas** → automação e saneamento de dados
- 📊 **Power BI / DAX** → dashboards estratégicos e KPIs
- 🗄️ **SQL** → consultas e modelagem de dados
- ⚙️ **ERP (SAP/TOTVS)** → integração com sistemas corporativos

---

## 📁 Estrutura de Arquivos

```
Portfolio Data Analytics/        ← Pasta raiz do projeto
│
├── index.html                   ← Página principal (home do portfólio)
├── projeto_compras.html         ← Página de detalhes: Dashboard de Compras
├── projeto_vendas.html          ← Página de detalhes: TechNova Vendas
├── projeto_logistica.html       ← Página de detalhes: Dashboard Logística
│
├── assets/                      ← Recursos do template Editorial
│   ├── css/
│   │   └── main.css             ← Folha de estilos principal do template
│   ├── js/
│   │   ├── jquery.min.js        ← Biblioteca jQuery (manipulação DOM)
│   │   ├── browser.min.js       ← Detecção de navegador
│   │   ├── breakpoints.min.js   ← Breakpoints para layout responsivo
│   │   ├── util.js              ← Funções utilitárias do template
│   │   └── main.js              ← Script principal: sidebar, animações
│   ├── sass/                    ← Arquivos fonte SASS (pré-processador CSS)
│   └── webfonts/                ← Fontes do Font Awesome (ícones)
│
├── images/                      ← Todas as imagens do portfólio
│   ├── banner.png               ← Imagem de capa da seção de apresentação
│   ├── saneamento.png           ← Imagem do projeto de saneamento de dados
│   ├── automacao.png            ← Imagem do projeto de automação fiscal
│   ├── dash_compras.png         ← Screenshot do Dashboard de Compras
│   ├── dash_vendas.png          ← Screenshot do Dashboard TechNova
│   ├── dash_logistica.png       ← Screenshot do Dashboard de Logística
│   └── 1739905716703.jpg        ← Foto de perfil pessoal
│
├── data/                        ← (Reservado) Arquivos .csv, .xlsx para projetos Python
├── src/                         ← (Reservado) Scripts Python dos projetos
├── tests/                       ← (Reservado) Testes dos scripts Python
├── docs/                        ← (Reservado) Anotações, diagramas, documentação
│
├── .gitignore                   ← Define o que NÃO deve ser enviado ao GitHub
├── LICENSE.txt                  ← Licença do template HTML5 UP (CCA 3.0)
├── README.md                    ← Este arquivo (documentação do projeto)
└── README.txt                   ← README original do template HTML5 UP
```

### 💡 Por que essa estrutura?

| Pasta | Propósito |
|-------|-----------|
| `assets/` | Recursos do template: CSS, JS, fontes. Não alterar sem necessidade |
| `images/` | Centraliza todas as imagens para fácil manutenção |
| `src/` | Todo código Python ficará aqui (padrão de mercado) |
| `data/` | Bases de dados, CSVs e arquivos de entrada dos scripts |
| `tests/` | Scripts que validam se o código Python funciona corretamente |
| `docs/` | Documentação técnica, fluxogramas e anotações de estudo |

---

## 🚀 Projetos em Destaque

### 1. 📦 Dashboard de Compras — Follow UP
**Arquivo:** `projeto_compras.html`  
**Ferramenta:** Power BI + DAX + Power Query  

**Problema resolvido:** Falta de visibilidade sobre o status das ordens de compra e o desempenho dos fornecedores, levando a rupturas de estoque e atrasos operacionais.

**Solução:** Dashboard estratégico que monitora em tempo real:
- Status de **374 ordens de compra** em aberto
- Pipeline completo: Requisição → Aprovação → Pedido → Entrega
- Performance individual de fornecedores (atrasos, conformidade)
- Lead Time médio por categoria de produto

➡️ [Acessar Dashboard Online](https://app.powerbi.com/view?r=eyJrIjoiZjY3NjJkMWEtMTdlMi00ZDc2LTg2NTAtMjA3ZTc1MmUwYWNjIiwidCI6IjU0YjdjOTcwLTNkZmUtNDYyYS04ZjdmLTc0ODk2MzIzOGY2NyJ9)

---

### 2. 💹 TechNova — Dashboard Comercial & Vendas
**Arquivo:** `projeto_vendas.html`  
**Ferramenta:** Power BI + DAX Avançado + Star Schema  

**Problema resolvido:** Gestores sem visão clara sobre quais produtos, marcas e regiões geram mais margem, dificultando decisões comerciais estratégicas.

**Solução:** Dashboard analítico para empresa varejista fictícia "TechNova" com:
- **Receita Total:** R$ 7,06 Milhões
- **Lucro Bruto:** R$ 4,56 Milhões (Margem de 64,53%)
- **Volume:** 45.314 unidades faturadas
- **Taxa de Devolução:** 3,27%
- Filtros interativos por produto, marca, tipo de loja e continente

**Destaque técnico:** Modelagem em **Star Schema** e cálculos DAX avançados de Time Intelligence.

➡️ [Acessar Dashboard Online](https://app.powerbi.com/view?r=eyJrIjoiOTNkYmJmZTctMTA3YS00MWNkLTk3ZDktMmE2N2U5ZDE5Y2IwIiwidCI6IjU0YjdjOTcwLTNkZmUtNDYyYS04ZjdmLTc0ODk2MzIzOGY2NyJ9)

---

### 3. 🚛 Dashboard Logística — Desempenho Operacional
**Arquivo:** `projeto_logistica.html`  
**Ferramenta:** Power BI + Power Query  

**Problema resolvido:** Controladores de tráfego sem dados estruturados sobre atrasos de entrega, rotas problemáticas e motivos de devolução.

**Solução:** Painel operacional com foco em eficiência de frota:
- **8.026 ordens** de frete analisadas (+3,1% crescimento)
- **Nível de Serviço (On-Time):** 53% das entregas dentro do SLA
- **Análise de ofensores:** "Desistência do cliente" como principal causa de devolução
- Faróis de alerta para identificação proativa de gargalos

➡️ [Acessar Dashboard Online](https://app.powerbi.com/view?r=eyJrIjoiMzE0MWE2M2UtZjYzMi00ZjY2LTgxNWUtNGE5M2Y0ZjM0ZTEwIiwidCI6IjU0YjdjOTcwLTNkZmUtNDYyYS04ZjdmLTc0ODk2MzIzOGY2NyJ9)

---

### 4. 🐍 Saneamento e Padronização de Cadastros *(em breve)*
**Arquivo:** `src/saneamento_cadastros.py` *(a criar)*  
**Ferramenta:** Python + Pandas  

**Problema resolvido:** Descrições de produtos duplicadas ou inconsistentes no ERP, causando erros no fluxo de compras e estoque impreciso.

**Solução planejada:** Script Python com Pandas para limpeza e normalização automática de bases de cadastro.

---

### 5. 📄 Automação de Recebimento Fiscal *(em breve)*
**Arquivo:** `src/automacao_fiscal.py` *(a criar)*  
**Ferramenta:** Python + xml.etree / lxml  

**Problema resolvido:** Conferência manual de Notas Fiscais contra Pedidos de Compra: processo lento, manual e sujeito a erros humanos.

**Solução planejada:** Rotina Python para leitura massiva de XMLs de NF-e, cruzamento automático com o sistema e validação das condições fiscais.

---

## 🛠️ Tecnologias Utilizadas

### Front-end (Site do Portfólio)

| Tecnologia | Versão | Para que serve |
|------------|--------|----------------|
| HTML5 | — | Estrutura e semântica das páginas |
| CSS3 | — | Estilização e layout responsivo |
| JavaScript | ES6+ | Interatividade e comportamento |
| jQuery | 3.x | Simplificação de manipulação DOM |
| Font Awesome | 5.x | Ícones vetoriais (LinkedIn, GitHub, etc.) |
| Template Editorial | HTML5 UP | Base do layout de duas colunas |

### Projetos Analíticos

| Tecnologia | Para que serve |
|------------|----------------|
| Power BI Desktop | Construção dos dashboards |
| Power Query (M) | ETL: extração, transformação e carga de dados |
| DAX | Linguagem de cálculo do Power BI |
| Python 3.x | Automação e saneamento de dados |
| Pandas | Manipulação de DataFrames no Python |
| SQL | Consultas e modelagem relacional |

---

## 💻 Como Rodar Localmente

Este projeto é um **site estático** — não precisa de servidor, banco de dados ou instalação de dependências.

### Método 1: Abrir diretamente (mais simples)
```
1. Baixe ou clone este repositório no seu computador
2. Navegue até a pasta do projeto
3. Dê duplo clique no arquivo: index.html
4. O site abre no seu navegador padrão ✅
```

### Método 2: Clonar via Git
```bash
# Clone o repositório
git clone https://github.com/Fabricio-O-S/Portfolio_Data_Analytics.git

# Entre na pasta do projeto
cd Portfolio_Data_Analytics

# Abra o arquivo principal (Windows)
start index.html

# Abra o arquivo principal (Mac/Linux)
open index.html
```

### Método 3: Servidor local (recomendado para desenvolvimento)

Se você tiver Python instalado, pode usar o servidor embutido:
```bash
# Python 3
python -m http.server 8000

# Depois abra no navegador:
# http://localhost:8000
```

Ou com a extensão **Live Server** no VS Code:
```
1. Instale a extensão "Live Server" no VS Code
2. Clique direito em index.html
3. Selecione "Open with Live Server"
4. O site abre automaticamente em http://localhost:5500
```

> **💡 Dica:** O servidor local é melhor porque simula um ambiente real e evita problemas de CORS com arquivos locais.

---

## 🌐 Como Publicar no GitHub Pages

O GitHub Pages hospeda sites estáticos **gratuitamente** direto do seu repositório.

```
1. Faça push de todo o código para o repositório no GitHub
2. No GitHub, vá em: Repositório → Settings → Pages
3. Em "Source", selecione: "Deploy from a branch"
4. Em "Branch", selecione: "main" e "/root"
5. Clique em "Save"
6. Aguarde ~2 minutos
7. Seu site estará disponível em:
   https://[seu-usuario].github.io/[nome-do-repositorio]/
```

---

## 📚 Conceitos Aprendidos

### HTML Fundamental
- **Estrutura básica** do documento: `<!DOCTYPE>`, `<html>`, `<head>`, `<body>`
- **Tags semânticas** do HTML5: `<header>`, `<nav>`, `<section>`, `<article>`, `<footer>`
- **Por que usar semântica?** → Melhor acessibilidade (leitores de tela) e SEO (Google entende a estrutura)
- **Diferença entre `id` e `class`**: `id` é único por página, `class` pode ser reutilizada
- **Links internos com âncoras**: `href="#projetos"` rola a página até o elemento com `id="projetos"`
- **Link externo em nova aba**: `target="_blank"` evita que o usuário perca a página atual
- **Entidades HTML**: `&amp;` = `&`, `&copy;` = `©`, `&lt;` = `<`

### CSS Aplicado
- **CSS Inline** (`style="..."`) vs **CSS Externo** (arquivo `.css`): quando usar cada um
- **Box Model**: toda elemento HTML é uma caixa com `margin`, `border`, `padding` e `content`
- **Flexbox & Grid**: o template usa-os internamente para o layout de duas colunas
- **`object-fit: cover`**: como manter imagens sem distorção em contêineres de tamanho fixo
- **`border-radius: 50%`**: transforma qualquer elemento quadrado em um círculo
- **Valores relativos**: `em` é relativo ao tamanho da fonte atual (mais flexível que `px`)
- **`rgba()`**: define cores com canal alpha (transparência)

### JavaScript e o DOM
- **DOM** (Document Object Model): a representação em árvore do HTML que o JS manipula
- **Por que scripts no final do `<body>`?** → Evita bloqueio de renderização, melhora performance percebida
- **jQuery**: biblioteca que simplifica `document.getElementById()` → `$('#id')`
- **Classe `is-preload`**: técnica para suprimir animações durante o carregamento da página

### Conceitos de Web
- **Site Estático vs Dinâmico**: estático = só HTML/CSS/JS; dinâmico = tem servidor e banco de dados
- **GitHub Pages**: hospedagem gratuita para sites estáticos
- **Responsividade**: como a meta tag `viewport` e o CSS permitem que o site funcione no celular
- **iFrame**: como embutir conteúdo externo (Power BI) dentro de uma página HTML
- **Técnica 16:9 com CSS**: `padding-bottom: 56.25%` para iframes responsivos

### Power BI & Dados
- **Star Schema**: modelo de dados otimizado para BI com tabela Fato + Dimensões
- **DAX**: linguagem de fórmulas do Power BI para medidas calculadas
- **Power Query (M)**: ferramenta ETL do Power BI para transformar dados brutos
- **KPI vs Métrica**: KPI é uma métrica estratégica que indica saúde do negócio
- **SLA**: Acordo de Nível de Serviço — prazo contratado para entrega/atendimento

---

## 🗺️ Próximos Passos

- [ ] Criar página `projeto_saneamento.html` com detalhes do script Python
- [ ] Criar página `projeto_fiscal.html` com detalhes da automação de NF-e
- [ ] Adicionar seção **"Sobre Mim / Currículo"** com histórico profissional
- [ ] Implementar o script Python de saneamento de cadastros (`src/`)
- [ ] Implementar o script Python de automação fiscal (`src/`)
- [ ] Adicionar meta tags de SEO (description, og:image) para melhor indexação
- [ ] Criar página de erro 404 personalizada
- [ ] Adicionar Google Analytics para rastrear visitas

---

## 📬 Contato

**Fabrício Silva**  
*Data Analyst | Supply Chain & Suprimentos*

| Canal | Link |
|-------|------|
| 📧 E-mail | [fabricio_la_gnt@hotmail.com](mailto:fabricio_la_gnt@hotmail.com) |
| 💼 LinkedIn | [linkedin.com/in/compradorfabriciosilva](https://www.linkedin.com/in/compradorfabriciosilva/) |
| 🐙 GitHub | [github.com/Fabricio-O-S](https://github.com/Fabricio-O-S) |
| 📍 Localização | Sertãozinho - SP, Brasil |
| 📱 Telefone | (16) 99106-9995 |

---

## 📄 Licença

O template **Editorial** foi desenvolvido por [HTML5 UP](https://html5up.net) e é licenciado sob a **Creative Commons Attribution 3.0 (CCA 3.0)**.  
Isso significa: pode usar livremente, inclusive comercialmente, desde que mantenha a atribuição ao autor original.

Todo o **conteúdo, projetos e textos** do portfólio são de autoria de **Fabrício Silva** © 2025. Todos os direitos reservados.

---

*Desenvolvido com 💙 por Fabrício Silva — aprendendo e construindo a cada projeto.*
