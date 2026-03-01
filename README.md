# Emanuella Melo - Currículo

Um currículo moderno e responsivo construído com React, Tailwind CSS e Vite.

## Estrutura do Projeto

```
src/
├── components/
│   ├── Navigation.jsx       # Barra de navegação fixa
│   ├── HeroSection.jsx      # Seção hero com apresentação
│   ├── ExperienceSection.jsx # Experiência profissional
│   ├── SkillsSection.jsx    # Habilidades e competências
│   ├── EducationSection.jsx # Formação acadêmica
│   ├── Footer.jsx           # Rodapé
│   └── index.js             # Exportações dos componentes
├── constants/
│   └── data.jsx             # Dados e configurações
├── utils/
│   └── helpers.js           # Funções auxiliares
├── App.jsx                  # Componente principal
├── main.jsx                 # Ponto de entrada
└── index.css                # Estilos globais
```

## Instalação

```bash
npm install
```

## Desenvolvimento

Para iniciar o servidor de desenvolvimento:

```bash
npm run dev
```

O aplicativo será aberto em `http://localhost:3000`

## Build

Para gerar a build de produção:

```bash
npm run build
```

## Preview

Para visualizar a build de produção localmente:

```bash
npm run preview
```

## Tecnologias Utilizadas

- **React 18** - Biblioteca JavaScript para interfaces
- **Vite** - Build tool moderno e rápido
- **Tailwind CSS** - Framework CSS utilitário
- **Lucide React** - Ícones SVG
- **PostCSS** - Processador CSS

## Personalizando o Conteúdo

Todos os dados estão centralizados em `src/constants/data.jsx`. Para atualizar as informações:

1. Abra `src/constants/data.jsx`
2. Edite as constantes (personalInfo, experienceData, skillsData, etc.)
3. As alterações serão refletidas automaticamente

## Seções

### 1. Navegação
- Navbar fixa com logo e links de navegação
- Botão de contato com cópia de email
- Toast de notificação

### 2. Hero Section
- Apresentação pessoal com animação
- Cards de contato
- Links de redes sociais
- Avatar visual animado

### 3. Experiência Profissional
- Lista de experiências com ícones
- Status (Atual/Encerrado)
- Competências associadas

### 4. Habilidades
- Categorias: Programação, Ferramentas, Interpessoais
- Tags interativas
- Nuvem de palavras-chave

### 5. Formação Acadêmica
- Graus acadêmicos
- Cursos complementares
- Status e períodos

### 6. Rodapé
- Links sociais
- Informações de copyright

## Estilos e Animações

- **Float Animation**: Avatar flutuante contínuo
- **Pulse Glow**: Efeito de brilho pulsante
- **Card Hover**: Efeito ao passar do mouse
- **Smooth Scroll**: Rolagem suave entre seções
- **Gradient Text**: Texto com gradiente azul

## Responsividade

O projeto é totalmente responsivo, otimizado para:
- Dispositivos móveis (< 640px)
- Tablets (640px - 1024px)
- Desktops (> 1024px)

## Licença

Este projeto é de uso pessoal.
