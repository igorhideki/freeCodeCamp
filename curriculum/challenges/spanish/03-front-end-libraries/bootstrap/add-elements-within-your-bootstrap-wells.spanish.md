---
id: bad87fee1348bd9aec908849
title: Add Elements within Your Bootstrap Wells
challengeType: 0
videoUrl: ''
localeTitle: Agrega elementos dentro de tus pozos de Bootstrap
---

## Description
<section id="description"> Ahora somos varios elementos <code>div</code> en cada columna de nuestra fila. Esto es tan profundo como tendremos que ir. Ahora podemos añadir nuestros elementos de <code>button</code> . Nido de tres <code>button</code> elementos dentro de cada uno de sus <code>well</code> <code>div</code> elementos. </section>

## Instructions
<section id="instructions">
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: Anida tres elementos de <code>button</code> dentro de cada uno de tus elementos <code>div</code> con clase <code>well</code> .
    testString: 'assert($("div.well:eq(0)").children("button").length === 3 && $("div.well:eq(1)").children("button").length === 3, "Nest three <code>button</code> elements within each of your <code>div</code> elements with class <code>well</code>.");'
  - text: Debes tener un total de 6 elementos de <code>button</code> .
    testString: 'assert($("button") && $("button").length > 5, "You should have a total of 6 <code>button</code> elements.");'
  - text: Asegúrese de que todos los elementos de sus <code>button</code> tengan etiquetas de cierre.
    testString: 'assert(code.match(/<\/button>/g) && code.match(/<button/g) && code.match(/<\/button>/g).length === code.match(/<button/g).length, "Make sure all your <code>button</code> elements have closing tags.");'

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='html-seed'>

```html
<div class="container-fluid">
  <h3 class="text-primary text-center">jQuery Playground</h3>
  <div class="row">
    <div class="col-xs-6">
      <div class="well">



      </div>
    </div>
    <div class="col-xs-6">
      <div class="well">



      </div>
    </div>
  </div>
</div>

```

</div>



</section>

## Solution
<section id='solution'>

```js
// solution required
```
</section>
