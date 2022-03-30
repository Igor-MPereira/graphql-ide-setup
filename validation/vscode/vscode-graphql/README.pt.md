# [VSCode GraphQL - GraphQL Foundation](https://marketplace.visualstudio.com/items?itemName=GraphQL.vscode-graphql)

## Adquirindo A Extensão

Instale a extensão [vscode-graphql](vscode:extension/GraphQL.vscode-graphql)

## Configuração Básica

A configuração básica requer um único arquivo `.graphqlrc.yml` no root do workspace

```yml
schema: <uri ou arquivo>
documents: <glob pattern com arquivos>
```

> *(exemplo: [.graphqlrc.yml](example/.graphqlrc.yml))*

Reinicie seu visual studio code e a extensão agora fará autocomplete, formatação, e validação de schema.

> *nota: esse arquivo de configuração pode ser utilizado com qualquer plugin que use __[graphql-config](https://www.graphql-config.com/)__*

## Configuração Avançada

Para configuração mais avançadas consulte a [página da extensão](https://marketplace.visualstudio.com/items?itemName=GraphQL.vscode-graphql) e o [repositório](https://github.com/graphql/vscode-graphql)

Consulte também a documentação do [graphql-config](https://www.graphql-config.com/)

## [Erros comuns](https://marketplace.visualstudio.com/items?itemName=GraphQL.vscode-graphql#:~:text=Frequently%20Asked%20Questions)

A extensão pode não inicializar corretamente se o arquivo de configuração não se encontrar no root do workspace

Consulte [este link](https://marketplace.visualstudio.com/items?itemName=GraphQL.vscode-graphql#:~:text=My%20graphql%20config%20file%20is%20not%20at%20the%20root) para resolver o problema
