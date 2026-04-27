# Cardápio Serenatto — PHP + MySQL

> Sistema de cardápio digital para a cafeteria Serenatto com painel administrativo, autenticação e geração de PDF.

## Funcionalidades

- Listagem de opções de café da manhã e almoço
- Painel admin para cadastro, edição e exclusão de produtos
- Login com autenticação
- Geração de cardápio em PDF
- Upload de imagens dos produtos

## Stack

<img src="https://skillicons.dev/icons?i=php,mysql,html,css" />

| Tecnologia | Uso |
|-----------|-----|
| PHP | Backend e templates |
| MySQL + PDO | Banco de dados |
| Composer | Gerenciamento de dependências |
| HTML/CSS | Frontend |

## Estrutura

```
├── index.php              # Cardápio público
├── admin.php              # Painel administrativo
├── login.html             # Autenticação
├── cadastrar-produto.php  # Novo produto
├── editar-produto.php     # Editar produto
├── excluir-produto.php    # Remover produto
├── gerador-pdf.php        # Exportar PDF
└── src/
    ├── conexao-bd.php
    ├── Modelo/Produto.php
    └── Repositorio/ProdutoRepositorio.php
```

## Como rodar

```bash
# Instalar dependências
composer install

# Configurar banco de dados em src/conexao-bd.php
# Importar o schema SQL

# Rodar com PHP built-in server
php -S localhost:8000
```

---

Desenvolvido com PHP · MySQL · Composer