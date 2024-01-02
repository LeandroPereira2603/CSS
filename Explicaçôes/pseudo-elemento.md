

<p> Pseudoelementos são como elementos virtuais que podem ser tratados como elementos regulares da marcação HTML. Contudo, eles não existem na árvore do documento (no DOM) pois são criados com uso de CSS. Alguns pseudoelementos mais conhecidos são: :after , :before e :first-letter </p>

<p> vai deixar o background laranja de todos os parágrafos exceto o id ="missao" </p>

```css

.principal p:not(#missao){
    background-color: orange;
}

```

vai colocar a estrela antes de li

```css
.li:before{
    content: "⭐";
}

```


vai colocar a estrela depois de li

```css

.li:after{
    content: "⭐";
}

```

