
# CRUD-NEST-VUE

Este é o repositório principal que contém submodules para os projetos:

- **Frontend**: Repositório Vue.js
- **Backend**: Repositório NestJS

## Estrutura do Projeto

```
CRUD-NEST-VUE/
├── frontend/     # Submodule Vue.js
├── backend/      # Submodule NestJS
└── README.md     # Este arquivo
```

## Como clonar este repositório com submodules

```bash
# Clonar o repositório principal
git clone <URL_DO_REPOSITORIO_PRINCIPAL>

# Inicializar e atualizar os submodules
git submodule init
git submodule update
```

## Como trabalhar com os submodules

```bash
# Atualizar todos os submodules
git submodule update --remote

# Atualizar um submodule específico
git submodule update --remote frontend
git submodule update --remote backend
```

## Desenvolvimento

Para trabalhar nos projetos individuais, navegue para as pastas dos submodules:

```bash
cd frontend  # Para trabalhar no frontend Vue.js
cd backend   # Para trabalhar no backend NestJS
``` 