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
