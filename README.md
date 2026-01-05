# **Codex: A minimal multiformat LuaLaTeX template**
------------------------------------------------
## **Description**

This repository contains a flexible and minimalistic LuaLaTeX template that can be used to typeset:
- **longform** documents (theses, formal reports, ...)
- **shortform** documents (notes, assignments, ...)
- **beamer** presentations (seminars, conference presentations, ...)

The main philosophy of this project is to provide a versatile template with minimal busywork. In particular, these templates use the same preamble where documentclass-specific information is stored in class specific files.

## **Basic usage**

Copy the `Codex` repository that actually contains the template and you should be good to go! A couple basic commands are given below.

#### ***Compilation***

Go to `Codex/` and run `latexmk`. Compilation should automatically proceed by reading the `latexmkrc` file. If you have many `.tex` files in `Codex/`, the addition of a target will clear all ambiguity (e.g. `latexmk MAIN.tex`)

#### ***Cleaning***

Still in `Codex/`, run `latexmk -C` and the cleanup should also proceed automagically.

## **Contents & structure**

**Coming eventually ...**



------------------------------------------------
## ***Geneology & Credits***

This template takes its roots in a template crafted by the wise **Prof. David Sénéchal** (Université de Sherbrooke) which was forked circa 2013. More recently, it was updated by my dear friend **Jérôme Leblanc** (2025) who among many things fixed some pesky bugs and merged the template with my favorite "old faitful" template [TeX-JAM](https://github.com/LJerome94/TeX-JAM). Since I realized that I also needed to write my thesis eventually, I started working on the template, tweaking some fonts and figured that I might aswell make something that can benefit others along the way. The shortform template is simply a minor variation of the longform template. Moreover, I was directly inspired by **Antoine de Lagrave** (2025) for the choice of Libertinus as a font and for his minimal beamer template [UniTeX](https://github.com/antoinedelagrave/UniTeX).

## ***License***

GNU GPL v3 (as included).

------------------------------------------------

## ***Todo***

-
- Grand name uniformization tour
- Write the contents and structure
- Organize and partition `MAIN.tex`

#### *Priority*

- Make a clean example document for each
- Figure out what I want to do for tikz and pgfplots.

#### *Beamer*

- Fix bibliography... ugly
- Add a big section divider slide macro or figure out how to do natively.

#### *Backburner*

- Do big picture tightening
- Figure out how to do bibliographies in a modern way...
- Update subcaption.
- Add back in pdfx as a tourdeforce
- Comment uniformization

-----------------------------------------------
### Backstore

In summary, my main contributions are:
- Improving compatibility to the more modern and powerful **LuaLaTeX** (crucial for `fontspec` and `unicode-math`).
- Body in **EB Garamond**
- Math in **Libertinus Math** (with tweaks and additions)
- Flexible **colored boxes** (both in math mode and "theorem" boxes)
- More math **macros** (mostly physics oriented)
- Fixing some dicey package interactions (by nuking them)
- Making a derived shortform template to match the longform
- *coming soon :* A mathching template for making beamers that don't hurt the eyes. Inspo : **Antoine de Lagrave**'s clean an minimalist one published within [UniTeX](https://github.com/antoinedelagrave/UniTeX).
