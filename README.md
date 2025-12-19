# **Codex: A minimal multiformat LuaLaTeX template**

## ***Description***

***Update this description to add the fact that there are a couple templates now***

This repository contains a latex template is meant for those that wish to typeset a longform document (thesis, memoir *etc*). This template takes its roots in a template produced by Prof. David Sénéchal (2013) and was more recently modified into its current form by my dear friend Jérôme Leblanc (2025).

In summary, my main contributions are:
- Improving compatibility to the more modern and powerful **LuaLaTeX**
- Main text in **EB Garamond** (beautiful and traditional open source font)
- Math in **Libertinus Math** (neutral font with good overall support)
- Flexible colored boxes (both in math mode and "theorem" boxes)
- More math macros and minor fixes
- Adding a shortform version of the template for notes, assignments and others...

---
***Geneology & Credits*** 

This repository contains a latex template is meant for those that wish to typeset a longform document (thesis, memoir *etc*). This template takes its roots in a template produced by Prof. David Sénéchal (2013) and was more recently modified into its current form by my dear friend Jérôme Leblanc (2025).

In summary, my main contributions are:
- Improving compatibility to the more modern and powerful **LuaLaTeX**
- Main text in **EB Garamond** (beautiful and traditional open source font)
- Math in **Libertinus Math** (neutral font with good overall support)
- Flexible colored boxes (both in math mode and "theorem" boxes)
- More math macros and minor fixes
- Adding a shortform version of the template for notes, assignments and others...

## ***Basic usage***

Copy the `Codex` repository that actually contains the template and you should be good to go! A couple basic commands are given below.

#### **Compilation**

Go to `./Codex/` and run `latexmk`. Compilation should automatically proceed by reading the `latexmkrc` file.

#### **Cleaning**

Still in `./Codex/`, run `latexmk -C` and the cleanup should also proceed automagically.

## ***Contents & structure***

**Coming eventually**

## ***License***

Consult `LICENSE.md`

## *Todo*
- Grand name uniformization tour
- Write the contents and structure
- Organize and partition `MAIN.tex`

#### *Priority*

- Merge macros from the examprep and the tight bibliographyfix
- Move examples into a separate section (requires directory awareness I think)
- Make a crispy template-ish MAIN.tex that can be compiled and easily switched.


- Crisp up `math_macros.sty`
- Crisp up both layout documents
- Crisp up colorscheme document
- Modularize font choices?
- Make sure everything is language supported

#### *Backburner*

- Figure out how to do bibliographies in a modern way...
- Figure out what I want to do for tikz and pgfplots.
- Update subcaption.
- Add back in pdfx as a tourdeforce
- Do big picture tightening
