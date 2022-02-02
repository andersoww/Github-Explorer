## Configurando Babel

Babel tem a reponsabilidade em "traduzir o código do projeto" para os demais browsers interpretarem da melhor maneira.

### Instalacao
yarn add @babel/core @babel/cli @babel/preset-env -D 

### Execucao
yarn babel src/index.js --out-file dist/bundle.js