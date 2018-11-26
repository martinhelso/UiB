# UiB
Beamer theme for the University of Bergen

## Options
Options are given as
```LaTeX
\usetheme[option]{UiB}
```

### Font
By default, almost all text is typeset in a sans serif. The option `MathSerif` enables serifs for mathematical symbols, whereas `Serif` enables serifs for all text.

### Numbered environments
By default, the environments listed below are unnumbered. The option `numbered` adds numbers, whereas `AMS` adds numbers and typesets the environment names in the style of the American Mathematical Society.

### Title frame and final frame
Presentations automatically start with a title frame and a closing frame. Either one of them can be disabled with the options `NoTitlePage` or `NoFinalFrame`.

### Language
If one of the options
* `american`
* `english`
* `UKenglish`
* `USenglish`
* `norsk`
* `nynorsk`

are given, the environments listed below are translated into the specified language.

## Emblem
The emblem in the lower right corner can be removed from a specific `frame` using the macro `\nologo` like this:
```LaTeX
\nologo
{
    \begin{frame}
        ...
    \end{frame}
}
```

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

## Dependencies
`UiB` imports the following packages:
* `babel`
* `calc`
* `etoolbox`
* `fontenc`
* `gfsneohellenic`
* `inputenx`
* `thmtools`
* `tikz`
