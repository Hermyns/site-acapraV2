# Site ACAPRA - Associação de Proteção aos Animais

Este projeto foi desenvolvido baseado no design do Figma fornecido, transformando-o em um site HTML/CSS totalmente funcional e responsivo.

## 📋 Sobre o Projeto

O site da ACAPRA (Associação Campinense de Proteção aos Animais) foi criado para promover a adoção responsável de animais, conscientizar sobre maus tratos e facilitar doações para a organização.

## 🎨 Design

O design foi baseado no projeto Figma fornecido, mantendo:
- Paleta de cores roxa/violeta (#6B46C1) como cor principal
- Layout responsivo e moderno
- Seções bem definidas para cada tipo de conteúdo
- Interface intuitiva e acessível

## 📁 Estrutura do Projeto

```
site-acapra/
├── index.html              # Página principal
├── css/                    # Arquivos de estilo
│   ├── reset.css          # Reset CSS
│   ├── global.css         # Estilos globais e variáveis
│   ├── header.css         # Estilos do cabeçalho
│   ├── home.css           # Estilos da seção inicial
│   ├── info-maus-tratos.css # Estilos da seção de informações
│   ├── historia-missao.css  # Estilos da seção história e missão
│   ├── doacao.css         # Estilos da seção de doação
│   ├── historias-animais.css # Estilos das histórias de animais
│   ├── estatisticas.css   # Estilos da seção de estatísticas
│   ├── noticias.css       # Estilos da seção de notícias
│   └── footer.css         # Estilos do rodapé
├── js/                    # Arquivos JavaScript
│   └── main.js           # Funcionalidades interativas
├── images/               # Pasta para imagens
└── README.md            # Este arquivo
```

## 🚀 Seções do Site

### 1. **Home (Página Inicial)**
- Hero section com gradiente roxo
- Galeria de animais disponíveis para adoção
- Cards interativos com hover effects
- Layout responsivo em grid

### 2. **Informações sobre Maus Tratos**
- Informações sobre legislação brasileira
- Layout em duas colunas (texto + imagem)
- Call-to-action para denúncias
- Design educativo e informativo

### 3. **História e Missão**
- História da ACAPRA
- Missão e objetivos da organização
- Lista de atividades e serviços
- Timeline de conquistas

### 4. **Doação**
- Múltiplas formas de doação (PIX, transferência, físicas)
- Seção de impacto das doações
- Call-to-action destacado
- Informações bancárias organizadas

### 5. **Histórias de Animais**
- Cards com histórias de resgate
- Sistema de filtros por categoria
- Modal para histórias completas
- Badges de status (adotado, disponível, tratamento)

### 6. **Estatísticas**
- Números da ACAPRA com animações
- Gráficos interativos
- Comparações anuais
- Visualização de dados atrativa

### 7. **Notícias**
- Grid de notícias e eventos
- Sistema de busca e filtros
- Newsletter signup
- Paginação

## 🎯 Funcionalidades

### Interatividade
- Menu mobile responsivo
- Smooth scrolling entre seções
- Animações on scroll
- Botão "voltar ao topo"
- Hover effects em cards e botões

### Responsividade
- Design mobile-first
- Breakpoints para tablet e desktop
- Grid layouts adaptativos
- Imagens responsivas

### Acessibilidade
- Estrutura semântica HTML5
- Contraste adequado de cores
- Navegação por teclado
- Labels e alt texts apropriados

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com Flexbox e Grid
- **JavaScript**: Interatividade e animações
- **Google Fonts**: Tipografia (Inter)
- **CSS Variables**: Sistema de cores consistente

## 📱 Responsividade

O site é totalmente responsivo com breakpoints:
- **Mobile**: até 480px
- **Tablet**: 481px - 768px
- **Desktop**: 769px+

## 🎨 Paleta de Cores

```css
--primary-color: #6B46C1;     /* Roxo principal */
--primary-dark: #553C9A;      /* Roxo escuro */
--primary-light: #8B5CF6;     /* Roxo claro */
--secondary-color: #EC4899;   /* Rosa */
--accent-color: #F59E0B;      /* Amarelo/Laranja */
--text-dark: #1F2937;         /* Texto escuro */
--text-light: #6B7280;        /* Texto claro */
```

## 🚀 Como Usar

1. **Visualização Local**:
   - Abra o arquivo `index.html` em qualquer navegador moderno
   - Todas as funcionalidades funcionam offline

2. **Hospedagem**:
   - Faça upload de todos os arquivos para seu servidor web
   - Certifique-se de manter a estrutura de pastas

3. **Personalização**:
   - Edite as variáveis CSS em `global.css` para alterar cores
   - Substitua as imagens na pasta `images/`
   - Modifique o conteúdo no `index.html`

## 📝 Customização

### Alterando Cores
Edite as variáveis CSS no arquivo `css/global.css`:

```css
:root {
    --primary-color: #SUA_COR_AQUI;
    /* ... outras variáveis */
}
```

### Adicionando Imagens
1. Coloque as imagens na pasta `images/`
2. Atualize os caminhos no HTML
3. Mantenha proporções adequadas para melhor visualização

### Modificando Conteúdo
- Textos: Edite diretamente no `index.html`
- Estilos: Modifique os arquivos CSS correspondentes
- Funcionalidades: Ajuste o `main.js`

## 🔧 Manutenção

- **Imagens**: Otimize imagens para web (WebP recomendado)
- **Performance**: Minifique CSS e JS para produção
- **SEO**: Adicione meta tags apropriadas
- **Analytics**: Integre Google Analytics se necessário

## 📞 Suporte

Para dúvidas ou sugestões sobre o código:
- Verifique a documentação nos comentários do código
- Teste em diferentes navegadores
- Valide HTML e CSS com ferramentas online

## 📄 Licença

Este projeto foi desenvolvido especificamente para a ACAPRA baseado no design Figma fornecido.

---

**Desenvolvido com ❤️ para a proteção animal**

