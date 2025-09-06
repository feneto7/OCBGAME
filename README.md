# 🎮 OCB Showdown

Jogo online de Pokémon inspirado no Pokémon Showdown, desenvolvido com Node.js, WebSockets e tecnologias web modernas.

## 🚀 Início Rápido

### Pré-requisitos
- Node.js 14+ 
- npm ou yarn

### Instalação e Execução

1. **Clone o repositório**
```bash
git clone <url-do-repositorio>
cd ocb-showdown
```

2. **Instale as dependências**
```bash
npm install
```

3. **Inicie o servidor de desenvolvimento**
```bash
npm run dev
```

O servidor será iniciado automaticamente e abrirá o navegador em `http://localhost:3000`

## 📁 Estrutura do Projeto

```
OCB Showdown/
├── Assets/                 # Recursos do jogo (imagens, sprites, etc.)
├── Client/                 # Frontend (HTML, CSS, JS)
│   ├── Home/              # Página inicial
│   ├── styles/            # Estilos CSS e Less
│   ├── js/                # Scripts JavaScript
│   └── img/               # Imagens do cliente
├── Server/                # Backend (Node.js, WebSockets)
├── scripts/               # Scripts de desenvolvimento
└── package.json           # Configurações do projeto
```

## 🛠️ Scripts Disponíveis

- `npm run dev` - Inicia servidor de desenvolvimento e abre navegador
- `npm start` - Alias para `npm run dev`
- `npm run build` - Build do projeto (futuro)
- `npm test` - Executa testes (futuro)

## 🎯 Funcionalidades Atuais

### ✅ Implementado
- **Página inicial** com layout responsivo
- **Sistema de navegação** entre páginas
- **Lobby lateral** com lista de usuários online
- **Chat funcional** com envio de mensagens
- **Design responsivo** para mobile e desktop
- **Servidor de desenvolvimento** com auto-reload

### 🚧 Em Desenvolvimento
- Sistema de autenticação
- Team Builder
- Batalhas em tempo real
- Integração com WebSocket
- Sistema de ranking

## 🎨 Design

O jogo utiliza um design moderno e responsivo, inspirado no Pokémon Showdown original, com:
- Paleta de cores vibrantes
- Gradientes e sombras suaves
- Interface intuitiva e acessível
- Layout adaptável para diferentes dispositivos

## 🔧 Tecnologias

### Frontend
- HTML5 semântico
- CSS3 com variáveis e flexbox
- JavaScript ES6+ com classes
- Design responsivo

### Backend (Futuro)
- Node.js
- WebSockets para tempo real
- Express.js para API REST
- Integração com bancos de dados

### Desenvolvimento
- Servidor de desenvolvimento Express
- Auto-reload do navegador
- Scripts de build automatizados

## 📝 Regras de Desenvolvimento

Consulte o arquivo `rules.md` para as regras específicas do projeto, incluindo:
- Padrões de nomenclatura
- Estrutura de código
- Organização de módulos
- Convenções de estilo

## 🤝 Contribuição

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 🎮 Sobre o Jogo

OCB Showdown é um jogo online de Pokémon que permite aos jogadores:
- Construir times de Pokémon
- Batalhar contra outros jogadores
- Participar de torneios
- Conectar-se com a comunidade

---

**Desenvolvido com ❤️ pela equipe OCB Showdown**
