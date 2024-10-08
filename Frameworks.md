# Framework

## O que é Framework

> Os frameworks fazem parte do desenvolvimento de software, seja ele desktop, mobile ou web. 
> Um framework é uma coleção de classes abstratas, objetos e padrões dedicados a resolver determinado problema em uma arquitetura flexível e extensível. 
> Os frameworks contêm várias bibliotecas.

## Frameworks Front-End

Foundation

Materialize 

Angular

Vue ✔️

Nuxt (Framework feito em Vue)

Astro ✔️

Svelt

Nue

Tailwind (CSS)

Bootstrap (CSS)

Bulma (CSS)



## Frameworks para Back-End

Laravel (PHP)

Codelgniter (PHP)

Rail (Ruby)

.NET Framework (Plataforma .NET)

Django (Python)

Express (Node.js)

Ionic (Aplicativos Mobile)

Struts (Java)
______________________________________________________________________________________________



# Vue.js

## O que é o Vue.js?

> É um framework JavaScript para a criação de componentes de interface de usuário. 
> Também é uma Single Page Application, que são aplicações de página única. 
> Referenciado como um framework **reativo e progressivo**. 
> É possível utilizar o Vue em toda a aplicação e em partes da aplicação. 
> Possui uma sintaxe simples. 
> No Vue, é bastante utilizado o conceito de componentização. 
> Outra peculiaridade do Vue são os chamados Single File Components. 
> O Vue não precisa trabalhar com outras bibliotecas em conjunto.

 
``` 
// HTML
<div id = "app"> 
    <h1>{{ product }}</h1>
</div> 
```

```
//JS
let app = new Vue({
    el: '#app',
    data: {
        product: 'Socks'
    }
})
```

## Tags

**Data** = O data é o local onde será declarado as variáveis utilizadas ao longo da criação do componete

**Watch** = Executa algo quando a variavel que é referencida sofre alguma alteração

**Computed** = São funções computadas ou seja, sempre que alguma dependencia(variaveis dentro da função) sofre alteração, a função é ativa novamente, trocando os valores antigos pelos novos  

______________________________________________________________________________________________

**v-bind** = Utilizado para vincular o valor de uma propriedade do objeto data.

**v-if/v-else** = Fazem a validação "se", "senão"

**v-for** = Lembra o forEach

**v-on:click** = Realiza algo quando clicado

**@click** = Realiza algo quando clicado

**key** = 

**@mouseover** = Realiza algo quando o mouse passa em cima

**@submit** = Envia informações de um formulário

**@keyup.enter** = É quando a tecla do formulário é liberada 

**.enter** = Tags como essa são chamadas de Modifier 



## Two-Way Data Biding

> É uma caracteristica do Vue, que sincroniza a interface com o model.
> Sempre que há uma alteração na interface havera alteração no model e vice versa.


## Conceitos de reatividade e progressividade - Vue.js

> REATIVIDADE: Diz respeito a arquitetura, que atualiza a camada visual cada vez que se tem uma mudança de estado.
> O HTML será atualizado toda vez que o valor de uma variavel de um componente no Vue for alterada.

> PROGRESSIVIDADE: Significa que foi projetado para ser altamente adaptável a outros frameworks e bibliotecas.
> É possível utilizar o Vue.js em apenas uma parte da aplicação que já está desenvolvido.

## Conceito de Componentização - Vue.js

> É a divisão do código em partes menores, cada uma focada em um componente específico
> A componentização traz benefícios como a diminuição da complexidade do código, facilitando sua manutenção e reutilização

## Single File Components - Vue.js

> Realiza a separação de cada componente dentro de um arquivo com extenção .vue
> Para realizar a leitura desses arquivos é necessario um webpack para transformar o código em JavaScript

## Links

([Link Documentação Vue.js](https://vuejs.org/))

> Canal - Código Fonte TV
([Link Vídeo Auxiliar](https://youtu.be/bEl6yN3vd-U?si=XbQ9WUJbRrxPfMKs))

> Canal - Caraline
([Link Vídeo Auxiliar](https://youtu.be/1W35ITPUp6Y?si=l8gAnMSuwsHzUGJO))
______________________________________________________________________________________________



# Astro

## O que é o Astro?

> Astro é um Static Site Builder(Gerador estático de site)
> O Astro possui Hidratação Parcial 
> Por padrão o Astro faz build de todo projeto sem código JS no client side 
> No momento da compilação será renderizado o HTML Removendo todo JS

## O que é Hidratação Parcial - Astro

> Hidratação Parcial seria a eliminação de código não usado e fazer utilização do que realmente é necessário
> A Hidratação Parcial pode ser chamada também de Arquitetura de Ilhas
> Na Arquitetura de Ilhas a ideia geral é renderizar páginas HTML no servidor como ilhas de interatividade, que podem ser hidratadas de maneira independente 
> Ao hidratar componentes individualmente na página, somente JS que seja essencial vai rodar no client side  

## Links

([Link Documentação Astro](https://astro.build/))

> Canal - dpw
([Link Vídeo Auxiliar](https://youtu.be/jIg0b_lAJss?si=75eZVZdZ46VYqW3t))
______________________________________________________________________________________________



 
