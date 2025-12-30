# **Codex: A minimal multiformat LuaLaTeX template**
------------------------------------------------
## ***Description***

This repository contains a relatively flexible and minimalistic LuaLaTeX template that can be used to typeset both longform documents (theses, formal reports *etc*.) and shortform documents (notes, assignments *etc.*).

The main philosophy of this project is to provide a pragmatic hierarchy of customization layers allowing one to tweak and improve this template with minimal busywork in any way. Additionaly, these templates have been designed to use more or less the same preamble (where all necessary differences are assigned modularly) in order to keep all templates coordinated.

## ***Basic usage***

Copy the `Codex` repository that actually contains the template and you should be good to go! A couple basic commands are given below.

#### **Compilation**

Go to `Codex/` and run `latexmk`. Compilation should automatically proceed by reading the `latexmkrc` file. If you have many `.tex` files in `Codex/`, the addition of a target will clear all ambiguity (e.g. `latexmk MAIN.tex`)

#### **Cleaning**

Still in `Codex/`, run `latexmk -C` and the cleanup should also proceed automagically.

## ***Contents & structure***

**Coming eventually**

------------------------------------------------
## ***Geneology & Credits***

This template takes its roots in a template crafted by the wise **Prof. David Sénéchal** (Université de Sherbrooke) which was forked circa 2013. More recently, it was updated by my dear friend **Jérôme Leblanc** (2025) who among many things fixed some pesky bugs and merged the template with my favorite "old faitful" template [TeX-JAM](https://github.com/LJerome94/TeX-JAM). Since I realized that I also needed to write my thesis eventually, I started working on the template, tweaking some fonts and figured that I might aswell make something that can benefit others along the way.

## ***License***

GNU GPL v3 (as included).

------------------------------------------------

## ***Todo***

- ***Coming soon*** A crispy beamer template.

- Grand name uniformization tour
- Write the contents and structure
- Organize and partition `MAIN.tex`
- Make a development branch and a main for public...

#### *Priority*

- Move examples into a separate section (requires directory awareness I think)

- Make sure that the colors are defined right.
- Crisp up `math_macros.sty`
- Crisp up both layout documents
- Crisp up colorscheme document

#### *Backburner*

- Figure out how to do bibliographies in a modern way...
- Figure out what I want to do for tikz and pgfplots.
- Update subcaption.
- Add back in pdfx as a tourdeforce
- Do big picture tightening

-----------------------------------------------
### Backstore

In summary, my main contributions are:
- Improving compatibility to the more modern and powerful **LuaLaTeX** (crucial for `fontspec` and `unicode-math`).
- Body in **EB Garamond**
- Math in **Libertinus Math** (with tweaks and additions)
- Flexible **colored boxes** (both in math mode and "theorem" boxes)
- More math **macros** (mostly physics oriented)
- Fixing some dicey package interactions (by nuking them)
- Making a derived
- *coming soon :* A mathching template for making beamers that don't hurt the eyes. Inspo : **Antoine de Lagrave**'s clean an minimalist one published within [UniTeX](https://github.com/antoinedelagrave/UniTeX).
