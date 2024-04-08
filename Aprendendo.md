# API

## O que é API

> Pode ser aplicada em qualquer contexto de desenvolvimento de software e em qualquer tipo de software
> A API é a interface ideal para que um sistema se comunique com outro sistema
> Os beneficios das APIs são diversos por sua conexão com vários sistemas diferentes 
> As APIs funcionam em diversos locais, Front-End, Back-End, WEB e até em Sistemas Operacionais

## API - Significado

> Aplication Program Interface - Interface de Programação de Aplicações

## API Rest - HTTP 1.1

> O HTTP utiliza protocolos de navegação como GET, POST e HEAD, o API Rest permite que haja novos protocolos como PUT, DELETE, TRACE, CONNECT

## EndPoints

> É a extremidade de um canal de comunicação, representado por um URL de um servidor ou serviço
> Possui três caracteristicas ABC: A - Address, B - Binding e C - Contract


## Segurança

> O uso do SSL nas conexões das APIs é importantissimo, pois o SSL garante a troca de informações criptografadas utilizando o protocolo HTTPS
> A autenticação é ecencial para isolar o que pode ser fornecido de informações para cada um dos softwares que chama a API
> Uma das tecnicas preferidas de autenticação são os Tokens
> Os Tokens são identificadores únicos que são composto por uma sequência de caracteres
> Os Tokesn são enviados juntos as chamadas de APIs, são chaves que ficam guardadas como se fossem uma senha 

## Retorno de uma API

> As APIs basedas em web retornam os dados através de arquivos JSON ou XML 




______________________________________________________________________________________________


# DOM

## O que é DOM?

> É uma interface que permite criar e manipular páginas e conteúdos no navegador  
> O DOM já é imbutido nos navegadores, definindo regras de como funcionar 
> Essas regras são definidas pela **World Wide Web Consortium** 

## DOM - Significado

> Document Object Model - Modelo de documentos por objeto

## Estrutura em arvore DOM - exemplo HTML

>                           window
>                              | 
>                          document
>                              | 
>                            HTML
>                              | 
>                           |     |
>                         |         |  
>                       |             | 
>                     |                 | 
>                   HEAD               BODY 
>                 |  |  |  |            |  
>               |   |   |   |         |    |                
>             |    |    |    |      |        |              
>           meta meta title link   div    script          
>                                   |        
>                                   |        
>                              |  |  |  | 
>                            |   |    |   | 
>                            |   |    |   |
>                          img  h1    p  div 
______________________________________________________________________________________________


# JSON

## O que é JSON?

> JSON é um acrônico de JavaScript Object Notion, define um padrão de armazenamento e troca de informaçõs em formato texto

> O arquivo JSON **não é escrito na linguagem JavaScript**, possui facil interpretação por conter um padrão lógico muito simples, tornando a leitura do arquivo rapido e simples pelas maquinas 

> **Bastante utilizado pelas APIs** por seus diversos beneficios citados 

## Syntax 

> Todo JSON começa e termina com {}
> {
>   "nome":"João",   
>   "sobrenome":"Silva", 
>   "idade":37,
>   "casado":false,
>   "filhos":["Gabriel", "Felipe"],
>   "netos":null
>}


## Definição de JSON

> Arquivo de texto utilizado para **troca** e **armazenamento de informações**, facil de entender, interpretar e gerar.>
______________________________________________________________________________________________



# CDN

## O que é CDN?

> CDN ajuda a armazenar contúdo em **cache** na **borda da rede**, aprimorando o desempenho do site.


# Jamstack

## O que é o Jamstack ?
> É uma idéia de como construir aplicações melhores não só para devs mas também para usuários

## JAM - significado

> J - Javascript | A - Aplication Programming Interfaces(APIs) | M - Markup(HTML)

> Pode ser constituida por diversas tecnologias, não precisa necessáriamente utilizar a linguagem Javascript por conta disso acaba sendo uma boa escolha na hora de construir aplicaçõe 

## Como funciona?

> As informações em HTML são armazenadas em cache, puopando o serviço do servidor de mandar o conteúdo e acelerando todo o processo de carregamento da página.

> Isso é feito utilizando uma ferramenta SSG(Static Site Generator) ou Build Tool ambas compilam a página HTML podendo disponibiliza-la através de um CDN(Content Delivery Network)

> Mas isso não substitui o serviço do servidor, sempre que houver alguma alteração no código o sevidor será responsavel por mandar a nova versão disponivel


# Vantagens e Desvantagens

## Vantagem

> Velocidade - Por ter um código limpo e um armazenamento em cache
> Segurança - O Front-end trabalha de forma desacoplada do Back-end
> Ganhos de escala - Com o Work Load reduzido o ganho de escala é maior
> Portabilidade - Por ser pre-gerado é possivel ospedar em praticamente qualquer lugar
> Otima experiência de Desenvolvedor - Por ser uma stack muito felxivel é possivel usar diversas ferramentas diferentes 

## Desvantagens

> Dificuldade para editores de conetúdo 
> Atualização = codificação 
> Recursos dinâmicos exigem mais trabalho
> Falha da aplicação em caso de falha em serviçoes de terceiros 

## Melhores práticas

> Projeto inteiro em um CDN
> Ferramentas de construção modernas
> Compilações automatizadas - Converte o código para linguagem da maquina 
> Implementações Atômicas - Utilizar um sistema onde nenhuma operação é ativada até que todos os arquivos sejam carregados
> Invalidação de Cache Instantêneo - Verificar se o CDN faz limpeza de cache
> Tudo vive no Git 
______________________________________________________________________________________________





# Stack & Heap

## O que é Stack & Heap?

> São locais de armazenamento de dados na memoria
> O Stack tem uma capacidade menor  KB - MB
> O Heap tem uma capacidade maior MB - GB
> Trabalham com pilha de dados 
______________________________________________________________________________________________
