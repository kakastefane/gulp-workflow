# Workflow com Gulp

Para utilizar o Gulp, primeiro é necessário baixar e instalar o [NodeJS](http://nodejs.org/download/)

Instale o Gulp globalmente:
```
[sudo] npm i -g gulp
```

Depois de baixar esse repositório, coloque-o em um diretório `src`, por exemplo, no seu projeto, e execute o comando:
```
npm install
```

para instalar todas as dependências do Gulp.

## Configuração

Edite o arquivo `gulp/assets-src` para definir os caminhos corretos para seus arquivos.

## Utilização

### `gulp w`

Assiste todos os arquivos JS e SASS e concatena.

### `gulp wjs`

Assiste todos os arquivos JS e concatena.

### `gulp wcss`

Assiste todos os arquivos SASS e concatena.

### `gulp`

Compila e concatena todos os JS e CSS e minifica-os.
