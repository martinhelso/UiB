# UiB
Beamer theme for the University of Bergen

Available on [Overleaf](https://www.overleaf.com/latex/templates/uib-beamer-theme/ddsnzprthmfv).

![Image of first slide](https://i.imgur.com/PFPWBvN.png)

## Logo
The logo in the lower right corner can be removed from a specific `frame`
using the macro `\hidelogo` outside of the `frame` like this:
```LaTeX
\hidelogo
\begin{frame}
    ...
\end{frame}
```
Use `\showlogo` in the same manner to make the logo appear again. 

## Section page
The command `\SectionPage` inserts a `[NoFrameNumbering, plain]` frame
with red background issuing the `\sectionpage` command.
The command `\SectionPage` is used outside of a `frame`,
unlike `\sectionpage`. 

## Enumerated references
The command `\enumref` inserts a reference to an enumerated item
in the shape of a red box,
like the ones used in the `enumerate` environment.

## Options
Options are given as
```LaTeX
\usetheme[option]{UiB}
```

### Font
By default,
almost all text is typeset in a sans serif.
The option `MathSerif` enables serifs for mathematical symbols,
whereas `Serif` enables serifs for all text.

### Numbered environments
By default,
the environments listed below are unnumbered.
The option `numbered` adds numbers,
whereas `AMS` adds numbers and typesets the environment names
in the style of the American Mathematical Society.

### Title frame
Presentations automatically start with a title frame.
It can be disabled with the option `NoTitlePage`.

### Language
If one of the options
* `american`
* `english`
* `UKenglish`
* `USenglish`
* `norsk`
* `nynorsk`

are given,
the environments listed below are translated into the specified language.

## Environments
An _environment_ is initialized with
```LaTeX
\begin{environment}
    ...
\end{environment}
```
The following environments are predefined by `beamer`:
* `corollary`
* `definition`
* `definitions`
* `example`
* `examples`
* `fact`
* `lemma`
* `theorem`

In addition, `UiB` defines these environments:
* `assumption`
* `axiom`
* `calculation`
* `computation`
* `conjecture`
* `facts`
* `hypothesis`
* `notation`
* `observation`
* `proposition`
* `property`
* `remark`
* `remarks`
