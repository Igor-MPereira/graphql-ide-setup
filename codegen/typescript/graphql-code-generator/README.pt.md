# [GraphQL Code Generator](https://graphql-code-generator.com) - [TypeScript](https://www.typescriptlang.org)

## Configuração Básica

### Instalando o pacote

Para dar início à configuração, instale os pacotes `typescript`, `graphql` e `@graphql-codegen/cli`

```sh
# yarn

yarn add graphql
yarn add -D typescript @graphql-codegen/cli

# ou npm

npm i -S graphql
npm i -D typescript @graphql-codegen/cli
```

> *[É importante evitar instalações globais para evitar conflitos](https://www.graphql-code-generator.com/docs/getting-started/installation#global-installation)*

### *[Initialization Wizard](https://www.graphql-code-generator.com/plugins)*

> *para uma configuração manual consulte a seção [Configuração Manual](#configuração-manual)*

Digite no terminal

```sh
# yarn

yarn graphql-codegen init

# ou npm

npm run graphql-codegen init
```

### Templates

Será exibido uma lista de templates para selecionar

> - Backend
> - Angular
> - React
> - Stencil
> - other framework or vanilla JS

Selecione um e siga para o próximo passo

> *Para o exemplo será selecionado o template **`vanilla JS`***

### Definição de Schema

Será pedido a localização do seu schema, o schema pode ser um arquivo local ou um endpoint GraphQL

> *(exemplo: `graphql/schema.graphql`, <https://countries.trevorblades.com>, `https://localhost:5000`)*

### Arquivos Alvo

Em seguida será pedido a localização dos arquivos com as operações e fragmentos GraphQL

> *(exemplo: `graphql/**/*.graphql`)*

### Plugins

Selecione os plugins desejados, os plugins restantes e as configurações adicionais são feitos [manualmente](#plugins-manuais)

> *Para o exemplo serão utlizados os plugins **`typescript`, `typescript-operations` e `typescript-document-nodes`***

### Destino

Informe o destino do arquivo gerado

> *(exemplo: `graphql/generated.ts`)*

#### Informe se deseja um arquivo de introspecção JSON

### Arquivo de configuração

Informe o nome do arquivo de configuração

*por padrão é `codegen.yml`*

### Script de codegen

Determine o nome do script de geração de código

> *(exemplo: `gql`)*

### Instalando os plugins

Por fim digite

```sh
# yarn

yarn install

# ou npm

npm install
```

para instalar os plugins selecionados na etapa de [plugins](#plugins)

### Gerando o código

O script pode ser executado digitando no terminal

```sh
# yarn

yarn gql

# ou npm

npm run gql
```

## Configuração Avançada

Para uma configuração avançada veja [codegen.pt.yml](example/codegen.pt.yml)

lembre-se de consultar o [hub de plugins](https://www.graphql-code-generator.com/plugins) para uma lista e documentação completa dos plugins

----------

## Configuração Manual

### Arquivo de configuração manual

Para um guia de configuração manual consulte a [documentação de configuração](https://www.graphql-code-generator.com/docs/config-reference/codegen-config)

### Plugins manuais

Para uma lista completa dos plugins disponíveis consulte o [hub de plugins](https://www.graphql-code-generator.com/plugins)
