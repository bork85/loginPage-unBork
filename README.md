# 🔐 Página de Login - unBork

Uma página de login moderna e responsiva desenvolvida para a **unBork**, com design elegante e interface intuitiva.

## ✨ Características

- 🎨 **Design Moderno**: Interface limpa com paleta de cores profissional
- 📱 **Responsivo**: Layout totalmente adaptativo usando CSS Grid
- 🔒 **Campos de Segurança**: Entrada de email e senha com validação
- ☑️ **Lembrar-me**: Checkbox para manter sessão ativa
- 🔗 **Link de Recuperação**: Opção para recuperar senha esquecida
- 📲 **WhatsApp Integration**: Link direto para contato via WhatsApp
- 🎯 **Material Icons**: Ícones modernos do Google Material Symbols

## 📁 Estrutura do Projeto

```
loginPage-unBork/
├── index.html           # Arquivo principal HTML
├── styles.css          # Estilos CSS
├── README.md           # Este arquivo
└── assets/             # Pasta com imagens
    ├── logo-unBork.png        # Logo da marca
    ├── lateral-cartao.png     # Imagem de fundo lateral
    └── whatsapp.png           # Ícone do WhatsApp
```

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com variáveis CSS e Grid Layout
- **Google Material Symbols**: Ícones vetoriais
- **Responsive Design**: Mobile-first approach

## 📋 Campos do Formulário

| Campo | Tipo | Descrição |
|-------|------|-----------|
| E-mail | `email` | Entrada de correio eletrônico do usuário |
| Senha | `password` | Campo seguro para senha |
| Lembrar de mim | `checkbox` | Manter sessão ativa |
| Botão Entrar | `submit` | Enviar credenciais |
| Link Esqueceu senha | `link` | Recuperação de dados de acesso |

## 🎨 Paleta de Cores

```css
--bg-color: #ffffff           /* Branco - fundo principal */
--input-color: #e0e0e0       /* Cinza claro - campos input */
--text-color: #333333        /* Escuro - texto principal */
--text-color-light: #333333dd /* Cinza escuro - texto secundário */
--bg-btn-color: #ddcc34      /* Amarelo - destaque de botões */
```

## 📱 Layout

A página utiliza um layout em **duas colunas**:

- **Coluna Esquerda**: Imagem de fundo com informações de copyright
- **Coluna Direita**: Formulário de login com branding unBork

## 🚀 Como Usar

1. **Clone ou baixe o repositório**
   ```bash
   git clone https://github.com/bork85/loginPage-unBork.git
   cd loginPage-unBork
   ```

2. **Abra no navegador**
   - Abra o arquivo `index.html` diretamente no seu navegador
   - ou utilize a extensão "Live Server" (após instala-la basta clicar com o direito no arquivo `index.html` e ir na opção `open with Live Server`

3. **Acesse em seu navegador**
   ```
   http://localhost:5500
   ```
   - Se utilizar o Live Server a pagina será aberta automaticamente...

## 📝 Notas de Desenvolvimento

- O formulário está estruturado para futuro envio de dados via JavaScript/backend
- As imagens estão otimizadas em PNG para melhor qualidade
- Os estilos usam variáveis CSS personalizadas para fácil manutenção de temas
- O design segue princípios de acessibilidade web

## 🔧 Personalização

Para customizar a página, você pode:

1. **Alterar cores**: Modifique as variáveis CSS no `styles.css` (seção `:root`)
2. **Trocar imagens**: Substitua os arquivos na pasta `assets/`
3. **Atualizar textos**: Edite os textos no `index.html`
4. **Ajustar espaçamento**: Modifique as propriedades de padding/margin no CSS

## 📄 Licença e Copyright

© 2026 - **unBork** - Todos os direitos reservados

Feito com ❤️ pela unBork

## 📞 Contato

- **WhatsApp**: Clique no ícone do WhatsApp na página
- **Link de Suporte**: Disponível na seção "Esqueceu sua senha?"

---

**Versão**: 1.0  
**Idioma**: Português (Brasil)  
**Data de Criação**: Março de 2026
