# Codex: A minimal template for typesetting longform documents in latex

## Description

This repository contains a latex template is meant for those that wish to typeset a longform document (thesis, memoir *etc*). This template takes its roots in a template produced by Prof. David Sénéchal (2013) and was more recently modified into its current form by my dear friend Jérôme Leblanc (2025).

In summary, my main contributions are:
- Improving compatibility to the more modern and powerful **LuaLaTeX**
- Main text in **EB Garamond** (beautiful and traditional open source font)
- Math in **Libertinus Math** (neutral font with good overall support)
- Flexible colored boxes (both in math mode and "theorem" boxes)
- More math macros and minor fixes

## Basic usage

#### **Compilation**

Go to `./Codex/` and run `latexmk`. Compilation should automatically proceed by reading the `latexmkrc` file.

#### **Cleaning**

Still in `./Codex/`, run `latexmk -c` and the cleanup should also proceed automagically. For nuclear cleanup `rm -r build/`.

## Contents & structure

**Coming eventually**

## License

Consult `LICENSE.md`

### *Todo*
- Write the contents and structure
- Clean up comments and structure of preamble chain
- Organize and partition `MAIN.tex`
- Finish migrating preamble stuff to `preambles/`
- Rethink the structure of the preambles for the least possible brain fuckery.
