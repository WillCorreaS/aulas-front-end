# aulas-front-end
 Atividades de estudos Front-End (HTML, CSS e JAVASCRIPT) -Senac

 # Anotações sobre Front-End

Atividades de estudo de HTML e CSS.

## HTML

- Estruturação
- Semântica
- Padrões Web

## CSS

Linguagem de estilização que "casa" com elementos HTML.

Em geral, CSS serve para:

1. Estilos de vários tipos (cores, sombra, borda etc)
2. Alinhamentos e espaçamentos
3. Design Responsivo
4. Animações e efeitos especiais de interação

### Formas de implementação

#### Inline

O CSS é aplicado diretamente em cada tag HTML.

#### Interna/OnPage

O CSS é criado usando regras (com seletores, propriedades, valores) dentro da própria página que queremos formatar.

As regras vão valer para todos os elementos/tags desta página.

##### Como fazer uma regra CSS?
```css
seletor { propriedade: valor; }

seletor {
    propriedade1: valor;
    propriedade2: valor;
    propriedadeN: valor;
}
```
#### Externa (mais usada!)

É criado um arquivo de extensão CSS dedicado às regras de formatação. Este arquivo é então "conectado" às páginas HTML.


#### Tipos de Seletores 

- TAG: Seletor generalista, casa com elementos HTML comuma tag especificada.

- Descendente: Seletor mais espedífico, casa com elementos que são filhas. Usa-se espaço para separar tags Pai/Filhas.

- Agrupado: Grupo de seletores que compartilha uma mesma formatação. Usa-se ' , ' para separar os elementos.

- Pseudo-Classe: Classes "pré-prontas/nativas" da linguagem que podem ser usadas em diversas situações. Ex: passar o mauses, reconhecer o foco, selecionar determinados elementos etc. Todas Pseudo-Classes começão com ' : '

- Classe: Seletor versátil que permite a aplicação de estilos em diversos elementos, possibilitando também a combinação de diferentes classes. No CSS usa-se '.nome-da-classe' para criar a classe, no html usa-se o 'atributo classe= nome-da-classe' para aplicar a classe.

- Identificado (ID): seletor bastante restrito (o mesmo id só pode ser usado em um elemento por página), permitindo criar uma estilização altamente específica. No CSS usa-se '#nome-do-id' para criar, e no HTML usa-se 'atributo id= nome-do-id' para aplicar.

*****************************************************************************************

### date 14.03.2024

- Pseudo-Elemento: categorizado com o uso de ' :: '

#### Web Disign Responsivo

- Mobile First (desenvolvido primeiramente para telas pequenas - Celulares, tablets)
        Nesta abordagem o desenvolvimento é focado <b>primeiro em telas pequenas</b>, para somente depois realizarmos em telas grandes


- Desktop First (desenvolvido primeiramente para telas grandes - Computadores) 
        Nesta abordagem o desenvolvimento é focado <b>primeiro em telas grandes</b>, para somente depois realizarmos em telas pequenas


Mídia Quéries (consultas de mídias)/*estilos que serão aplicados em determinadas condições dependendo do uso de telas (neste exemplo que estamos usando designe responsivo)*/
    @media 


#### Estrutu Básica de HTML para CSS ####


''<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Layout Responsivo</title>
</head>

<body>
    <div class="container">

        <header class="topo">

            <h1>Site Exemplo</h1>

            <nav class="menu">
                <a href="">Link</a>
                <a href="">Link</a>
                <a href="">Link</a>
            </nav>

        </header>

        <main class="conteudo">

            <article class="um">
                <h2>Um</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut beatae, sunt temporibus doloremque neque vitae aliquam omnis, vel consequuntur laudantium, quae repellendus possimus modi eaque officiis ducimus fugit similique nulla.</p>
            </article>

            <article class="dois">
                <h2>Dois</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut beatae, sunt temporibus doloremque neque vitae aliquam omnis, vel consequuntur laudantium, quae repellendus possimus modi eaque officiis ducimus fugit similique nulla.</p>
            </article>

            <article class="tres">
                <h2>Tres</h2>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ut beatae, sunt temporibus doloremque neque vitae aliquam omnis, vel consequuntur laudantium, quae repellendus possimus modi eaque officiis ducimus fugit similique nulla.</p>
            </article>

        </main>

        <footer>
            <h2>Rodapé</h2>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Similique, recusandae!</p>
        </footer>
        
    </div>
</body>

</html>''


###### Utilizando Flex-Box ######

-display:flex = utilizado para habilitar o uso dos atributos do Flex-box


