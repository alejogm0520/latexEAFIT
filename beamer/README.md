
# EAFIT beamer template

## Usage

### Affiliation

To specify the affiliation, we can use `\affiliation{...}` command:

```latex
\affiliation{
	Universidad EAFIT\\
	Escuela de Ciencias\\
	Departamento de Ciencias Matemáticas\\
	Maestría en Matemáticas Aplicadas}
```

### Language

To specify the language of the slides, write this:

```latex
\usetheme[language=EN]{EAFIT}
```

- Use the option `language=EN` to set the beamer theme in English.
- Use the option `language=ES` to set the beamer theme in Spanish.

### Colors

There are some color schemes by default that user can use:

```latex
\usetheme[color=white]{EAFIT}
```

- Use the option `color=white` to set the background in white and
the bottom bar in blue.

- Use the option `color=blue` to set the background in blue and
the bottom bar in white.

- Use the option `color=blue2` to set the background in blue and
the bottom bar in blue.


### Font Color

```latex
\usetheme[fontc=black]{EAFIT}
```

Use the option `fontc=black` to set the font color in black. If this
argument is not given the default color is set depending of the
color scheme selected.

### Table of contents

This command help to add the Table of Contents (ToC) frame:

```latex
\makeToC
```

- The ToC title is  `Outline` when `language=EN`.
- The ToC title is  `Contenido` when `language=ES`.
- A custom ToC title is possible through the option:

	```latex
	\makeToC[Custom Title]
	```


