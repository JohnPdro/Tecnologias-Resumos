# Guia NPM - Node Package Manager

O npm não é um gerenciador de pacotes apenas do Node, mas sim do JavaScript como um todo (Back-end, Front-end, Mobile etc.). Ou seja, onde houver JavaScript, será possível adicionar pacotes através do npm.

## Instalação do NPM

Para instalar o NPM, será necessário instalar o Node. O npm é um pacote que é instalado junto com o Node.

Para verificar se o Node e o npm estão instalados, basta utilizar o terminal.
```
 node -v
 // versão instalada

 npm -v
 // versão instalada
```

## package.json
O arquivo package.json descreve o que está instalado no seu diretório, incluindo nome, versão, etc. Basicamente, ele serve para descrever o projeto e permite fazer alterações no arquivo.

Uma das funções do package.json é permitir a instalação de dependências (bibliotecas, módulos etc.).

Também são exibidos os metadados do projeto, como nome, descrição, autor, licença e versão.

Se você tentar instalar um pacote em um diretório que não possui o arquivo package.json, a instalação não ocorrerá.

No arquivo package.json, existe um campo chamado “scripts”, onde ficam comandos que podem ser utilizados no projeto.

Para criar um arquivo package.json, basta abrir o terminal, entrar no diretório do projeto e digitar o comando **npm init**.

**IMPORTANTE**: Para adicionar um framework ao seu projeto, basta instalar os pacotes dele através do terminal, seguindo a seguinte forma:
```
npm i ou install react
```
Para remover o framework basta fazer da seguinte forma:
```
npm r ou remove react
```
Caso algum pacote seja adicionado ou removido manualmente é necessário executar o mesmo código de instalção: 'npm i'

## Package.lock.json

Pode-se dizer que o arquivo package-lock.json é uma árvore de dependências, que informa os pacotes ou versões instalados e necessários para que não haja conflito caso o código seja aberto em outro ambiente de desenvolvimento.


## Diferença entre “dependencies” e “devDependencies”

**dependencies**: É o local onde são adicionados os pacotes de bibliotecas e frameworks.

**devDependencies**: É o local onde são adicionadas ferramentas exclusivamente para desenvolvimento.

## Como instalar pacotes de “devDependencies”

Para instalar os pacotes de “devDependencies”, basta seguir o mesmo caminho de instalação de pacotes, com apenas um detalhe a mais:
```
 npm i typescript --save-dev ou -D
```

## NPM e Git

Para subir apenas os arquivos desejados, basta criar um arquivo chamado .gitignore. Dentro deste arquivo, escreva o nome dos arquivos ou repositórios que você não pretende enviar. Normalmente, esses arquivos são as ferramentas utilizadas e estão dentro da pasta node_modules.

É recomendado fazer isso para que o arquivo não fique pesado na hora de subir.

Quando alguém da equipe precisar do código, basta clonar o repositório e verificar se há algum arquivo de bloqueio (package-lock.json). Em seguida, execute o comando de instalação.

**IMPORTANTE**: Não é recomendado ter dois gerenciadores de pacotes no projeto, pois quando o deployer for realizar a leitura, haverá dois arquivos de bloqueio, o que pode causar problemas.

**Curiosidade sobre .json**: Os arquivos .json nada mais são do que grandes objetos seguidos por chave e valor. Por exemplo:
```
{
 "name": "curso-npm"
 "version": "1.0.0"
 "description": "Hello World!"
}
```

**Curiosidade - LTS**
Softwares que possuem versão com sigla LTS (Long Term Support) significam que aquela versão tem suporte por longo período.


## Vídeos
([Link Curso de NPM](https://www.youtube.com/watch?v=g-V5qptW2oo&list=PLbV6TI03ZWYVjruiKLeb3m2rEXeYsG6RQ&pp=iAQB))