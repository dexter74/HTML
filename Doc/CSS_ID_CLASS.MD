#### Des commentaires dans du CSS

```css
/* Mon Commentaire */ 
```

------------------------------------------------------------------------------------------

## Appliquer un style : sélectionner une balise

#### Le style dans le HTML

```html
<p style="color: blue;">Bonjour et bienvenue sur mon site !</p>
```

#### Le style dans un CSS:
```html
<p>TEST</p>
<em>TEST 2</em>
```

```css
p
 {
 color: blue;
 }


p, em
{
    color: blue;
}
```

------------------------------------------------------------------------------------------

## Appliquer un style : class

```html
<p class="introduction">Bonjour et bienvenue sur mon site !</p>
```

```css
.introduction

{
    color: blue;
}
```


------------------------------------------------------------------------------------------

## Appliquer un style : ID

```html
<p id="introduction">Bonjour et bienvenue sur mon site !</p>
```

```css
#introduction
{
    background: black;
}
```

