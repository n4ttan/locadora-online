# 🎬 Corujão Flix — Locadora Online

Site de **locadora / streaming de filmes** desenvolvido com HTML, CSS e Bootstrap. O projeto simula a experiência de uma plataforma de filmes, com catálogo, páginas individuais para cada título, trailers e trilhas sonoras.

## ✨ Funcionalidades

- **Catálogo de filmes** com páginas dedicadas para cada título
- **Trailers** em vídeo para os filmes disponíveis
- **Trilha sonora** de cada filme (faixas de áudio)
- **Wallpapers** e artes de cada título
- Páginas de **contato**, **sobre** e navegação entre seções
- Layout responsivo com fundo desfocado (blur overlay) e cabeçalho fixo

## 🎞️ Títulos no catálogo

Entre os filmes incluídos estão: *Annabelle 3*, *Clube da Luta*, *Cães de Guerra*, *Interestelar*, *John Wick 4*, *O Lobo de Wall Street*, *O Grande Gatsby* e *O Jogo da Imitação*.

## 🛠️ Tecnologias

- **HTML5** — estrutura das páginas
- **CSS3** — estilização, efeitos de blur e layout
- **Bootstrap 5.3** — componentes e grid responsivo (via CDN)
- **Mídia** — vídeos (`.mp4`), áudios (`.mp3`) e imagens

## 🚀 Como rodar

Projeto estático, sem build:

```bash
git clone https://github.com/n4ttan/locadora-online.git
cd locadora-online
```

Abra `index.html` (ou `paginaInicial.html`) no navegador, ou sirva localmente:

```bash
python -m http.server 8000
# acesse http://localhost:8000
```

## 📁 Estrutura

```
locadora-online/
├── index.html          → página de entrada
├── paginaInicial.html  → página inicial / home
├── filmes.html         → catálogo de filmes
├── trailers.html       → trailers
├── trilhaSonora.html   → trilhas sonoras
├── contato.html        → página de contato
├── sobre.html          → sobre o projeto
├── sair.html           → tela de saída
├── images/             → logos e imagens da interface
└── Filmes/             → uma pasta por filme (vídeo, áudio, wallpaper, página)
```

## 📝 Sobre

Projeto educacional de front-end que recria a interface de uma locadora de filmes online, com foco em layout, organização de mídia e navegação entre páginas.
