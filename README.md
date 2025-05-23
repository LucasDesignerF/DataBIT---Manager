# DataBIT - Manager

![GitHub repo size](https://img.shields.io/github/repo-size/LucasDesignerF/DataBIT---Manager?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/LucasDesignerF/DataBIT---Manager?style=for-the-badge)
![License](https://img.shields.io/github/license/LucasDesignerF/DataBIT---Manager?style=for-the-badge)
![React](https://img.shields.io/badge/React-18.2.0-61DAFB?style=for-the-badge&logo=react)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-3.4.1-38B2AC?style=for-the-badge&logo=tailwind-css)

**DataBIT - Manager** é uma interface web moderna e avançada para gerenciar aplicações hospedadas na [Discloud](https://discloud.app). Inspirada no design do Discord, a aplicação oferece uma experiência fluida com tema escuro, animações suaves, e respostas em embeds estilizados. Com suporte a todas as principais rotas da API da Discloud, você pode gerenciar suas aplicações com facilidade, desde upload até administração avançada.

## 📖 Sobre o Projeto

DataBIT - Manager permite que desenvolvedores controlem suas aplicações na Discloud de forma intuitiva. A interface utiliza uma navbar superior, cards interativos, e um sistema de mensagens em embeds para feedback em tempo real. Com telas de carregamento, animações, e suporte a ações como iniciar, parar, reiniciar, alterar RAM, fazer commits, e excluir aplicações, o projeto é ideal para quem busca uma ferramenta poderosa e visualmente atraente.

## 🚀 Funcionalidades

- **Gerenciamento de Usuário**: Visualize ID, plano, RAM usada/total, e mais.
- **Upload de Aplicações**: Envie arquivos ZIP para criar novas aplicações.
- **Lista de Aplicações**: Veja todas as aplicações com nome, ID, status, e RAM.
- **Detalhes da Aplicação**:
  - Informações completas (tipo, linguagem, arquivo principal, etc.).
  - Status em tempo real (CPU, memória, SSD, rede).
  - Logs (formato reduzido ou completo).
  - Download de backups.
- **Administração Avançada**:
  - Iniciar, reiniciar, ou parar aplicações.
  - Alterar a quantidade de RAM (mínimo 100 MB).
  - Fazer commits de atualizações via ZIP.
  - Excluir aplicações com confirmação.
- **Interface Moderna**:
  - Tema escuro inspirado no Discord (cores #2F3136, #36393F, #5865F2, #57F287).
  - Animações suaves (fade-ins, hover effects, transições).
  - Telas de carregamento (spinners) para uploads, commits, e requisições.
  - Mensagens de feedback em embeds estilizados (sucesso, erro, informação).
- **Responsividade**: Layout adaptável para desktops e dispositivos móveis.

## 🛠️ Pré-requisitos

- Navegador moderno (Chrome, Firefox, Edge, etc.).
- Conexão com a internet para acessar a API da Discloud.
- Uma API Key válida da Discloud (obtenha em [discloud.app](https://discloud.app)).

## 📦 Instalação

1. **Clone o Repositório**:
   ```bash
   git clone https://github.com/LucasDesignerF/DataBIT---Manager.git
   cd DataBIT---Manager
   ```

2. **Abra o Projeto**:
   - Como o projeto é uma aplicação web estática, não requer dependências adicionais.
   - Abra o arquivo `index.html` diretamente em um navegador:
     ```bash
     open index.html  # Mac/Linux
     start index.html # Windows
     ```

3. **(Opcional) Servidor Local**:
   - Para desenvolvimento, use um servidor local como `live-server`:
     ```bash
     npm install -g live-server
     live-server
     ```

## 🎮 Como Usar

1. **Acesse a Interface**:
   - Abra `index.html` no navegador ou acesse via servidor local.
2. **Insira a API Key**:
   - Na navbar superior, digite sua API Key da Discloud no campo fornecido.
3. **Navegue pelas Funcionalidades**:
   - **Usuário**: Veja informações do seu plano e uso de RAM.
   - **Upload**: Envie um arquivo ZIP para criar uma nova aplicação (spinner durante upload).
   - **Aplicações**: Liste todas as aplicações e clique em "Ver Detalhes" para gerenciar.
   - **Detalhes da Aplicação**: Controle a aplicação com botões para iniciar, parar, reiniciar, alterar RAM, fazer commit, ou excluir.
4. **Feedback**:
   - Todas as ações exibem embeds de sucesso (verde), erro (vermelho), ou informação (azul) no canto superior direito.
   - Embeds desaparecem automaticamente após 5 segundos.

## 🧑‍💻 Tecnologias Utilizadas

- **React**: 18.2.0 (via CDN) - Biblioteca para construção da interface.
- **Tailwind CSS**: 3.4.1 (via CDN) - Estilização responsiva e moderna.
- **Boxicons**: 2.1.4 (via CDN) - Ícones para ações e navegação.
- **Animate.css**: 4.1.1 (via CDN) - Animações de fade-in e transições.
- **JavaScript (ES6)**: Lógica da aplicação e integração com a API.
- **Discloud API**: v2 - Backend para gerenciamento de aplicações.

## 🤝 Contribuição

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. **Fork o Repositório**:
   - Clique em "Fork" no GitHub.
2. **Crie uma Branch**:
   ```bash
   git checkout -b feature/nova-funcionalidade
   ```
3. **Faça suas Alterações**:
   - Adicione commits com mensagens claras.
4. **Envie um Pull Request**:
   - Descreva suas mudanças e envie para revisão.
5. **Siga as Diretrizes**:
   - Mantenha o código limpo e documentado.
   - Teste localmente antes de enviar.

## 📝 Licença

Este projeto está licenciado sob a [MIT License](LICENSE).

## 📬 Contato

- **Autor**: LucasDesignerF
- **GitHub**: [LucasDesignerF](https://github.com/LucasDesignerF)
- **Repositório**: [DataBIT - Manager](https://github.com/LucasDesignerF/DataBIT---Manager)
- **Issues**: Abra uma [issue](https://github.com/LucasDesignerF/DataBIT---Manager/issues) para reportar bugs ou sugerir melhorias.

---

⭐ **Gostou do projeto? Dê uma estrela no GitHub!**
