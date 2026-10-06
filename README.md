<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,25&height=230&section=header&text=TechNews%20Today&fontSize=62&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Portal%20de%20not%C3%ADcias%20de%20tecnologia%20%7C%20HTML%20sem%C3%A2ntico%20%2B%20CSS%20puro&descAlignY=60&descSize=18" alt="Banner TechNews Today" />

<a href="https://github.com/SEU-USUARIO/technews-today">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=A78BFA&center=true&vCenter=true&width=680&lines=Um+portal+escuro+e+moderno+%F0%9F%8C%99;Glassmorphism+%2B+gradiente+no+texto+%E2%9C%A8;CSS+Grid+%2B+header+sticky+%F0%9F%A7%B1;Menos+de+50+linhas+de+CSS.+Zero+JavaScript.+%F0%9F%92%AA" alt="Animação de texto" />
</a>

<br/>

![HTML5](https://img.shields.io/badge/HTML5-semântico-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-puro-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-0%25-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Frameworks](https://img.shields.io/badge/Frameworks-nenhum-8B5CF6?style=for-the-badge)

![Linhas de CSS](https://img.shields.io/badge/CSS-máx.%2050%20linhas-0ea5e9?style=flat-square)
![Responsivo](https://img.shields.io/badge/Layout-responsivo-22c55e?style=flat-square)
![Tema](https://img.shields.io/badge/Tema-dark%20mode-111827?style=flat-square)
![Pontos](https://img.shields.io/badge/Desafio-100%20pontos-f59e0b?style=flat-square)
![SENAI](https://img.shields.io/badge/SENAI-1ID--DS-ef4444?style=flat-square)

<br/>

**[🌐 Ver demo](#-demo-ao-vivo) · [🎯 Desafio](#-o-desafio) · [🧩 Anatomia](#-anatomia-do-html) · [🎨 Técnicas de CSS](#-técnicas-de-css-usadas) · [🚀 Como rodar](#-como-executar) · [🙋 Autor](#-autor)**

</div>

---

## 📑 Sumário

<details open>
<summary><b>Clique para recolher/expandir o índice</b></summary>

1. [📖 Sobre o projeto](#-sobre-o-projeto)
2. [📸 Preview](#-preview)
3. [🌐 Demo ao vivo](#-demo-ao-vivo)
4. [🎯 O desafio](#-o-desafio)
5. [✅ Checklist de requisitos](#-checklist-de-requisitos)
6. [🛠️ Tecnologias](#️-tecnologias)
7. [🗂️ Estrutura do repositório](#️-estrutura-do-repositório)
8. [🧩 Anatomia do HTML](#-anatomia-do-html)
9. [🎨 Técnicas de CSS usadas](#-técnicas-de-css-usadas)
10. [📱 Layout responsivo](#-layout-responsivo)
11. [🌈 Paleta de cores](#-paleta-de-cores)
12. [🚀 Como executar](#-como-executar)
13. [📤 Como foi a entrega](#-como-foi-a-entrega)
14. [🧠 O que aprendi](#-o-que-aprendi)
15. [❓ Perguntas frequentes](#-perguntas-frequentes)
16. [🔮 Próximos passos](#-próximos-passos)
17. [🙋 Autor](#-autor)

</details>

---

## 📖 Sobre o projeto

O **TechNews Today** nasceu na **Aula 10** do curso de **Desenvolvimento de Sistemas (SENAI)**. Na aula, um portal de notícias de tecnologia foi **desmontado peça por peça** para entender o que cada tag HTML realmente faz. O desafio da semana foi pegar essa página "crua" e transformá-la em um **portal moderno e escuro**, usando **somente CSS**.

> 💡 **Ideia central:** o HTML já vem pronto e **não pode ser alterado**. Todo o visual vem de **um único arquivo CSS**, com no máximo **50 linhas**.

### ✨ Destaques

| | Recurso | Como foi feito |
|---|---|---|
| 🪟 | Header de vidro fosco | `backdrop-filter: blur()` + fundo translúcido |
| 🌈 | Título em degradê | `linear-gradient` + `background-clip: text` |
| 🧱 | Layout em grade | `display: grid` |
| 📌 | Cabeçalho que acompanha a rolagem | `position: sticky` |
| 📺 | Vídeo e newsletter lado a lado | CSS Grid com colunas |
| 📱 | Adaptação para celular | `@media (max-width: …)` |
| 📖 | "Leia mais" sem JavaScript | `<details>` + `<summary>` nativos |

---

## 📸 Preview

<!--
  📌 DICA: depois de subir os prints para a pasta /assets, remova este comentário
  e ajuste os nomes dos arquivos abaixo.

<div align="center">

| 🖥️ Desktop | 📱 Celular |
|:---:|:---:|
| <img src="assets/preview-desktop.png" width="520" alt="TechNews Today no desktop" /> | <img src="assets/preview-mobile.png" width="220" alt="TechNews Today no celular" /> |

</div>
-->

> 🖼️ *Os prints do projeto podem ser adicionados na pasta `assets/` e exibidos aqui.*

---

## 🌐 Demo ao vivo

Acesse o projeto publicado pelo **GitHub Pages**:

### 👉 [`https://SEU-USUARIO.github.io/technews-today/desafio10a.html`](https://SEU-USUARIO.github.io/technews-today/desafio10a.html)

<details>
<summary><b>⚙️ Como ativar o GitHub Pages neste repositório</b></summary>

1. Abra o repositório no GitHub e vá em **Settings** ⚙️
2. No menu lateral, clique em **Pages**
3. Em **Build and deployment**, escolha **Deploy from a branch**
4. Selecione a branch **`main`** e a pasta **`/ (root)`**
5. Clique em **Save** e aguarde cerca de 1 a 2 minutos ⏳
6. O link do site aparece no topo da página de Pages 🎉

> ⚠️ Como o arquivo principal se chama `desafio10a.html` (e não `index.html`), lembre de colocar o nome dele no final do link.

</details>

---

## 🎯 O desafio

> **📱🚀 Aula 10 — TechNews Today!** · Prof. **André Luis Denani** · **100 pontos**

Criar o arquivo **`10a_desafio.css`** e transformar a página `desafio10a.html` em um **portal moderno e escuro**, seguindo os prints de referência:

- 🪟 **Header** de vidro fosco
- 🌈 **Título** com degradê
- 📺 **Vídeo** e 📧 **newsletter** lado a lado
- 🌙 Visual escuro e moderno de ponta a ponta

---

## ✅ Checklist de requisitos

<details open>
<summary><b>📋 Requisitos técnicos do desafio</b></summary>

- [x] 🪟 **Glassmorphism** com `backdrop-filter`
- [x] 🌈 **Gradiente no texto**
- [x] 🧱 **CSS Grid** no layout
- [x] 📌 **Header** com `position: sticky`
- [x] 📱 **Media query** para celular
- [x] 📏 **No máximo 50 linhas** de CSS
- [x] 🚫 **Sem frameworks**
- [x] 🚫 **Sem JavaScript**
- [x] 🚫 **Sem mexer no HTML**

</details>

<details>
<summary><b>🏆 Boas práticas extras (capricho!)</b></summary>

- [x] 💬 Comentários nas partes importantes do CSS
- [x] 🔗 Nome do CSS idêntico ao do `<link>` no HTML
- [x] 📂 Repositório **público** no GitHub
- [x] 📝 README completo e organizado

</details>

---

## 🛠️ Tecnologias

<div align="center">

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white" alt="VS Code" />

</div>

---

## 🗂️ Estrutura do repositório

```text
📦 technews-today
 ┣ 📜 desafio10a.html     ← página completa (fornecida na aula, intocada)
 ┣ 🎨 10a_desafio.css     ← todo o visual do portal (máx. 50 linhas)
 ┗ 📖 README.md           ← você está aqui
```

> 🔗 O HTML carrega o estilo pelo `<link rel="stylesheet" href="10a_desafio.css">`. Se o nome do arquivo estiver diferente, **o estilo simplesmente não carrega**. 😱

---

## 🧩 Anatomia do HTML

O ponto de partida da aula: um **esqueleto semântico**, onde cada tag tem um papel claro.

```mermaid
graph TD
    A["🌐 body"] --> B["🧢 header<br/>topo do portal"]
    A --> C["📰 main<br/>conteúdo principal"]
    A --> D["🦶 footer<br/>rodapé"]
    C --> E["📄 article<br/>a notícia"]
    C --> F["🧱 section<br/>blocos temáticos"]
    E --> G["📝 h1 · p · strong · em"]
    E --> H["📖 details + summary<br/>Leia mais"]
    F --> I["📺 iframe<br/>vídeo do YouTube"]
    F --> J["📧 form<br/>newsletter"]
    J --> K["input · select · checkbox · button"]

    style A fill:#1e1b4b,stroke:#a78bfa,color:#fff
    style B fill:#312e81,stroke:#a78bfa,color:#fff
    style C fill:#312e81,stroke:#a78bfa,color:#fff
    style D fill:#312e81,stroke:#a78bfa,color:#fff
```

<details>
<summary><b>🧱 Tags de estrutura (o esqueleto semântico)</b></summary>

| Tag | Função | Por que usar em vez de `<div>`? |
|---|---|---|
| `<header>` | Cabeçalho da página ou da seção | Indica o topo e a navegação |
| `<main>` | Conteúdo principal, único por página | Ajuda leitores de tela a pular direto ao essencial |
| `<article>` | Conteúdo independente (uma notícia) | Faz sentido sozinho, até fora da página |
| `<section>` | Agrupamento temático | Organiza o conteúdo em blocos com assunto |
| `<footer>` | Rodapé | Créditos, contatos e informações finais |

</details>

<details>
<summary><b>📝 Tags de texto</b></summary>

| Tag | Função |
|---|---|
| `<h1>` | Título principal da página |
| `<p>` | Parágrafo |
| `<strong>` | Destaque de **forte importância** |
| `<em>` | Ênfase, com sentido de *entonação* |

</details>

<details>
<summary><b>📖 "Leia mais" sem JavaScript 🤯</b></summary>

As tags `<details>` e `<summary>` criam um **bloco que abre e fecha sozinho**, sem nenhuma linha de JavaScript. O `<summary>` é o que fica sempre visível, e o resto do conteúdo aparece ao clicar.

```html
<details>
  <summary>Leia mais</summary>
  <p>Este texto só aparece depois do clique!</p>
</details>
```

> 👀 Você está vendo essa mesma técnica agora: os blocos recolhíveis deste README usam `<details>`!

</details>

<details>
<summary><b>📺 Vídeo do YouTube com <code>iframe</code></b></summary>

O `<iframe>` incorpora outra página dentro da sua. É assim que o vídeo do YouTube aparece **dentro** do portal, sem sair do site.

</details>

<details>
<summary><b>📧 Formulário de newsletter</b></summary>

| Elemento | Para que serve |
|---|---|
| `<input>` | Campo de digitação (nome, e-mail…) |
| `<select>` | Lista de opções para escolher |
| `<input type="checkbox">` | Caixa de marcar (aceite, preferência…) |
| `<button>` | Botão de enviar |

😎 **Bônus:** com o atributo `required`, o próprio navegador avisa *"Preencha este campo."* sozinho, sem JavaScript.

</details>

---

## 🎨 Técnicas de CSS usadas

> 📌 Os trechos abaixo são **exemplos didáticos de cada técnica**, para estudo. O código completo do projeto está em [`10a_desafio.css`](./10a_desafio.css).

<details>
<summary><b>🪟 1. Glassmorphism (vidro fosco)</b></summary>

Efeito de vidro: um **fundo translúcido** combinado com **desfoque** do que está atrás do elemento.

```css
header {
  background: rgba(255, 255, 255, 0.08);   /* fundo semitransparente */
  backdrop-filter: blur(12px);             /* desfoca o que está atrás */
  border: 1px solid rgba(255, 255, 255, 0.15);
}
```

💡 Sem transparência no fundo, o desfoque não aparece. Os dois trabalham juntos.

</details>

<details>
<summary><b>🌈 2. Gradiente no texto</b></summary>

O degradê é aplicado como **fundo** e depois **recortado no formato das letras**.

```css
h1 {
  background: linear-gradient(90deg, #38bdf8, #a78bfa, #f472b6);
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;    /* deixa o texto "vazado" */
}
```

</details>

<details>
<summary><b>🧱 3. CSS Grid</b></summary>

Cria **linhas e colunas** de forma simples. Ideal para colocar o vídeo e a newsletter **lado a lado**.

```css
.duas-colunas {
  display: grid;
  grid-template-columns: 1fr 1fr;          /* duas colunas iguais */
  gap: 24px;                               /* espaço entre elas */
}
```

</details>

<details>
<summary><b>📌 4. Header sticky</b></summary>

O cabeçalho **fica preso no topo** enquanto a página rola.

```css
header {
  position: sticky;
  top: 0;
  z-index: 10;                             /* fica acima do conteúdo */
}
```

</details>

<details>
<summary><b>📱 5. Media query (celular)</b></summary>

Muda o layout quando a tela é pequena. No celular, as duas colunas viram **uma só**.

```css
@media (max-width: 768px) {
  .duas-colunas {
    grid-template-columns: 1fr;            /* uma coluna só */
  }
}
```

</details>

<details>
<summary><b>🏁 Resumo das técnicas</b></summary>

| Técnica | Propriedade-chave | Efeito |
|---|---|---|
| Glassmorphism | `backdrop-filter` | Vidro fosco |
| Texto em degradê | `background-clip: text` | Título colorido |
| Layout em grade | `display: grid` | Colunas organizadas |
| Header fixo | `position: sticky` | Topo acompanha a rolagem |
| Responsividade | `@media` | Adapta ao celular |

</details>

---

## 📱 Layout responsivo

```mermaid
graph LR
    subgraph DESK["🖥️ Desktop"]
        direction TB
        D1["🧢 Header (sticky + vidro fosco)"]
        D2["📰 Notícia + Leia mais"]
        D3["📺 Vídeo"] --- D4["📧 Newsletter"]
        D5["🦶 Footer"]
        D1 --> D2 --> D3
        D2 --> D4
        D3 --> D5
        D4 --> D5
    end
    subgraph MOB["📱 Celular"]
        direction TB
        M1["🧢 Header"]
        M2["📰 Notícia"]
        M3["📺 Vídeo"]
        M4["📧 Newsletter"]
        M5["🦶 Footer"]
        M1 --> M2 --> M3 --> M4 --> M5
    end
    DESK -. "@media" .-> MOB
```

| Elemento | 🖥️ Desktop | 📱 Celular |
|---|---|---|
| Vídeo + Newsletter | Lado a lado | Um embaixo do outro |
| Header | Sticky | Sticky |
| Colunas do grid | 2 | 1 |

---

## 🌈 Paleta de cores

> 🎨 Paleta de referência do tema escuro. Ajuste os valores para os que realmente estão no seu CSS.

| Cor | Hex | Uso sugerido |
|:---:|:---:|---|
| ![](https://img.shields.io/badge/-%20%20%20%20%20-0B0F1A?style=flat-square) | `#0B0F1A` | Fundo da página |
| ![](https://img.shields.io/badge/-%20%20%20%20%20-1E1B4B?style=flat-square) | `#1E1B4B` | Cartões e blocos |
| ![](https://img.shields.io/badge/-%20%20%20%20%20-38BDF8?style=flat-square) | `#38BDF8` | Início do degradê |
| ![](https://img.shields.io/badge/-%20%20%20%20%20-A78BFA?style=flat-square) | `#A78BFA` | Destaques |
| ![](https://img.shields.io/badge/-%20%20%20%20%20-F472B6?style=flat-square) | `#F472B6` | Fim do degradê |
| ![](https://img.shields.io/badge/-%20%20%20%20%20-E5E7EB?style=flat-square) | `#E5E7EB` | Texto principal |

---

## 🚀 Como executar

<details open>
<summary><b>💻 Opção 1 — Clonar e abrir</b></summary>

```bash
# 1. Clone o repositório
git clone https://github.com/SEU-USUARIO/technews-today.git

# 2. Entre na pasta
cd technews-today

# 3. Abra o arquivo no navegador
#    (dê dois cliques em desafio10a.html)
```

</details>

<details>
<summary><b>⚡ Opção 2 — VS Code + Live Server</b></summary>

1. Abra a pasta do projeto no **VS Code**
2. Instale a extensão **Live Server**
3. Clique com o botão direito em `desafio10a.html`
4. Escolha **Open with Live Server**
5. A página recarrega sozinha a cada alteração no CSS 🔄

</details>

<details>
<summary><b>📥 Opção 3 — Baixar o ZIP</b></summary>

1. Clique no botão verde **Code** deste repositório
2. Escolha **Download ZIP**
3. Extraia os arquivos **na mesma pasta** (HTML e CSS juntos!)
4. Abra `desafio10a.html` no navegador

</details>

> ⚠️ **Importante:** os arquivos `desafio10a.html` e `10a_desafio.css` precisam estar **na mesma pasta**, senão o estilo não carrega.

---

## 📤 Como foi a entrega

```mermaid
flowchart LR
    A["1️⃣ Criar repositório<br/>público"] --> B["2️⃣ Subir HTML + CSS"]
    B --> C["3️⃣ Conferir nome<br/>do CSS"]
    C --> D["4️⃣ Copiar link<br/>do repositório"]
    D --> E["5️⃣ Colar na atividade<br/>e clicar em Entregar"]
    E --> F["🏆 100 pontos"]
```

<details>
<summary><b>📋 Checklist antes de entregar</b></summary>

- [x] Repositório está **público**
- [x] `desafio10a.html` foi enviado
- [x] `10a_desafio.css` foi enviado
- [x] O nome do CSS é **idêntico** ao do `<link>` no HTML
- [x] O CSS tem **no máximo 50 linhas**
- [x] O link do repositório foi colado na atividade
- [x] Cliquei em **Entregar** ✅

> 🚨 Só vale o **link do repositório**. Arquivo solto ou print não conta como entrega.

</details>

---

## 🧠 O que aprendi

<details>
<summary><b>🔍 Sobre HTML</b></summary>

- Tags semânticas dão **significado** à página, não só aparência
- `<details>` e `<summary>` fazem um acordeão **sem JavaScript**
- Um `<iframe>` permite incorporar um vídeo do YouTube
- Formulários têm validação nativa do navegador

</details>

<details>
<summary><b>🎨 Sobre CSS</b></summary>

- Dá para criar um visual completo com **poucas linhas** bem pensadas
- `backdrop-filter` só funciona bem com fundo **semitransparente**
- `background-clip: text` transforma o degradê em cor do texto
- CSS Grid simplifica layouts em colunas
- Media queries tornam o site amigável para o celular

</details>

<details>
<summary><b>🐙 Sobre Git e GitHub</b></summary>

- Criar e organizar um repositório público
- Entregar um trabalho por link de repositório
- Documentar um projeto com um bom README

</details>

---

## ❓ Perguntas frequentes

<details>
<summary><b>😱 Abri o HTML e o estilo não carregou. O que houve?</b></summary>

Verifique estes três pontos:

1. O nome do CSS é **exatamente** `10a_desafio.css` (maiúsculas, minúsculas e underline importam)
2. O HTML e o CSS estão **na mesma pasta**
3. O `<link>` dentro do HTML aponta para esse mesmo nome

</details>

<details>
<summary><b>🪟 O efeito de vidro fosco não aparece. E agora?</b></summary>

- Confira se o fundo do header é **semitransparente** (`rgba`)
- Use também o prefixo `-webkit-backdrop-filter` para maior compatibilidade
- Confirme que existe algo **atrás** do header para ser desfocado

</details>

<details>
<summary><b>🚫 Por que não posso usar JavaScript ou frameworks?</b></summary>

O objetivo é **treinar CSS puro** e entender o que o navegador já faz sozinho. O "Leia mais" e a validação do formulário são exemplos de recursos nativos do HTML.

</details>

<details>
<summary><b>📏 Por que o limite de 50 linhas?</b></summary>

Para incentivar um CSS **enxuto e inteligente**: usar seletores certos, agrupar regras e aproveitar bem Grid e propriedades modernas.

</details>

---

## 🔮 Próximos passos

- [ ] 🖼️ Adicionar os prints do projeto na pasta `assets/`
- [ ] 🌗 Experimentar um **tema claro** com `prefers-color-scheme`
- [ ] 🎞️ Testar `transition` em botões e links
- [ ] 🔤 Explorar fontes do Google Fonts
- [ ] ♿ Revisar acessibilidade (contraste e foco do teclado)
- [ ] 🧪 Validar o HTML e o CSS nos validadores da W3C

---

## 🙋 Autor

<div align="center">

### **Vinycius Lopes Monteiro da Silva**
🎓 Estudante de **Desenvolvimento de Sistemas** · **SENAI** · Turma **1ID-DS**

[![GitHub](https://img.shields.io/badge/GitHub-SEU--USUARIO-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SEU-USUARIO)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Perfil-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/SEU-PERFIL)

</div>

### 🙏 Agradecimentos

- 👨‍🏫 Ao professor **André Luis Denani**, pela aula e pelo desafio
- 🏫 Ao **SENAI**, pelo ambiente de aprendizado
- 🤝 À turma **1ID-DS**, pela troca de ideias

---

<div align="center">

⭐ **Gostou do projeto? Deixe uma estrela no repositório!** ⭐

*Projeto educacional desenvolvido na Aula 10 · Desafio CSS TechNews Today*

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,25&height=120&section=footer" alt="Rodapé" />

</div>
