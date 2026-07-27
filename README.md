# 🎨 Portfólio Pessoal

Um template moderno e responsivo de portfólio desenvolvido com **HTML5** e **CSS3**, ideal para apresentar seus projetos, experiências e habilidades como desenvolvedor.

---

## 📋 Índice

- [🎯 Visão Geral](#visão-geral)
- [✨ Características](#características)
- [📁 Estrutura do Projeto](#estrutura-do-projeto)
- [📄 Páginas](#páginas)
- [🚀 Como Usar](#como-usar)
- [🎨 Personalização](#personalização)
- [🎭 Cores e Tipografia](#cores-e-tipografia)
- [👨‍💻 Autor](#autor)

---

## 🎯 Visão Geral

Este é um template de portfólio profissional com design moderno e minimalista. Utiliza uma paleta de cores contrastante (preto, branco e ciano) para criar uma interface limpa e profissional. O template é totalmente personalizável e pronto para ser utilizado. Perfeito para quem gosta de design **dark** e elegante! 🖤

---

## ✨ Características

- 🎯 **Design Responsivo** - Adaptável a diferentes tamanhos de tela
- 🧭 **Navegação Intuitiva** - Menu de navegação em todas as páginas
- 🌐 **Integração com Redes Sociais** - Links diretos para GitHub e LinkedIn
- ✍️ **Tipografia Moderna** - Fontes Google Fonts (Krona One e Montserrat)
- ⚫ **Estilo Limpo** - Design minimalista e profissional (tema dark)
- 🔧 **Fácil Personalização** - Estrutura bem organizada com variáveis CSS

---

## 📁 Estrutura do Projeto

```
Portfólio/
├── 📄 Index.html              # Página inicial/home
├── 👤 sobreMim.HTML           # Página sobre você
├── 📜 Curriculo.html          # Página com experiências e estudos
├── 📂 styles/
│   └── 🎨 style.css           # Arquivo de estilos principal
├── 🖼️ assets/
│   ├── 🐱 github.png          # Ícone do GitHub
│   ├── 💼 linkedin.png        # Ícone do LinkedIn
│   └── 📸 knee.jpg            # Imagem de perfil (exemplo)
└── 📖 README.md               # Este arquivo
```

---

## 📄 Páginas

### 🏠 **Index.html** - Página Inicial
- 🎭 Apresentação principal
- 💬 Título e descrição pessoal
- 🔗 Botões de acesso às redes sociais (GitHub e LinkedIn)
- 🖼️ Imagem de perfil

### 👤 **sobreMim.HTML** - Sobre Mim
- 📝 Seção para descrever quem você é
- 📚 Histórico profissional e pessoal
- 🎯 Informações detalhadas sobre sua trajetória

### 📜 **Curriculo.html** - Currículo
- **💼 Experiências**: Empresas onde trabalhou com datas
- **🎓 Estudos**: Cursos realizados com certificados
- 📋 Informações organizadas em listas

---

## 🚀 Como Usar

### 1️⃣ **Clone ou baixe o projeto**
```bash
git clone <URL-DO-REPOSITORIO>
```

### 2️⃣ **Abra o arquivo Index.html**
Simplesmente clique duas vezes em `Index.html` ou abra em seu navegador.

### 3️⃣ **Personalize o conteúdo**
- 📝 Edite os textos nas páginas HTML
- 🖼️ Substitua as imagens na pasta `assets/`
- 🔗 Atualize os links das redes sociais

### 4️⃣ **Faça deploy**
Hospede em plataformas como:
- 🐙 **GitHub Pages**
- 🚀 **Netlify**
- ⚡ **Vercel**
- 🌐 **000webhost**

---

## 🎨 Personalização

### ✏️ Alterar Informações Principais

#### Na página **Index.html**:
```html
<h1 class="apresentacao__conteudo__titulo">
    Seu nome ou profissão aqui
</h1>
<p class="apresentacao__conteudo__texto">
    Uma breve descrição sobre você
</p>
```

#### 🔗 Atualizar links das redes sociais:
```html
<a class="apresentacao__links__botao" href="https://github.com/seu-usuario">
    <img class="apresentacao__links__botao__imagem" src="./assets/github.png">
    GitHub
</a>
```

### 🖼️ Ajustar Imagem de Perfil

Para diminuir o tamanho da imagem, edite em `styles/style.css`:
```css
.apresentacao__imagem {
    width: 300px;  /* Reduza este valor */
    height: auto;
    margin-right: 50px;  /* Espaço entre imagem e texto */
}
```

---

## � Cores e Tipografia

### 🎨 Paleta de Cores
Editáveis em `styles/style.css`:

```css
:root {
    --cor-primaria: #000000;      /* ⬛ Preto */
    --cor-secundaria: #F6F6F6;    /* ⚪ Cinza claro */
    --cor-terciaria: #22d4fd;     /* 🔵 Ciano */
    --cor-hover-botao: #272727;   /* 🟫 Cinza escuro */
}
```

### ✍️ Fontes
- **Títulos**: Krona One
- **Texto**: Montserrat

Ambas importadas do Google Fonts.

---

## 💡 Dicas Úteis

### 🌐 Para adicionar mais redes sociais:
1. 🔍 Obtenha o ícone (PNG ou SVG) da rede social
2. 💾 Salve em `assets/`
3. 📋 Copie e adapte o botão existente:

```html
<a class="apresentacao__links__botao" href="https://twitter.com/seu-usuario">
    <img class="apresentacao__links__botao__imagem" src="./assets/twitter.png">
    Twitter
</a>
```

### 📱 Para melhorar a responsividade:
Adicione media queries ao final do `style.css`:

```css
@media (max-width: 768px) {
    .apresentacao {
        flex-direction: column;
    }
    
    .apresentacao__imagem {
        width: 300px;
    }
}
```

---

## 👨‍💻 Autor

Desenvolvido por **Vaundyyy** 🎩😈

---

## 📝 Licença

Este projeto é livre para uso pessoal e educacional.

---

## 🔗 Links Úteis

- 🎨 [Google Fonts](https://fonts.google.com/)
- 🐙 [GitHub](https://github.com)
- 💼 [LinkedIn](https://linkedin.com)
- 🚀 [Netlify](https://netlify.com) - Para deploy

---

## 📞 Suporte

Se tiver dúvidas sobre como personalizar o template, consulte a documentação HTML/CSS ou entre em contato através das redes sociais.

---

**Desenvolvido com 🖤 para ajudar você a criar um portfólio incrível!**
