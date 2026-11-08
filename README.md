<img src="icon.png" width="64" height="64" alt="">

# MathGen

A free equation editor for Windows, made for students and teachers, with a
step-by-step solver, a scientific calculator with graphs, 36 maths tools, a
Board for lessons and Live lessons for the whole class. Type equations with the keyboard and toolbars, then
paste them into your documents and slides. No account, no adverts, and no
data collected.

## Download

**From the Microsoft Store (easiest):**
**[Get MathGen from the Microsoft Store](https://apps.microsoft.com/detail/9PPJ9XLT2V3B)**.
It installs and updates itself, needs no administrator rights, and Windows
shows no warning. It is the full version; for exam PCs, use the installer
below.

Or get the newest version from the **[Releases page](https://github.com/Thedevelop3r/MathGen-Releases/releases/latest)**:

- **`MathGen-…-x64.msi`**: the installer. Its first page asks for the
  **full version** or the version **for exams** (see below). Adds MathGen
  to the Start menu and opens `.mgq` equation and `.mgb` board files.
  Uninstall from Settings → Apps.
- **`MathGen-…-portable-x64.zip`**: the full version with no installation
  and no administrator rights. Unzip anywhere (a USB stick works) and run
  `mathgen.exe`.
- **`MathGen-…-exam-portable-x64.zip`**: the exam version without
  installing (for exams, install it instead: see below).
- **`SHA256SUMS.txt`**: checksums, to check that a download is complete and
  unchanged.

Needs Windows 10 or 11 (64-bit), and nothing else: no extra runtimes to
install.

If Windows shows **"Windows protected your PC"** for the installer or a zip,
choose **More info → Run anyway**. Windows shows this for new programs that
few people have downloaded yet. The
[Microsoft Store version](https://apps.microsoft.com/detail/9PPJ9XLT2V3B)
installs without this warning.

Press **F1** in MathGen for the Quick Start guide, and **Ctrl+K** to find
any command, symbol, formula or tool.

## What it does

- **Equations**: fractions, roots, scripts, brackets that grow, sums,
  integrals, limits, matrices, piecewise functions, accents, boxes, arrows
  and aligned multi-line working, typeset to textbook quality (New Computer
  Modern fonts, OpenType MATH).
- **Calculator tab**: a scientific calculator with a textbook display
  (fractions, roots, powers, Σ, ∫ and d/dx as they are written), exact
  answers, 13 modes, over 400 functions, constants and conversions, and
  graphs with roots, turning points, crossings and areas.
- **Step-by-step solver**: equations, inequalities, simultaneous equations,
  calculus, differential equations and matrices, with every step explained
  and checked.
- **36 tools (Ctrl+T)**: calculator, fractions, units, number bases; a
  function grapher, tables of values, polynomials and sequences; areas,
  volumes, a triangle solver, the unit circle and constructions; statistics,
  charts and probability; matrices and vectors; formula sheets and the
  periodic table; a timer and a class picker.
- **The Board**: equations, notes and ink on an endless board, with a
  protractor, ruler, set squares and compasses; snapshots, full-screen
  presenting and printing.
- **Live lessons**: share your MathGen with up to 200 students, who join
  with a code; choose who comes in, save your class, and run quick polls.
- **With your documents**: copy as an editable equation for word processors
  and presentations, as a sharp picture for web apps, or as **LaTeX** or
  **MathML**; type or paste LaTeX; export PNG, SVG and EMF.
- **For everyone**: English and Urdu interface, three themes (Night, Paper,
  High contrast), interface sizes up to 250 %, customisable shortcuts, full
  keyboard use, and autosave with recovery after a crash.

## For exams

The installer's **Install for exams** puts a separate exam program on the PC:
the editor, the Board, copy, paste, export and print, but no solver, no
tools, no Live lessons and no network code at all. Windows Firewall blocks
it both ways, and its title bar always says **EXAM EDITION**. Schools can
allow the formula library, stamp exported pictures with the student's name
and ID, forget recent files when it closes, and allow the calculator (with
or without graphs). For a lab, install it silently:

```
msiexec /i MathGen-5.1.0.120-x64.msi EDITION=exam /qn
```

and add `ALLOWFORMULAS=1`, `STAMPEXPORTS=1`, `CLEARONEXIT=1`,
`ALLOWCALCULATOR=1` or `ALLOWGRAPHS=1` to turn those options on.

## Help and feedback

Found a bug, have an idea, or want to correct or add a translation?
[Open an issue](https://github.com/Thedevelop3r/MathGen-Releases/issues/new/choose).
Please include the version from Help → About MathGen.

## Licence

MathGen is freeware: free to use, for anyone, and free to share unchanged.
See [LICENSE.txt](LICENSE.txt). It includes open-source components and fonts
under their own licences, listed in `THIRD_PARTY_LICENSES.txt` in every
download. Privacy: [PRIVACY.md](PRIVACY.md) (nothing is sent to the
publisher; Live lessons connect only the teacher's and students' computers).

MathGen is an independent project, not affiliated with other equation editors.

Published by [Bilal Amjad](https://github.com/Thedevelop3r).
