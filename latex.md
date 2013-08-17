Latex
=====

TeX

 - computer program for typesetting documents, 
 - created by D. E. Knuth
 
LaTeX
 
 - written by L. B. Lamport
 - `dialects' of TeX
 - suited to the production of long articles and books
 - facilities for the automatic numbering of chapters, sections, theorems, equations etc
 -  facilities for cross-referencing
 - LaTeX2e, released in 1994

Books on Latex

 - LaTeX User's Guide and Reference Manual by Leslie Lamport
 - The LaTeX Companion by Michel Goossens, Frank Mittelbach and Alexander Samarin.

The LaTeX program 

 - reads in text from a suitably prepared input file, and 
 - creates a `DVI file' which
    - encodes information on the fonts to be used and the
    - positioning of the characters on the printed page.

Characters and Control Sequences
--------------------------------

the characters `\ { } $ ^ _ % ~ # &` are used for special purposes within LaTeX. 

`control sequences` consist of 

 - a backslash \ followed by a string of (upper or lower case) letters
   - eg. `\delta`, `\emph`
 - backslash followed by a single character that is not a letter
   - eg. `\{`, `\"`, `\$`
   
`{` and `}` are used for grouping

`$` is used when embedding mathematical expressions in paragraphs of ordinary text

 `^` and `_` are used in mathematical expressions to produce superscripts and subscripts respectively
 
 `%` is used to introduce comments 

`#` is used to specify arguments in definitions of control sequences. 

 `&` is used when typesetting tables in order to separate entries in different columns.


Producing Simple Documents using LaTeX
----------------------------

 first line of the input file should normally consist of an appropriate `\documentclass[a4paper,12pt]{article}` command
 
  - article, letters, reports, books, etc
 
optional commands, such as the `\pagestyle` command
 
`\begin{document}`
 
main body of the text
 
`\end{document}`
 
 
LaTeX will automatically indent all paragraphs with the exception of the first paragraph of a new section.

blank space equivalent
  - carriage return at the end of a line
  - tab characters as blank spaces
  - a sequence of blank spaces as though it were a single space
  -
Ignores blank spaces at the beginning or end of a line

Any spaces which follow a control sequence will be ignored by LaTeX.

A blank space should not occur in the input file after a left parenthesis or before a right parenthesis.

Single quotation marks are produced in LaTeX using ` and '

Double quotation marks are produced by typing `` and ''

 hyphens -
 en-dashes --
 em-dashes ---
 
use the control sequence \, between the quotation marks, so as to obtain the necessary amount of separation.

`\section`,`\subsection` and `\subsubsection`

  - Other document styles have other `sectioning' commands availableeg. the book style has a `\chapter` 
  - `\section*{Section Headings}` suppress the automatic numbering 

`\emph{text}` 

`\textbf{text}`

    \tiny, \scriptsize, \footnotesize, \small, \normalsize, \large, \Large, \LARGE, \huge, \HUGE
    
`\textrm`   Roman family
`\textsf`   Sans serif family
`\texttt`   Typewriter family

`\textup`   Upright shape
`\textit`   Italic shape
`\textsl`   Slanted shape
`\textsc`   Small caps shape

`\textmd`   Medium series
`\textbf`   Boldface series




 
 






