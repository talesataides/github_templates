# Github Templates

Repositório para teste de templates de Pull Requests para múltiplas branches.

## Templates

- default
- develop
- main

## Objetivo

<!-- Motivação aqui -->

Por padrão, o GitHub disponibiliza a possibilidade de ter múltiplos templates de Pull Request em um repositório, sendo possível controlar o template utilizado através de `query parameters` na URL.

[Veja na documentação oficial](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/using-query-parameters-to-create-a-pull-request)

> `https://github.com/octo-org/octo-repo/compare/main...my-branch?quick_pull=1&template=issue_template.md` creates a pull request with a template in the pull request body. The template query parameter works with templates stored in a PULL_REQUEST_TEMPLATE subdirectory within the root, docs/ or .github/ directory in a repository.

No entanto, visando uma melhor experiência do desenvolvedor, é possível criar uma "interface" para a seleção do template utilizando um template padrão.

## Como utilizar

A estrutura da pasta .github deve ser semelhante a essa: