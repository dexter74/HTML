## Formatez du texte


#### Une taille absolue
```html
<p>MON TEXTE</p>
```

```css
p
 {
 font-size: 35px;
 }
```


-------------------------------------------------------------------------------------------
### Une valeur relative

```html
<p>MON TEXTE</p>
```

```css
p
{
    font-size: small; 
}

/* xx-small : minuscule   */
/* x-small  : très petit  */
/* small    : petit       */
/* medium   : moyen       */
/* large    : grand       */
/* x-large  : très grand  */
/* xx-large : Gigantesque */
```

-------------------------------------------------------------------------------------------
#### La Police
```html
<p>MON TEXTE</p>
```

```css
p
 {
 font-family: CourierNew, Arial, verdana;
 }

/* serif (Défaut)    */
/* Arial             */
/* "Arial Black"     */
/* "Comic Sans MS"   */
/* "Courier New"     */
/* Georgia           */
/* Impact            */
/* "Times New Roman" */
/* "Trebuchet MS"    */
/* Verdana           */
```

-------------------------------------------------------------------------------------------
#### Utiliser une police personnalisée 

```html
<p>MON TEXTE</p>
```

```css
/* Déclarer la POLICE */
@font-face {
 font-family: "MAPOLICE";
 src: url("Courage Road.otf") format('opentype');
 src: url("Courage Road.ttf") format('truetype');
}

/* Utilisation de la police */
p
 {
 font-family: MAPOLICE, "arial black";
 }
```

-------------------------------------------------------------------------------------------
#### Normal, Italique et Gras

```html
<p>MON TEXTE</p>
```

```css
p
{
    font-style: normal; /* normal, italic */
    font-weight: bold;
}





```

-------------------------------------------------------------------------------------------
#### Soulignement et autres décorations

```html
<p>MON TEXTE</p>
```

```css
p
{
 text-decoration: blink;
}

/* blink        - Normal              */
/* underline    - Surligné au dessous */
/* line-through - Barré               */
/* overline     - Surligné au dessus  */
```


-------------------------------------------------------------------------------------------
#### L'alignement

```html
<p>MON TEXTE</p>
```

```css
p
{
 text-align: center; /* left, center,right, right, justify */
}


```

-------------------------------------------------------------------------------------------
#### 

```html
```

```css

```

-------------------------------------------------------------------------------------------
#### 

```html
```

```css
```

-------------------------------------------------------------------------------------------
#### 

```html
```

```css
```

-------------------------------------------------------------------------------------------
#### 

```html
```

```css
```

-------------------------------------------------------------------------------------------
#### 

```html
```

```css
```

-------------------------------------------------------------------------------------------
#### Les flottants

```html
<p><img src="flash.gif" class="imageflottante" alt="Image flottante" /> Ceci est un texte normal de paragraphe, écrit à la suite de l'image et qui l'habillera car l'image est flottante.</p>
```

```css
.imageflottante
{
    float: left;
}
```
