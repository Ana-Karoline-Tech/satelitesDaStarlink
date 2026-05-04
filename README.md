# 🛰️ Starlink Satellite Tracker

Um rastreador em tempo real dos satélites Starlink, utilizando dados oficiais da SpaceX e visualização interativa em mapa-múndi.

## 🚀 Sobre o Projeto

Este projeto é uma aplicação web desenvolvida com **React** e **Leaflet** que consome a API da SpaceX para exibir a localização atual da constelação de satélites Starlink. O objetivo é fornecer uma interface visual e intuitiva para monitorar a posição dos satélites em órbita.

## ✨ Funcionalidades

- **Mapa Mundial Interativo:** Visualização em tempo real de satélites sobre um mapa temático (Dark Mode).
- **Dados Reais:** Integração direta com a API da SpaceX (`/v4/starlink`).
- **Estatísticas ao Vivo:** Contador de satélites totais vs. satélites com posição rastreável.
- **Paginação Dinâmica:** Carregamento sob demanda de mais satélites para otimização de performance.
- **Interface Futurista:** UI estilizada com temática espacial e elementos visuais modernos.

## 🛠️ Tecnologias Utilizadas

- [React 19](https://react.dev/) - Biblioteca JavaScript para construção de interfaces.
- [Vite](https://vitejs.dev/) - Build tool ultra-rápida.
- [Leaflet](https://leafletjs.com/) & [React-Leaflet](https://react-leaflet.js.org/) - Mapas interativos.
- [SpaceX API](https://github.com/r-spacex/SpaceX-API) - Fonte de dados dos satélites.
- [Vanilla CSS] - Estilização personalizada.

## 🏁 Como Rodar o Projeto

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/satelites-starlink.git
   ```

2. **Instale as dependências:**
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento:**
   ```bash
   npm run dev
   ```

4. **Acesse no navegador:**
   O projeto estará rodando em `http://localhost:5173`.

---
Desenvolvido como projeto de estudo sobre React e integração de APIs.
