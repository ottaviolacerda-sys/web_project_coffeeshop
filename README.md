# ☕ Coffee Coding - Triple Peaks Coffee Shop

**Coffee Coding** é uma landing page moderna e responsiva para a _Triple Peaks_, uma cafeteria especializada que combina a paixão por café de alta qualidade com um ambiente acolhedor, ideal para estudos e trabalho. O projeto simula uma experiência completa de usuário, desde a apresentação da marca até a reserva de mesas e descoberta de receitas de café.

## 🚀 Funcionalidades e Tecnologias

O projeto é construído com as tecnologias fundamentais da web, sem dependências de frameworks externos para garantir performance e aprendizado sólido.

- **Estrutura Semântica:** Uso correto de tags HTML5 como `<header>`, `<nav>`, `<main>`, `<section>`, e `<footer>` para melhor acessibilidade e SEO.
- **Estilização Moderna (CSS3):**
  - **Layout com Flexbox:** Para alinhamento e distribuição de elementos no `nav`, `header`, `footer` e formulários.
  - **Design Responsivo:** A página se adapta a diferentes tamanhos de tela.
  - **Tipografia Híbrida:** Combinação das fontes `Inter` (para UI moderna) e `Noto Serif` (para títulos elegantes e descrições).
  - **Variáveis de Cores:** Uso consistente da paleta de cores (azul `#0a2850`, acento `#2f80ed`, fundo `#d9e7ff`).
- **Interatividade:**
  - Formulário de reserva funcional (frontend) com validação HTML5 (`required`, `min`, `max`, `type="email"`).
  - Botões e links com estados de `:hover` para feedback visual.
  - Incorporação de vídeos do YouTube para receitas de café (Aeropress e Prensa Francesa).
- **Acessibilidade e SEO:**
  - Meta tags de descrição e palavras-chave otimizadas.
  - Atributos `alt` em todas as imagens.
  - Foco em contraste e legibilidade.

## 📂 Estrutura do Projeto

- `index.html`: Conteúdo principal da página.
- `pages/index.css`: Estilos completos da aplicação.
- `images/`: Pasta para logotipos, ícones sociais e imagens de fundo.
- `favicon.ico`: Ícone da aba do navegador.

## 🎨 Design e UX

- **Header Hero:** Destaque visual com título em itálico e imagem de fundo da cafeteria.
- **Seção de Receitas:** Fundo escuro contrastante com vídeos embutidos e legendas informativas.
- **Formulário de Reserva:** Limpo, centralizado e com feedback visual ao passar o mouse no botão.
- **Rodapé (Footer):** Design moderno com logotipo, círculo decorativo, links sociais e copyright.

## 🚧 Planos de Melhoria (Future Roadmap)

Para expandir o projeto e enriquecer ainda mais o portfólio, os próximos passos incluem:

1. **Responsividade Completa (Mobile-First)**
   - **Objetivo:** Adaptar a interface para telas menores (smartphones e tablets), garantindo que o menu, o formulário e os vídeos se ajustem perfeitamente.
   - **Tecnologia:** Media Queries (`@media`) para reorganizar o layout com Flexbox/Grid.

2. **Validação de Formulário com JavaScript**
   - **Objetivo:** Melhorar a experiência do usuário com feedback visual mais rico (mensagens de erro suaves, validação de senha, verificação de e-mail real).
   - **Tecnologia:** JavaScript (ES6+) para interceptar o `submit` do formulário e validar os dados antes de enviar.

3. **Modo Escuro/Claro (Dark Mode Toggle)**
   - **Objetivo:** Permitir que o usuário alterne entre temas claros e escuros, melhorando a acessibilidade e a preferência pessoal.
   - **Tecnologia:** JavaScript para alternar uma classe no `body` e CSS com variáveis (`:root` e `[data-theme="dark"]`) para gerenciar cores dinamicamente.

4. **Integração com API de Reservas (Simulada)**
   - **Objetivo:** Ao invés de apenas exibir o formulário, simular o envio de dados para um backend (usando `fetch` e `Promise`) e exibir uma mensagem de sucesso com `toast notification`.

5. **Acesso por Teclado (Keyboard Navigation)**
   - **Objetivo:** Garantir que todos os interativos (links, botões, inputs) sejam navegáveis com `Tab` e acessíveis com `Enter`/`Space`.
   - **Tecnologia:** Atributo `tabindex` e eventos `keydown` para navegação otimizada.
