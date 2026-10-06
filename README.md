# 🧩 Ionic Formula Builder

Students discover how to write ionic formulas by assembling jigsaw-style ion pieces, then learn how to name each compound they built.

**▶ Open it:** https://tdavidsm.github.io/ionic-formula-builder/

## Tab 1: Build Formulas
- A full periodic table with the **metalloid staircase** drawn on it and the **family charges written over each column** (1+, 2+, 3+, 3−, 2−, 1−).
- Elements with more than one possible charge (most transition metals, Sn, Pb, In, Tl, Bi, H), the metalloids, and the noble gases are **grey and not available yet**. Single-charge metals such as Zn, Ag, Cd, Sc, Y, Al and Ga are available, with their charge shown in the corner.
- Tap an element to bring its ion to the workshop. Ions are simple boxes: **anions have a jigsaw tab for each negative charge** and **cations have a slot for each positive charge**.
- **+ Add another cation / + Add another anion** (or tap the same element again) give more pieces.
- A large **net charge** readout shows the sum of all the pieces.
- Drag the pieces so that every tab fits a slot. When all tabs and slots are filled and the net charge is 0, the **formula is revealed** (always the simplest ratio).
- Students must discover **six different formulas** to unlock Tab 2.

## Tab 2: Name Them
**Part 1: a worked example the student did not build.** A step-by-step animation highlights the part of the formula that supplies each part of the name:

1. The metal is named first (`Mg` → *magnesium*)
2. The nonmetal is named (`Cl` → *chlorine*)
3. The ending is dropped (*chlor~~ine~~*)
4. **-ide** is added (*chloride*)
5. The names are combined (*magnesium chloride*) and the subscripts are highlighted as **not** part of the name

Controls: Back, Play (auto-advance), Next, Replay, and **Show a different example** (always a compound the student has not found).

**Part 2: their turn.** Each formula the student discovered gets a card with a stack of boxes: **Metal Name** and **Nonmetal Name** (with the -ide ending) on one row, and the **Compound Name** below. **Check** marks each box green or red and gives a targeted hint (symbol instead of name, forgot -ide, wrong order, and so on; the hints get more specific after a few tries). Correct cards lock with a ✓, and progress is saved on the device. Alternate spellings (aluminium, caesium, sulphide) are accepted.

## Tab 3: Metals with Many Charges
An animation (with a different metal on each replay: Sn, Fe, Cu, Pb) explains why the pair of elements is not enough. Tin and oxygen can make **SnO** (Sn²⁺) or **SnO₂** (Sn⁴⁺): the same two elements, two different compounds. Calling both "tin oxide" is ambiguous, so the name carries the metal's charge as a **Roman numeral** (tin(II) oxide, tin(IV) oxide). Students must reach the last step to unlock Tab 4.

## Tab 4: Build Multi-Charge Formulas
Same periodic table and jigsaw workshop as Tab 1, but limited to the metals with more than one charge (Ti, Cr, Mn, Fe, Co, Cu, Au, Sn, Pb) plus the nonmetal anions to pair them with. Single-charge metals are grey.
- Tap a metal, then **choose which of its charges** to use. Each box shows the charges that metal can have.
- Build the compound. As soon as it's right, the workshop **automatically hands the student the metal's other charge** (same anion) to figure out.
- A finished pair is the same two elements in two different formulas (for example FeO and Fe₂O₃). Students complete **three pairs** to unlock Tab 5.

## Tab 5: Name with Roman Numerals
**Part 1:** a step-by-step, side-by-side animation for a pair the student did not build. Both compounds are named together so the difference is obvious: name the metal, find the nonmetal's total negative charge, set the metal total equal and opposite, divide by the number of metal ions to get one ion's charge, write it as a Roman numeral, then name the nonmetal with -ide.

**Part 2:** every compound in the student's pairs gets a card with **Metal Name**, **Roman Numeral**, **Nonmetal Name**, and **Compound Name** boxes. Check gives targeted hints (digit instead of a Roman numeral, lowercase numeral, wrong charge, the total-charge arithmetic after a few tries).

## Tab 6: Polyatomic Ions
An intro card shows what a polyatomic ion is (a covalently bonded group of atoms with one overall charge, drawn as sulfate in a bracket) and gives naming clues (-ate/-ite, a few -ide). Below it, a table of 17 common polyatomic ions is grouped by charge (1+, 1−, 2−, 3−), each showing its formula and name.

The student is asked, one at a time, either to **tap the ion with a given name** or **tap the ion with a given formula**. They need **5 correct from names and 5 correct from formulas**. A wrong tap does not count, shows what they tapped and the right answer, and moves on to a new question. There is no restart, and misses are only tallied for information. Progress is saved on the device.

## Completion code and turn-in
When a student has finished every tab (all formulas found and named, the Tab 3 animation, three pairs found and named, and the polyatomic ion practice), a **🏅 Get my code** button appears and a name prompt opens automatically. After they enter their name they get a completion code and a **Turn it in** button that opens the class Google Form with the Name and Code questions already filled in. The code only appears when everything is complete.

To point it at a different form, change `FORM_BASE` and `FORM_ENTRY` in `index.html`.

## Notes
- Progress (the discovered formulas) is saved on the device.
- Tabs 1–2 offer only single-charge ions, so every name follows "metal + nonmetal stem + -ide". Tabs 3–5 add the multi-charge metals and Roman numerals.
- Tabs unlock in order: 2 after six formulas, 3 after naming them all, 4 after the Tab 3 animation, 5 after three pairs, 6 after naming every compound in Tab 5.

## Tech
Single self-contained `index.html`: plain HTML/CSS/JS with a canvas workshop and Pointer Events (touch + mouse); no dependencies. Built for iPad Safari. Deployed via GitHub Pages from `main`.
