# Sistema de Cadastro de Professores 

Uma aplicação React desenvolvida nas aulas de Web 2 para cadastro e organização de professores por área de atuação.

## Sobre o Projeto

Sistema completo de cadastro que permite:

- **Cadastro de professores** com nome, título e imagem
- **Organização por áreas** de atuação
- **Visualização em cards** com design moderno
- **Interface responsiva** para diferentes dispositivos

## Objetivos de Aprendizado

- Desenvolvimento de formulários em React
- Trabalho com componentes funcionais
- Manipulação de estado e props
- Estilização com CSS modules
- Composição de componentes reutilizáveis
- Validação de dados de entrada

## Tecnologias Utilizadas

- **React** - Biblioteca principal
- **CSS Modules** - Estilização componentizada
- **Componentes Funcionais** - Padrão moderno do React
- **Props e State** - Gerenciamento de dados

## Estrutura do Projeto

```
src/
├── componentes/
│   ├── Banner/           # Banner institucional
│   ├── Formulario/       # Formulário de cadastro
│   ├── CampoTexto/       # Input de texto
│   ├── ListaSuspensa/    # Dropdown de seleção
│   ├── Botao/            # Botão de ação
│   ├── Area/             # Seção por área de atuação
│   ├── Professor/        # Card individual do professor
│   └── Lista/            # Lista geral de professores
├── App.jsx               # Componente principal
└── index.css             # Estilos globais
```

## Componentes Principais

### Formulario
Formulário completo para cadastro de novos professores com validação.

### Area
Seções organizadas por área de conhecimento com cores diferenciadas.

### Professor
Card individual que exibe foto, nome e título do professor.

### ListaSuspensa
Dropdown para seleção de área de atuação.

## Como Executar

```bash
# Instalar dependências
npm install

# Executar em desenvolvimento
npm run dev

# Build para produção
npm run build
```

---
