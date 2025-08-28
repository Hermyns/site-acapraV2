# Estrutura das Seções - Site ACAPRA

Este documento detalha cada seção do site e seus respectivos arquivos CSS, conforme solicitado.

## 📋 Mapeamento Seção → CSS

### 1. **Header (Cabeçalho)**
- **Arquivo CSS**: `css/header.css`
- **Elementos**:
  - Logo ACAPRA com ícone de pata
  - Menu de navegação horizontal
  - Menu mobile responsivo (hamburger)
  - Efeito de scroll no header
- **Funcionalidades**:
  - Header fixo no topo
  - Transparência ao rolar
  - Animações de hover nos links
  - Menu mobile com toggle

### 2. **Home Section (Seção Inicial)**
- **Arquivo CSS**: `css/home.css`
- **Elementos**:
  - Hero section com gradiente roxo
  - Título "ACAPRA" centralizado
  - Subtítulo "Associação de Proteção aos Animais"
  - Grid de 6 cards de animais
  - Botões "Adotar" em cada card
- **Funcionalidades**:
  - Animações de entrada escalonadas
  - Hover effects nos cards
  - Layout responsivo em grid
  - Efeitos de zoom nas imagens

### 3. **Info Maus Tratos Section**
- **Arquivo CSS**: `css/info-maus-tratos.css`
- **Elementos**:
  - Título da seção
  - Layout em duas colunas (texto + imagem)
  - Informações sobre legislação
  - Caixas de destaque
  - Botões de call-to-action
- **Funcionalidades**:
  - Hover effects nas imagens
  - Botões com animações
  - Layout responsivo
  - Caixas de destaque coloridas

### 4. **História e Missão Section**
- **Arquivo CSS**: `css/historia-missao.css`
- **Elementos**:
  - Grid de duas colunas (texto + imagens)
  - Lista de missões com ícones
  - Cards de missão
  - Timeline de eventos
  - Barra lateral colorida
- **Funcionalidades**:
  - Animações na timeline
  - Hover effects nos cards de missão
  - Lista interativa com ícones de pata
  - Layout adaptativo

### 5. **Doação Section**
- **Arquivo CSS**: `css/doacao.css`
- **Elementos**:
  - Background com gradiente roxo
  - Cards de opções de doação (PIX, Transferência, Físicas)
  - Seção PIX com código
  - Botão de copiar
  - Seção de impacto das doações
  - Call-to-action principal
- **Funcionalidades**:
  - Background animado com padrões
  - Cards com hover effects
  - Botão de copiar PIX
  - Animações de entrada
  - Layout responsivo

### 6. **Histórias de Animais Section**
- **Arquivo CSS**: `css/historias-animais.css`
- **Elementos**:
  - Grid de cards de histórias
  - Badges de status (adotado, disponível, tratamento)
  - Botões "Ler mais"
  - Filtros por categoria
  - Modal para histórias completas
  - Barra de progresso
- **Funcionalidades**:
  - Sistema de filtros
  - Modal interativo
  - Badges coloridos por status
  - Animações de progresso
  - Cards com hover effects

### 7. **Estatísticas Section**
- **Arquivo CSS**: `css/estatisticas.css`
- **Elementos**:
  - Background com gradiente roxo
  - Cards de estatísticas com números grandes
  - Gráfico de barras animado
  - Anéis de progresso
  - Seção de comparação
  - Ícones e elementos visuais
- **Funcionalidades**:
  - Animação de contadores
  - Gráficos animados
  - Anéis de progresso SVG
  - Background com padrões
  - Hover effects nos cards

### 8. **Notícias Section**
- **Arquivo CSS**: `css/noticias.css`
- **Elementos**:
  - Grid de cards de notícias
  - Artigo em destaque
  - Badges de categoria
  - Seção de newsletter
  - Controles de busca e filtro
  - Paginação
- **Funcionalidades**:
  - Sistema de busca
  - Filtros por categoria
  - Newsletter signup
  - Paginação interativa
  - Cards com hover effects

### 9. **Footer (Rodapé)**
- **Arquivo CSS**: `css/footer.css`
- **Elementos**:
  - Background escuro com gradiente
  - Grid de informações (3-4 colunas)
  - Links sociais circulares
  - Informações de contato com ícones
  - Newsletter signup
  - Call-to-action de doação
  - Botão "voltar ao topo"
- **Funcionalidades**:
  - Links sociais com hover effects
  - Botão voltar ao topo animado
  - Newsletter form
  - Background com padrões
  - Layout responsivo

## 🎨 Arquivos CSS Globais

### `css/reset.css`
- Reset básico de estilos
- Normalização entre navegadores
- Box-sizing border-box global

### `css/global.css`
- Variáveis CSS (cores, espaçamentos, etc.)
- Tipografia base (fonte Inter)
- Classes utilitárias
- Estilos de botões globais
- Grid layouts responsivos
- Animações keyframes
- Media queries base

## 📱 Responsividade por Seção

Cada arquivo CSS inclui media queries específicas:

### Mobile (max-width: 480px)
- Grids colapsam para 1 coluna
- Padding reduzido
- Fontes menores
- Botões full-width

### Tablet (max-width: 768px)
- Grids adaptados para 2 colunas
- Menu mobile ativado
- Espaçamentos ajustados
- Imagens redimensionadas

### Desktop (769px+)
- Layout completo
- Hover effects ativos
- Grids em múltiplas colunas
- Espaçamentos máximos

## 🔧 Customização por Seção

### Para alterar cores de uma seção específica:
1. Abra o arquivo CSS correspondente
2. Modifique as variáveis CSS utilizadas
3. Ou sobrescreva com cores específicas

### Para alterar layout:
1. Modifique as propriedades grid/flexbox
2. Ajuste os media queries
3. Teste em diferentes tamanhos de tela

### Para adicionar animações:
1. Use as classes existentes (.fade-in-up, etc.)
2. Ou crie novas animações no arquivo específico
3. Aplique via JavaScript se necessário

## 📝 Manutenção

### Adicionando nova seção:
1. Crie novo arquivo CSS na pasta `css/`
2. Adicione link no `<head>` do HTML
3. Siga o padrão de nomenclatura existente
4. Use as variáveis globais para consistência

### Modificando seção existente:
1. Identifique o arquivo CSS correspondente
2. Faça as alterações necessárias
3. Teste responsividade
4. Verifique compatibilidade entre navegadores

---

**Cada seção foi cuidadosamente desenvolvida para ser independente e facilmente customizável!**

