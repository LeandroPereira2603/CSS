

<p> Pseudoelementos são como elementos virtuais que podem ser tratados como elementos regulares da marcação HTML. Contudo, eles não existem na árvore do documento (no DOM) pois são criados com uso de CSS. Alguns pseudoelementos mais conhecidos são: :after , :before e :first-letter </p>

```css

.principal p:not(#missao){
    background-color: orange;
}

/* O Pseudoelemento :not ira mudar o estilo da
propriedade background laranja de todos os
parágrafos , exceto o id ="missao".         */

```

```css

.li:before{
    content: "⭐";
}

/* Vai incluir o texto , depois do espaço li*/

```

```css

.li:after{
    content: "⭐";
}

/* vai colocar o texto  ,depois da classe li*/

```

