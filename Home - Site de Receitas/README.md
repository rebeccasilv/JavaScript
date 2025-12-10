# 🍳 Home Site de Receitas - WordPress Template

<div align="center">

![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Template moderno e responsivo para páginas iniciais de sites de receitas no WordPress**

[Ver Demo](#-demonstração) • [Instalação](#-instalação) • [Recursos](#-recursos) • [Contribuir](#-contribuindo)

</div>

---

## 📋 Sobre o Projeto

Este é um template de **página inicial (home)** desenvolvido especialmente para sites de receitas no **WordPress**. O projeto foi criado seguindo as políticas e melhores práticas do WordPress, utilizando **PHP** para integração nativa com o CMS.

### 🎯 Diferencial

O grande diferencial deste projeto é que ele foi desenvolvido especificamente para WordPress, diferente de outras homes que criei para aplicativos. Ele segue todas as diretrizes do WordPress e foi construído em PHP, permitindo uma integração perfeita com o ecossistema WordPress.

---

## ✨ Recursos

### 🎨 Design Moderno e Atraente
- **Interface Premium**: Design profissional com gradientes animados e efeitos visuais modernos
- **Tipografia Elegante**: Utiliza as fontes Google Fonts (Playfair Display + Poppins)
- **Animações Suaves**: Biblioteca AOS (Animate On Scroll) para animações fluidas
- **Efeitos Interativos**: Hover effects, glassmorphism e animações customizadas

### 📱 100% Responsivo
- **Mobile First**: Totalmente otimizado para dispositivos móveis
- **Adaptável**: Funciona perfeitamente em tablets, smartphones e desktops
- **Menu Mobile**: Menu hambúrguer elegante com animações suaves
- **Touch Optimized**: Otimizado para interações touch em dispositivos móveis

### 🚀 Performance e Otimização
- **TailwindCSS via CDN**: Framework CSS moderno e eficiente
- **Lazy Loading**: Carregamento otimizado de recursos
- **Animações Otimizadas**: Animações reduzidas em dispositivos móveis para melhor performance
- **SEO Friendly**: Estrutura HTML semântica e otimizada para mecanismos de busca

### 🛠️ Funcionalidades

#### 🏠 Seções Principais
1. **Hero Section**: Banner principal com call-to-action destacado
2. **Categorias de Receitas**: Cards interativos com links para diferentes categorias
3. **Receitas em Destaque**: Grid de receitas com informações detalhadas
4. **Estatísticas Animadas**: Contadores animados com métricas do site
5. **Seção de Newsletter**: Formulário de inscrição estilizado
6. **Footer Completo**: Rodapé com links, redes sociais e informações de contato

#### 🎯 Componentes Interativos
- ✅ Menu de navegação fixo com efeito de scroll
- ✅ Botão "Voltar ao topo" com animação
- ✅ Cards de receitas com hover effects
- ✅ Sistema de categorias clicáveis
- ✅ Contadores animados de estatísticas
- ✅ Links para redes sociais
- ✅ Smooth scroll entre seções

---

## 📸 Demonstração

### 💻 Desktop
![Home Desktop - Visão 1] <img src="imagem 01.jpeg">

![Home Desktop - Visão 2] <img src="imagem 02.jpeg">

### 📱 Mobile
![Home Mobile - Visão 1] <img src="imagem 03.jpeg"> <br>
![Home Mobile - Visão 2] <img src="imagem 04.jpeg">

---

## 🔧 Instalação

### Método 1: Via WP File Manager (Recomendado)

1. **Instale o plugin WP File Manager** no seu WordPress:
   ```
   Painel Admin → Plugins → Adicionar Novo → Buscar "WP File Manager" → Instalar → Ativar
   ```

2. **Acesse o WP File Manager**:
   ```
   Painel Admin → WP File Manager
   ```

3. **Navegue até a pasta de templates**:
   ```
   wp-content/themes/seu-tema/
   ```

4. **Faça upload do arquivo** `home_index.html` para a pasta do tema

5. **Configure a página**:
   - Vá em: `Páginas → Adicionar Nova`
   - Dê um título à página (ex: "Home")
   - No painel lateral direito, em "Atributos de Página"
   - Selecione o template: **"Home Receitas Culinárias - Versão Melhorada"**
   - Publique a página

6. **Defina como página inicial**:
   - Vá em: `Configurações → Leitura`
   - Marque: "Uma página estática"
   - Selecione a página criada como "Página inicial"
   - Salve as alterações

### Método 2: Via FTP/cPanel

1. Conecte-se ao seu servidor via FTP ou acesse o Gerenciador de Arquivos do cPanel

2. Navegue até: `public_html/wp-content/themes/seu-tema/`

3. Faça upload do arquivo `home_index.html`

4. Siga os passos 5 e 6 do Método 1

---

## ⚙️ Personalização

### 🔗 Alterando Links de Redirecionamento

O template vem com links de exemplo para categorias. Você precisa alterar esses links para as suas próprias categorias:

```php
// Procure por seções como esta no código:
<a href="https://receitasculinarias.com.br/categoria/salgados/">

// E substitua pelo link da sua categoria:
<a href="https://seusite.com.br/categoria/sua-categoria/">
```

### 🎨 Personalizando Cores

As cores principais do template usam tons de laranja. Para alterar:

```css
/* Procure por classes como: */
bg-orange-500
text-orange-600
from-orange-500
hover:text-orange-500

/* E substitua pelos códigos de cor desejados */
```

### 📝 Adaptando para Outros Nichos

Embora desenvolvido para sites de receitas, o template pode ser facilmente adaptado para:
- 📰 Blogs de notícias
- 🎨 Portfolios criativos
- 🏪 Sites de produtos
- 📚 Blogs educacionais
- 💼 Sites corporativos

---

## 🛠️ Tecnologias Utilizadas

| Tecnologia | Descrição |
|------------|-----------|
| ![PHP](https://img.shields.io/badge/-PHP-777BB4?style=flat&logo=php&logoColor=white) | Linguagem server-side para integração com WordPress |
| ![TailwindCSS](https://img.shields.io/badge/-TailwindCSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white) | Framework CSS utility-first |
| ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black) | Interatividade e animações |
| ![AOS](https://img.shields.io/badge/-AOS-00A8E8?style=flat) | Biblioteca de animações on scroll |
| ![Font Awesome](https://img.shields.io/badge/-Font_Awesome-339AF0?style=flat&logo=font-awesome&logoColor=white) | Biblioteca de ícones |
| ![Google Fonts](https://img.shields.io/badge/-Google_Fonts-4285F4?style=flat&logo=google&logoColor=white) | Fontes tipográficas personalizadas |

---

## 📦 Estrutura do Código

```
home_index.html
├── Header PHP (WordPress Integration)
├── HTML Structure
│   ├── Head Section
│   │   ├── Meta Tags
│   │   ├── TailwindCSS CDN
│   │   ├── Google Fonts
│   │   ├── Font Awesome
│   │   └── AOS Library
│   ├── Custom Styles
│   │   ├── Animations
│   │   ├── Hover Effects
│   │   └── Responsive Design
│   └── Body Content
│       ├── Navigation Menu
│       ├── Hero Section
│       ├── Categories Section
│       ├── Featured Recipes
│       ├── Statistics Section
│       ├── Newsletter Section
│       └── Footer
├── JavaScript
│   ├── AOS Initialization
│   ├── Mobile Menu
│   ├── Header Scroll Effect
│   ├── Back to Top Button
│   ├── Counter Animation
│   └── Smooth Scroll
└── Footer PHP (WordPress Integration)
```

---

## 🎯 Recursos Destacados

### 🎨 Sistema de Animações

```javascript
// Animações customizadas incluem:
- fadeInUp: Entrada suave de elementos
- float: Efeito de flutuação
- pulse-glow: Efeito de brilho pulsante
- slideInRight: Entrada lateral
- gradient-animate: Gradiente animado
```

### 📱 Otimização Mobile

O template detecta automaticamente dispositivos móveis e ajusta:
- ✅ Tamanho de animações reduzido
- ✅ Hover effects adaptados
- ✅ Desempenho otimizado
- ✅ Touch gestures suportados

### 🔍 SEO Otimizado

```html
- Estrutura HTML semântica
- Meta tags apropriadas
- Alt texts em imagens
- Heading hierarchy correta
- Schema markup ready
```

---

## 🚀 Casos de Uso

Este template é perfeito para:

- 🍕 **Sites de Receitas**: Uso principal e otimizado
- 📰 **Blogs Gastronômicos**: Compartilhar conteúdo culinário
- 👨‍🍳 **Chefs e Cozinheiros**: Portfolio pessoal
- 🏪 **Restaurantes**: Showcase de menu e pratos
- 📚 **Cursos de Culinária**: Apresentação de cursos
- 🎥 **Canais de Culinária**: Complemento para canais do YouTube

---

## ⚠️ Requisitos

- ✅ WordPress 5.0 ou superior
- ✅ PHP 7.4 ou superior
- ✅ Tema WordPress ativo
- ✅ Plugin WP File Manager (recomendado)
- ✅ Conexão com internet (para CDNs)

---

## 📝 Notas Importantes

### ⚡ Performance
- O template utiliza CDNs para melhor performance
- Animações são otimizadas para não impactar o carregamento
- Mobile-first approach garante boa experiência em todos os dispositivos

### 🔐 Segurança
- Previne acesso direto ao arquivo com: `if (!defined('ABSPATH')) exit;`
- Segue as melhores práticas de segurança do WordPress
- Nenhum dado sensível hardcoded

### 🌐 Compatibilidade
- Testado nos principais navegadores (Chrome, Firefox, Safari, Edge)
- Compatível com os temas WordPress mais populares
- Responsivo em todos os tamanhos de tela

---

## 🤝 Contribuindo

Contribuições são bem-vindas! Se você tem sugestões, melhorias ou encontrou algum bug:

1. Fork o projeto
2. Crie uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abra um Pull Request

---

## 📜 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

## 👨‍💻 Autor - Rebecca Silva

Desenvolvido com ❤️ e ☕ 

---

## 🌟 Mostre seu Apoio

Se este projeto foi útil para você, considere dar uma ⭐️!

---

## 📊 Status do Projeto

![Status](https://img.shields.io/badge/Status-Ativo-brightgreen)
![Manutenção](https://img.shields.io/badge/Manuten%C3%A7%C3%A3o-Sim-brightgreen)
![WordPress](https://img.shields.io/badge/WordPress-5.0%2B-blue)

---

## 🔄 Changelog

### Versão 1.0.0 (Atual)
- ✅ Lançamento inicial
- ✅ Design responsivo completo
- ✅ Integração com WordPress
- ✅ Animações e efeitos interativos
- ✅ Sistema de categorias
- ✅ Newsletter section
- ✅ Otimização mobile

---

## 🎓 Aprendizados

Este projeto foi desenvolvido aplicando:
- **WordPress Template Development**: Criação de templates customizados
- **PHP Integration**: Integração nativa com WordPress
- **Responsive Design**: Mobile-first approach
- **Modern CSS**: TailwindCSS e animações CSS
- **JavaScript**: Interatividade e UX melhorada
- **Performance Optimization**: Carregamento otimizado e lazy loading

---

<div align="center">

**💡 Dica**: Não esqueça de personalizar os links e adaptar o conteúdo para seu projeto!

Desenvolvido por Rebecca Silva


</div>

