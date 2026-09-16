# iPhone 17 — Landing Page

Uma landing page moderna e interativa inspirada no conceito do iPhone 17, desenvolvida para explorar recursos de interface, animações, composição visual e experiência do usuário utilizando React, JavaScript, CSS e Vite.

## Preview

Este projeto apresenta uma experiência visual inspirada em páginas de apresentação de produtos premium, utilizando uma interface moderna, responsiva e focada em apresentação de produto.

## Tecnologias

- React
- JavaScript
- CSS
- Vite
- HTML5
- ESLint

## Funcionalidades

- Interface moderna e responsiva
- Navegação entre seções
- Hero section de apresentação
- Seção de introdução
- Destaques do produto
- Apresentação visual de cores
- Componentização com React
- Animações e efeitos visuais
- Layout adaptado para diferentes tamanhos de tela
- Estrutura otimizada para desenvolvimento e produção

## Estrutura do projeto

```text
iphone-17/
│
├── public/
│
├── src/
│   ├── assets/
│   │
│   ├── components/
│   │   ├── Colors.jsx
│   │   ├── footer.jsx
│   │   ├── Hero.jsx
│   │   ├── Highlights.jsx
│   │   ├── Intro.jsx
│   │   └── NavBar.jsx
│   │
│   ├── App.jsx
│   ├── index.css
│   └── main.jsx
│
├── .gitignore
├── eslint.config.js
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## Componentes

### `NavBar.jsx`

Componente responsável pela barra de navegação principal da aplicação.

### `Hero.jsx`

Seção principal da página, responsável pela apresentação inicial do produto.

### `Intro.jsx`

Componente utilizado para apresentar informações introdutórias sobre o produto e a experiência proposta pela página.

### `Highlights.jsx`

Seção responsável pela apresentação dos principais destaques e características do produto.

### `Colors.jsx`

Componente responsável pela apresentação das opções de cores.

### `footer.jsx`

Rodapé da aplicação com informações complementares.

### `App.jsx`

Componente principal responsável pela composição das diferentes partes da aplicação.

### `main.jsx`

Ponto de entrada da aplicação React.

### `index.css`

Arquivo responsável pelos estilos globais e pela identidade visual da aplicação.

## Instalação

Para executar o projeto localmente, primeiro clone o repositório:

```bash
git clone https://github.com/SEU-USUARIO/iphone17-landing-page.git
```

Entre na pasta do projeto:

```bash
cd iphone17-landing-page
```

Instale as dependências:

```bash
npm install
```

## Desenvolvimento

Execute o servidor de desenvolvimento:

```bash
npm run dev
```

O Vite disponibilizará o projeto localmente, normalmente em:

```text
http://localhost:5173
```

## Build de produção

Para gerar a versão otimizada para produção:

```bash
npm run build
```

Os arquivos de produção serão gerados na pasta:

```text
dist/
```

Para testar a versão de produção localmente:

```bash
npm run preview
```

## Lint

Para verificar problemas de código utilizando ESLint:

```bash
npm run lint
```

## Deploy

O projeto pode ser publicado utilizando plataformas de hospedagem compatíveis com aplicações React/Vite.

### Vercel

O projeto foi estruturado para ser compatível com deploy na Vercel.

Configuração esperada:

```text
Framework Preset: Vite
Build Command: npm run build
Output Directory: dist
Install Command: npm install
```

Em uma configuração padrão do Vite, a Vercel consegue detectar o projeto e realizar o deploy com pouca ou nenhuma configuração adicional.

## Responsividade

A interface foi desenvolvida considerando diferentes tamanhos de tela, incluindo:

- Desktop
- Notebook
- Tablet
- Smartphone

## Objetivo do projeto

Este projeto foi desenvolvido como uma experiência prática de desenvolvimento front-end, com foco em:

- React
- Componentização
- JavaScript
- CSS
- Vite
- Design responsivo
- UI/UX
- Animações
- Organização de código
- Desenvolvimento de interfaces modernas

## Aprendizados

Durante o desenvolvimento foram trabalhados conceitos como:

- Criação de componentes reutilizáveis
- Estruturação de aplicações React
- Comunicação entre componentes
- Organização de arquivos
- Gerenciamento de estilos
- Desenvolvimento de layouts responsivos
- Integração de assets
- Configuração de projetos utilizando Vite
- Preparação de aplicações para produção
- Deploy de aplicações web

## Status

Projeto concluído e disponível para demonstração.

## Autor

**João Pedro**

Estudante de Análise e Desenvolvimento de Sistemas.

Desenvolvedor com foco em desenvolvimento web e front-end.

### GitHub

https://github.com/debugbastos

---

## Observação

Este projeto é uma experiência independente de desenvolvimento e design de interface inspirada na apresentação visual de produtos da categoria de smartphones.

Não possui afiliação oficial com a Apple.

---

## Licença

Este projeto foi desenvolvido para fins de estudo, portfólio e demonstração de habilidades em desenvolvimento front-end.
