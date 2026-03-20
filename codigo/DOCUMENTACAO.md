# Documentação do Website PixelForge Studios

## Estrutura do Projeto

Este é um website institucional desenvolvido em HTML5 puro para a PixelForge Studios, uma startup de jogos indie.

### Estrutura de Pastas

```
codigo/
├── index.html          # Página principal
├── pagina2.html        # Página "Nossos Jogos"
├── pagina3.html        # Página "Portfólio"
└── img/
    ├── imagem1.jpg     # Imagem do jogo Cyber Quest
    ├── imagem2.jpg     # Imagem do jogo Pixel Dungeon
    └── imagem3.jpg     # Imagem do jogo Space Voyager
```

## Páginas do Website

### 1. index.html - Página Principal

**Estrutura Semântica:**
- `<!DOCTYPE html>` - Declaração do tipo de documento HTML5
- `<html lang="pt-BR">` - Elemento raiz com idioma português brasileiro
- `<head>` - Metadados do documento
  - `<meta charset="UTF-8">` - Codificação de caracteres
  - `<meta name="viewport">` - Configuração de visualização responsiva
  - `<title>` - Título da página
- `<body>` - Conteúdo visível da página

**Elementos Semânticos:**
- `<header>` - Cabeçalho do site
  - `<h1>` - Nome da empresa: "PixelForge Studios"
  - `<h3>` - Slogan: "Criando mundos digitais, um pixel de cada vez"
  - `<nav>` - Menu de navegação
    - `<ul>` - Lista não ordenada de links
    - `<li>` - Itens da lista com links para outras páginas
- `<main>` - Conteúdo principal
  - `<section>` - Seção 1: Apresentação
    - `<h2>` - Título da seção
    - `<h3>` - Dois parágrafos de texto sobre a empresa
  - `<section>` - Seção 2: Diferenciais
    - `<h2>` - Título da seção
    - `<ul>` - Lista não ordenada com 4 diferenciais
- `<footer>` - Rodapé
  - `<h3>` - Informações de contato
  - `<h3>` - Direitos autorais

### 2. pagina2.html - Nossos Jogos

**Estrutura:** Header e Nav idênticos à página principal

**Conteúdo Principal:**
- `<h1>` - Título principal: "Nossos Jogos"
- `<table>` - Tabela estruturada de jogos
  - `<thead>` - Cabeçalho da tabela
    - `<tr>` - Linha do cabeçalho
    - `<th>` - Células de cabeçalho: Item, Descrição, Duração/Data, Valor/Investimento
  - `<tbody>` - Corpo da tabela
    - `<tr>` - Linhas de dados (3 jogos)
    - `<td>` - Células de dados com informações dos jogos

**Jogos Listados:**
1. **Cyber Quest** - RPG de ação futurista (2025) - R$ 49,90
2. **Pixel Dungeon** - Roguelike pixel art (2024) - R$ 29,90
3. **Space Voyager** - Jogo de estratégia espacial (2026) - R$ 59,90

### 3. pagina3.html - Portfólio

**Estrutura:** Header e Nav idênticos às outras páginas

**Conteúdo Principal:**
- `<h1>` - Título principal: "Portfólio"
- `<img>` - Três imagens ilustrativas
  - `src="img/imagem1.jpg"` - Imagem do Cyber Quest
  - `src="img/imagem2.jpg"` - Imagem do Pixel Dungeon
  - `src="img/imagem3.jpg"` - Imagem do Space Voyager
  - `alt` - Atributos alternativos descritivos para acessibilidade
- `<h3>` - Descrições abaixo de cada imagem

## Elementos HTML5 Utilizados

### Estruturais
- `<!DOCTYPE html>`
- `<html>`
- `<head>`
- `<body>`

### Semânticos
- `<header>` - Cabeçalho do site
- `<nav>` - Navegação
- `<main>` - Conteúdo principal
- `<section>` - Seções de conteúdo
- `<footer>` - Rodapé

### Conteúdo
- `<h1>`, `<h2>`, `<h3>` - Hierarquia de títulos
- `<ul>` - Lista não ordenada
- `<li>` - Itens de lista
- `<table>` - Tabela de dados
- `<thead>` - Cabeçalho da tabela
- `<tbody>` - Corpo da tabela
- `<tr>` - Linhas da tabela
- `<th>` - Células de cabeçalho
- `<td>` - Células de dados
- `<img>` - Imagens
- `<a>` - Links de navegação

## Requisitos Técnicos Atendidos

✅ **HTML5 Semântico:** Uso correto de elementos semânticos
✅ **Hierarquia de Títulos:** Estrutura h1 > h2 > h3
✅ **Lista Não Ordenada:** Implementada com `<ul>` e `<li>`
✅ **Tabela Estruturada:** Completa com `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`
✅ **Imagens com Atributo alt:** Todas as imagens possuem descrição alternativa
✅ **Links Funcionais:** Navegação entre as três páginas
✅ **Organização de Imagens:** Pasta `/img` com arquivos nomeados
✅ **Código Indentado:** Formatação legível e organizada
✅ **Sem CSS/JavaScript:** Apenas HTML5 puro conforme especificação

## Acessibilidade

- **Lang Attribute:** `<html lang="pt-BR">` define o idioma do conteúdo
- **Alt Attributes:** Todas as imagens possuem texto alternativo descritivo
- **Hierarquia Semântica:** Uso adequado de elementos HTML5 para estrutura
- **Navegação por Teclado:** Links funcionais sem dependência de JavaScript

## Navegação

O sistema de navegação é consistente em todas as páginas:
- **Home:** `index.html`
- **Nossos Jogos:** `pagina2.html`
- **Portfólio:** `pagina3.html`

## Conteúdo Temático

**PixelForge Studios** é apresentada como:
- Startup de desenvolvimento de jogos indie
- Foco em PC e mobile
- Equipes ágeis e produtos de alta qualidade
- Três jogos principais em portfólio diversificado

## Validação

O código segue as especificações HTML5 e está pronto para validação em ferramentas como o W3C Validator.
