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
Uses only the formulas the student actually discovered. A step-by-step animation highlights the part of the formula that supplies each part of the name:

1. The metal is named first (`Mg` → *magnesium*)
2. The nonmetal is named (`Cl` → *chlorine*)
3. The ending is dropped (*chlor~~ine~~*)
4. **-ide** is added (*chloride*)
5. The names are combined (*magnesium chloride*) and the subscripts are highlighted as **not** part of the name

Controls: Back, Play (auto-advance), Next, Replay.

## Notes
- Progress (the discovered formulas) is saved on the device.
- Only single-charge ions are offered, so every name follows "metal + nonmetal stem + -ide".

## Tech
Single self-contained `index.html`: plain HTML/CSS/JS with a canvas workshop and Pointer Events (touch + mouse); no dependencies. Built for iPad Safari. Deployed via GitHub Pages from `main`.
