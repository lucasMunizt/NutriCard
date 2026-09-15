# NutriCard - Gerenciamento de Refeições e Informações Nutricionais

Este é o **frontend** do projeto NutriCard, uma aplicação voltada para o gerenciamento de refeições e informações nutricionais. O objetivo do sistema é permitir que os usuários possam registrar suas refeições, acompanhar os dados nutricionais dos alimentos e monitorar o consumo diário de calorias e nutrientes.

🔗 Confira o repositório do [Backend](https://github.com/SenaVitor/nutricard) para complementar este projeto.
📱 Confira o repositório do [Frontend Mobile](https://github.com/lucasMunizt/NutriCard-aplicativo/tree/master) para complementar este projeto.

## ⚙️ Funcionalidades

* **Cadastro de alimentos**: Insira informações nutricionais detalhadas dos alimentos por grama.
* **Gerenciamento de refeições**: Registre refeições associando alimentos, datas e quantidades.
* **Cálculo de nutrientes**: Visualize automaticamente as calorias, gorduras, carboidratos, sódio, fibras e proteínas consumidas em cada refeição.
* **Favoritos**: Mantenha uma lista de alimentos favoritos para acesso rápido.
* **Controle diário**: Acompanhe o consumo diário de nutrientes e calorias através de um calendário interativo.

## 🛠️ Tecnologias Utilizadas

* [React](https://react.dev/) — Biblioteca para construção da interface.
* [Vite](https://vitejs.dev/) — Ferramenta de build e desenvolvimento.
* [React Router DOM](https://reactrouter.com/) — Roteamento entre páginas da aplicação.
* [Bootstrap](https://getbootstrap.com/) e [Bootstrap Icons](https://icons.getbootstrap.com/) — Estilização e componentes visuais.
* [React Modal](https://www.npmjs.com/package/react-modal) — Exibição de modais.
* [React Big Calendar](https://www.npmjs.com/package/react-big-calendar) — Calendário para controle das refeições e consumo diário.
* [Moment.js](https://momentjs.com/) — Manipulação de datas (com localização em pt-br).
* [Swiper](https://swiperjs.com/) — Carrosséis e sliders interativos.
* JavaScript (ES6+) — Linguagem utilizada.

## 🚀 Como Executar o Projeto

### Pré-requisitos

* [Node.js](https://nodejs.org/) (versão 16 ou superior)
* Gerenciador de pacotes npm ou yarn
* Backend do [NutriCard](https://github.com/SenaVitor/nutricard) rodando (para consumo da API)

### Configuração

1. Clone o repositório:

```bash
git clone https://github.com/lucasMunizt/NutriCard.git
```

2. Entre na pasta do projeto:

```bash
cd NutriCard
```

3. Instale as dependências:

```bash
npm install
```

4. Rode o projeto em ambiente de desenvolvimento:

```bash
npm run dev
```

5. Acesse a aplicação no navegador através do endereço exibido no terminal (geralmente `http://localhost:5173`).

## 📁 Estrutura do Projeto

```
NutriCard/
├── public/          # Arquivos estáticos
├── src/             # Código-fonte da aplicação (componentes, páginas, estilos, etc.)
├── index.html        # Arquivo HTML principal
├── package.json       # Dependências e scripts do projeto
└── vite.config.js      # Configuração do Vite
```
## 📄 Licença

Este projeto está disponível para fins de estudo e aprendizado.
