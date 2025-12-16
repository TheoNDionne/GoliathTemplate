# **Codex: A minimal template for typesetting longform documents in latex**

## ***Description***

This repository contains a latex template is meant for those that wish to typeset a longform document (thesis, memoir *etc*). This template takes its roots in a template produced by Prof. David Sénéchal (2013) and was more recently modified into its current form by my dear friend Jérôme Leblanc (2025).

In summary, my main contributions are:
- Improving compatibility to the more modern and powerful **LuaLaTeX**
- Main text in **EB Garamond** (beautiful and traditional open source font)
- Math in **Libertinus Math** (neutral font with good overall support)
- Flexible colored boxes (both in math mode and "theorem" boxes)
- More math macros and minor fixes

## ***Basic usage***

Copy the `Codex` repository that actually contains the template and you should be good to go! A couple basic commands are given below.

#### **Compilation**

Go to `./Codex/` and run `latexmk`. Compilation should automatically proceed by reading the `latexmkrc` file.

#### **Cleaning**

Still in `./Codex/`, run `latexmk -c` and the cleanup should also proceed automagically. For nuclear cleanup `rm -r build/`.

## ***Contents & structure***

**Coming eventually**

## ***License***

Consult `LICENSE.md`

## *Todo*
- Grand name uniformization tour
- Write the contents and structure
- Organize and partition `MAIN.tex`

#### *Priority*

- Comment math macros
- Order and comment in layout.sty
- Make sure everything is language supported

#### *Backburner*

- Figure out how to do bibliographies in a modern way...
- Figure out what I want to do for tikz and pgfplots.
- Update subcaption.
- Add back in pdfx as a tourdeforce

## ***Coming next***

Currently in the experimental branch! Demon time...
- Make the boxes follow the style... I want the least possible goofy ahh comments/uncomments in the release version
- Merge the fixed macros into main
- Merge the fixed fonts into main
- Merge the fixed style for section/subsections into main
- Merge the bibliography fix, really nice. addcaption or whatever...

The short form version of this template! (once all except backburner is done)
