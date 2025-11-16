# Portfolio de Ana Cosme

## Descrição
Este é um portfólio web moderno e responsivo desenvolvido para Ana Cosme, licenciada em Ciências da Educação pela Faculdade de Psicologia da Universidade do Porto. O site destaca sua formação académica, experiência em voluntariado e competências sociais.

## 🚀 Características

### Design
- **Responsivo**: Adaptado para dispositivos móveis, tablets e desktops
- **Moderno**: Interface limpa com gradientes e animações suaves
- **Acessível**: Navegação intuitiva e semântica HTML adequada

### Funcionalidades
- **Navegação Suave**: Scrolling suave entre secções
- **Menu Mobile**: Hamburger menu para dispositivos móveis
- **Animações**: Elementos animados ao fazer scroll
- **Formulário de Contacto**: Com validação de campos
- **Loading Screen**: Animação de carregamento
- **Easter Egg**: Código Konami para diversão

### Secções
1. **Hero**: Apresentação principal com call-to-action
2. **Sobre**: Informações pessoais e estatísticas
3. **Educação**: Timeline da formação académica
4. **Experiência**: Cards com projetos de voluntariado
5. **Competências**: Organizado por categorias
6. **Contacto**: Informações e formulário

## 📁 Estrutura do Projeto

```
AnaCosmePortfolio/
│
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript interativo
└── README.md           # Este arquivo
```

## 🎨 Personalização

### Cores Principais
```css
--primary-color: #3498db;      /* Azul principal */
--secondary-color: #2c3e50;    /* Azul escuro */
--gradient-start: #667eea;     /* Gradiente início */
--gradient-end: #764ba2;       /* Gradiente fim */
```

### Informações Pessoais
Para personalizar as informações, edite as seguintes secções no `index.html`:

#### Informações de Contacto
```html
<div class="contact-method">
    <i class="fas fa-envelope"></i>
    <span>ana.cosme@email.com</span>    <!-- Alterar email -->
</div>
```

#### Links Sociais
```html
<a href="#" class="social-link">        <!-- Adicionar URL LinkedIn -->
    <i class="fab fa-linkedin"></i>
</a>
```

### Adicionando Foto de Perfil
Substitua o placeholder da imagem na secção hero:

```html
<!-- Substituir este bloco -->
<div class="profile-placeholder">
    <i class="fas fa-user"></i>
</div>

<!-- Por -->
<img src="caminho/para/foto.jpg" alt="Ana Cosme" class="profile-image">
```

E adicione este CSS:
```css
.profile-image {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

## 🛠️ Desenvolvimento Local

### Pré-requisitos
- Navegador web moderno
- Editor de código (VS Code recomendado)

### Execução
1. Clone ou baixe os arquivos
2. Abra `index.html` num navegador web
3. Para desenvolvimento, use um servidor local:
   ```bash
   # Com Python
   python -m http.server 8000
   
   # Com Node.js (http-server)
   npx http-server
   ```

## 🌐 Deploy

### GitHub Pages
1. Faça upload dos arquivos para um repositório GitHub
2. Vá a Settings > Pages
3. Selecione a branch main como source
4. O site estará disponível em `https://username.github.io/repository-name`

### Netlify
1. Arraste a pasta do projeto para netlify.com
2. Ou conecte o repositório GitHub
3. Deploy automático

### Vercel
1. Importe o projeto no vercel.com
2. Deploy com um clique

## 📱 Responsividade

O site está otimizado para:
- **Desktop**: 1200px+
- **Tablet**: 768px - 1199px
- **Mobile**: até 767px

## 🔧 Dependências Externas

- **Google Fonts**: Poppins
- **Font Awesome**: Ícones
- **CDN**: Carregados via CDN (não requer instalação)

## 📄 Licença

Este projeto está disponível para uso pessoal e educacional.

## 🤝 Contribuições

Sugestões e melhorias são bem-vindas! Para contribuir:

1. Faça um fork do projeto
2. Crie uma branch para sua feature
3. Commit suas mudanças
4. Push para a branch
5. Abra um Pull Request

## 📞 Suporte

Para dúvidas ou suporte:
- Abra uma issue no GitHub
- Entre em contacto através do formulário no site

## 🎯 Roadmap

- [ ] Integração com API de email para formulário
- [ ] Modo escuro/claro
- [ ] Mais animações CSS
- [ ] Blog/Portfolio de projetos
- [ ] Múltiplas linguagens
- [ ] PWA (Progressive Web App)

---

**Desenvolvido com ❤️ para Ana Cosme** 
