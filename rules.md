# Regras do Projeto OCB Showdown

## Estrutura do Projeto
- **Assets**: Recursos do jogo (imagens, sprites, etc.)
- **Server**: Node.js (JS/TS), WebSockets, JSON/arquivos, integrações com bancos
- **Client**: HTML, CSS (Less), JS/TS, WebSocket

## Regras de Desenvolvimento

### Idioma e Nomenclatura
- **Sempre responder em português**
- **Todas as variáveis e funções devem ser em inglês**
- **Comentários, labels e interface para o usuário em português**
- **Pastas, arquivos e variáveis em inglês**

### Organização do Código
- Evitar duplicidades de código
- Manter estrutura organizada e código limpo
- Adicionar comentários resumidos e naturais
- Usar arquivo global (styles/shared.ts) para estilos compartilhados
- Respeitar o framework utilizado e não mudar o padrão
- Formatar campos de valores para formato de moeda sempre

### Modulação
- Separar componentes reutilizáveis
- Criar módulos independentes e coesos
- Implementar interfaces claras entre módulos
- Evitar dependências circulares
- Usar padrões de design apropriados (MVC, MVVM, etc.)
- Implementar injeção de dependência quando apropriado
- Manter módulos pequenos e focados

### Estrutura de Páginas
- Cada página terá sua pasta com arquivos descritivos
- Exemplo: Home/Home.html, Home/Home.css, Home/Home.js
- As rotas estão definidas em app.js
- Cada página deve ter seus próprios arquivos CSS e JS específicos
- Estilos globais ficam na pasta styles/
- Scripts globais ficam na pasta js/

### Layout Principal
- Página dividida em 2 DIVs principais
- DIV da direita: Lobby (fixo, nunca sai da tela)
- DIV da esquerda: Renderização das páginas (muda conforme navegação)
- Topbar fina no topo com logo no canto esquerdo
- Conteúdo da esquerda deve parar exatamente onde o lobby começa (300px da direita)
- Lobby fixo de 300px de largura na lateral direita
- Topbar com altura de 50px

### Lobby
- Primeira parte: Lista de usuários online
- Meio: Chat
- Parte inferior: Campo para digitar mensagem
- Lobby deve ser sempre fixo na lateral direita
- Usuários online com indicadores visuais de status
- Chat com timestamps relativos (agora, 5m, 2h, etc.)
- Sistema de envio de mensagens com Enter ou botão

## Tecnologias
- **Frontend**: HTML, CSS (Less), JavaScript/TypeScript, WebSocket
- **Backend**: Node.js, WebSockets, JSON/arquivos
- **Infraestrutura**: Scripts customizados + GitHub Actions + Docker

## Padrões de Desenvolvimento

### Estrutura de Arquivos
- **Client/index.html** - Página principal com layout dividido
- **Client/styles/** - Estilos globais e compartilhados
- **Client/js/** - Scripts globais da aplicação
- **Client/Home/** - Página inicial com seus arquivos específicos
- **Client/Lobby/** - Página do lobby com seus arquivos específicos
- **Client/img/** - Imagens e recursos visuais

### Nomenclatura de Arquivos
- **Páginas**: NomeDaPagina.html, NomeDaPagina.css, NomeDaPagina.js
- **Estilos globais**: main.css, topbar.css, lobby.css
- **Scripts globais**: app.js, navigation.js, lobby.js
- **Recursos**: shared.ts para utilitários e variáveis

### Desenvolvimento Local
- **Comando**: `npm run dev` para iniciar servidor de desenvolvimento
- **Porta padrão**: 3000
- **Abertura automática**: Navegador abre automaticamente
- **Hot reload**: Atualizações em tempo real

### Responsividade
- **Mobile first**: Design responsivo para todos os dispositivos
- **Breakpoints**: 768px para mobile, 1024px para tablet
- **Lobby mobile**: Em telas pequenas, lobby fica abaixo do conteúdo
- **Topbar adaptável**: Elementos se ajustam ao tamanho da tela

### Performance
- **Carregamento modular**: Cada página carrega apenas seus arquivos
- **CSS otimizado**: Estilos específicos separados dos globais
- **JS modular**: Scripts organizados por funcionalidade
- **Imagens otimizadas**: Recursos visuais em formato adequado
