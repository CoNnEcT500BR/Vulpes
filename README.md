# 🦊 Vulpes - Plataforma Educacional de Programação

<div align="center">

![Vulpes](https://img.shields.io/badge/Projeto-Educacional-blue)
![HTML5](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

**Vulpes é um projeto educacional focado em ensinar programação de forma clara, objetiva e interativa.**

[Visualizar Demo](#-como-usar) • [Características](#-características) • [Tecnologias](#-tecnologias) • [Contribuir](#-contribuir)

</div>

---

## 📋 Sobre o Projeto

O **Vulpes** nasceu como uma iniciativa educacional para facilitar o aprendizado de lógica de programação, algoritmos e desenvolvimento moderno. Com uma abordagem didática e conteúdos práticos, a plataforma oferece uma base sólida para iniciantes que desejam ingressar no mundo da programação.

### 🎯 Objetivos

- ✨ Ensinar programação de forma clara e objetiva
- 🚀 Fornecer conteúdos práticos e exemplos reais
- 💡 Construir uma base sólida em lógica e algoritmos
- 🎨 Criar uma experiência de aprendizado visual e interativa

---

## ✨ Características

- **🦊 Design Moderno e Responsivo** - Interface intuitiva que funciona em qualquer dispositivo
- **🎨 Tema Escuro Profissional** - Paleta de cores azul (#1e90ff) e preto para melhor experiência visual
- **✨ Animações Suaves** - Transições elegantes e interações fluidas
- **📱 Mobile-First** - Totalmente responsivo e otimizado para dispositivos móveis
- **⚡ Performance** - Código limpo e otimizado
- **🎯 Fácil Navegação** - Menu intuitivo com scroll suave
- **🖼️ Ilustrações SVG** - Raposa animada e logo personalizado

---

## 🛠️ Tecnologias

### Frontend
- **HTML5** - Estrutura semântica
- **CSS3** - Estilos modernos com animações
  - Gradientes
  - Flexbox & Grid
  - Animações keyframes
  - Backdrop-filter
- **JavaScript** - Interatividade
  - Menu responsivo
  - Navegação suave
- **SVG** - Gráficos vetoriais animados

### Fontes
- **Google Fonts** - Inter (300, 400, 600, 700)

---

## 📁 Estrutura do Projeto

```
Vulpes/
├── index.html              # Página principal
├── README.md              # Este arquivo
├── assets/
│   ├── css/
│   │   └── style.css      # Estilos globais
│   ├── js/
│   │   └── main.js        # Scripts interativos
│   └── images/
│       └── favicon.svg    # Favicon da aplicação
```

---

## 🚀 Como Usar

### 1. Clone o Repositório
```bash
git clone https://github.com/seu-usuario/vulpes.git
cd vulpes
```

### 2. Abra Localmente
Simplesmente abra o arquivo `index.html` no seu navegador:
```bash
# No Windows
start index.html

# No macOS
open index.html

# No Linux
xdg-open index.html
```

### 3. Ou Use um Servidor Local
```bash
# Python 3
python -m http.server 8000

# Node.js (com http-server)
npx http-server

# PHP
php -S localhost:8000
```

Acesse `http://localhost:8000` no seu navegador.

---

## 🎨 Paleta de Cores

| Cor | Hex | Uso |
|-----|-----|-----|
| Azul Principal | `#1e90ff` | Botões, links, destaque |
| Preto Escuro | `#0b0f1a` | Fundo principal |
| Cinza Escuro | `#141a2b` | Seções alternadas |
| Texto Claro | `#eaeaea` | Texto principal |
| Branco | `#ffffff` | Títulos e destaques |

---

## 📄 Seções da Landing Page

### 🏠 Hero Section
- Apresentação principal com chamada para ação
- Raposa animada e interativa
- Animações de entrada suave

### ℹ️ Seção Sobre
- Informações sobre o projeto
- Foco educacional
- Grade com 2 colunas responsiva

### 📚 Conteúdos Principais
- Algoritmos
- HTML & CSS
- Java
- Cards com hover effects

### 🎯 Call-to-Action (CTA)
- Botão com animação de pulso
- Efeito de shimmer ao passar o mouse
- Link direto para contato

### 👣 Footer
- Informações da empresa
- Links rápidos
- Dados de contato
- Copyright

---

## 🎭 Animações e Interações

### Raposa Hero
- **Flutuação Contínua** - Movimento suave para cima e para baixo
- **Cauda Animada** - Balança de forma natural
- **Hover Effect** - Animação de "dança" ao passar o mouse
- **Glow Effect** - Sombra que intensifica no hover

### Navegação
- **Underline Animado** - Links com linha azul que aparece ao hover
- **Menu Mobile** - Slide-in com animação suave
- **Logo Interativo** - Pequeno zoom ao hover

### Botões
- **Efeito de Shimmer** - Linha branca desliza sobre o botão
- **Animação de Pulso** - Sombra faz efeito de batida
- **Elevação** - Botão sobe 3px no hover
- **Glow Dinâmico** - Sombra azul intensifica

### Scroll
- **Scroll Suave** - Transições fluidas ao clicar em links de navegação

---

## 📱 Responsividade

O projeto é totalmente responsivo para:
- 📱 Smartphones (320px+)
- 📱 Tablets (768px+)
- 💻 Desktops (1024px+)

Breakpoints implementados:
- `@media (max-width: 768px)` - Ajustes para mobile

---

## 🔧 Configuração e Personalização

### Mudar Cores
Edite as variáveis CSS em `assets/css/style.css`:
```css
:root {
  --blue: #1e90ff;      /* Cor primária */
  --dark: #0b0f1a;      /* Fundo escuro */
  --dark-light: #141a2b;/* Fundo secundário */
  --text: #eaeaea;      /* Cor do texto */
}
```

### Adicionar Novos Conteúdos
Os cards podem ser duplicados na seção de conteúdos:
```html
<div class="card">
  <h3>Novo Tópico</h3>
  <p>Descrição do conteúdo.</p>
</div>
```

---

## 🚀 Próximas Melhorias

- [ ] Páginas de conteúdo individual (Algoritmos, HTML & CSS, Java)
- [ ] Sistema de comentários
- [ ] Scroll spy para destacar seção ativa
- [ ] Mais animações e efeitos
- [ ] Integração com banco de dados
- [ ] Certificados de conclusão
- [ ] Fórum comunitário

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Para contribuir:

1. **Faça um Fork** do projeto
2. **Crie uma branch** para sua feature (`git checkout -b feature/MinhaFeature`)
3. **Commit suas mudanças** (`git commit -m 'Adiciona MinhaFeature'`)
4. **Push para a branch** (`git push origin feature/MinhaFeature`)
5. **Abra um Pull Request**

### Padrões de Código
- Use nomes descritivos em português
- Mantenha o CSS organizado por seção
- Adicione comentários em código complexo
- Teste em mobile antes de fazer push

---

## 📝 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
