# Titolo del documento

**Benvenuti** in questa pagina di visualizzazione di testo

![](https://raw.githubusercontent.com/cirospat/rtd-comemipiace/master/docs/images/mkdocs.png)

## struttura progetto su Github

```
.
├─ docs/
│  └─ index.md
└─ mkdocs.yml
```

## Additional CSS per modifiche allo stile delle pagine
If you want to tweak some colors or change the spacing of certain elements, you can do this in a separate stylesheet. The easiest way is by creating a new stylesheet file in the docs directory:

```
.
├─ docs/
│  └─ stylesheets/
│     └─ extra.css
└─ mkdocs.yml
```

## Additional JavaScript

The same is true for additional JavaScript. If you want to integrate another
syntax highlighter or add some custom logic to your theme, create a new
JavaScript file in the `docs` directory:

``` sh
.
├─ docs/
│  └─ javascripts/
│     └─ extra.js
└─ mkdocs.yml
```

Then, add the following line to `mkdocs.yml`:

``` yaml
extra_javascript:
  - javascripts/extra.js
```

[Altre info per customization](https://github.com/squidfunk/mkdocs-material/blob/master/docs/customization.md)


---


## Testo colorato con codice `html`

<p><span style="background-color: #6462d1; color: #ffffff; display: inline-block; padding: 3px 8px; border-radius: 10px;">Responsive</span> </p>

<p><span style="background-color: #105618; color: #ffffff; display: inline-block; padding: 3px 8px; border-radius: 10px;">Funzioni avanzate di ricerca testo</span> </p>

<p><span style="background-color: #14c9ab; color: #ffffff; display: inline-block; padding: 3px 8px; border-radius: 10px;">E' comodo</span> </p>

<p><span style="background-color: #e86514; color: #ffffff; display: inline-block; padding: 3px 8px; border-radius: 10px;">Codice sorgente del testo online su Github</span> </p>

<p><span style="background-color: #c914c0; color: #ffffff; display: inline-block; padding: 3px 8px; border-radius: 10px;">E’ elegante e bello da vedere</span> </p>


## Quote con evidenziazione

quote con `>`

e evidenziazione con {==    ==}


{==

testo

==}


risultato =


> {==
> 
> Formatting can also be applied to blocks, by putting the opening and closing tags on separate lines and adding new lines between the tags and the content. Formatting can also be applied to blocks, by putting the opening and closing tags on separate lines and adding new lines between the tags and the content.
> 
> ==}


## elenco puntato

* 1
* 2
* 3
* 4


## sottotitolo `code`

<code>technology names</code>


### sotto sottotitolo del documento

un sottotitolo con ###



#### sotto sotto sotto titolo del documento

linee di codice

```
line of code
line of code
line of code
```

Write a short description of the technologies that this workshop focuses on. Include a snazzy image, too.


### Immagine

![](https://raw.githubusercontent.com/cirospat/rtd-comemipiace/master/docs/images/mkdocs.png)


## Video

<iframe width="100%" height="500" src="https://www.youtube.com/embed/5O2D4h5hI18" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>
Breve video introduttivo (2’10”)


## Link on codice html

<div>Icons made by <a href="https://www.freepik.com" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">www.flaticon.com</a></div>


## Highlighting changes

testo cancellato, evidenziato, aggiunto

Text can be {--cancellato--} and replacement text {++aggiunto++}. This can also be
combined into {~~one~>a single~~} operation. {==**evidenziato**==} is also
possible {>>i commenti possono essere aggiunti in linea<<}.

{==

Formatting can also be applied to blocks, by putting the opening and closing tags on separate lines and adding new lines between the tags and the content.

==}

- ==questo è marked==
- ^^This was inserito^^
- ~~This was cancellato~~
- {++aggiunto++}


## Iframe

esempio di iframe
```
<iframe width="100%" height="2500px" frameBorder="0" src="https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vRrShxVf6VZYXPeHR9e3NXsYZ_x8nrE1gGTuhqao4ERRm1XDYuXBO7G4vqDkk4u96BfLRAjekwZPk3K/pubhtml?gid=0&single=true"></iframe>
```

<iframe width="100%" height="2500px" frameBorder="0" src="https://docs.google.com/spreadsheets/u/1/d/e/2PACX-1vRrShxVf6VZYXPeHR9e3NXsYZ_x8nrE1gGTuhqao4ERRm1XDYuXBO7G4vqDkk4u96BfLRAjekwZPk3K/pubhtml?gid=0&single=true"></iframe>


## annotazioni dentro un riquadro 
**non funzionano se non si è insiders del progetto MKDOCS**

=== "Material for MkDocs"

    ``` { .yaml .annotate }
    prova # (1)
    prova 2 0 Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
      
      Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.
        branches: # (2)
    ```
   
    1. You can change the name to your liking.

    2. At some point, GitHub renamed `master` to `main`. If your default branch is named `master`, you can safely remove `main`, vice versa.

    
