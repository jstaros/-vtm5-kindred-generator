# VTM V5 Kindred Character Builder

A browser-based character creator for **Vampire: The Masquerade (5th Edition)**.
Create and customize Kindred characters, allocate attributes and skills with point budgets, select clans, generations, and Disciplines, and export a **fillable PDF** character sheet — all directly in the browser.

---

## Features

* **Complete Clan Support**
  Includes all core and expanded clans: Brujah, Gangrel, Malkavian, Nosferatu, Toreador, Tremere, Ventrue, Caitiff, Banu Haqim, Hecata, Lasombra, The Ministry, Ravnos, Salubri, and Tzimisce.

* **Structured Attribute and Skill Allocation**
  Standard V5 creation spreads (Attributes 4/3/3, Skills 11/7/4) with visual dot interfaces and group priority selection.
  Includes a “Free Allocation” mode for homebrew or variant chronicle rules.

* **Discipline and Power Selection**
  In-clan Disciplines are automatically highlighted; add powers for each dot you assign. Out-of-clan options are also supported.

* **Dice Roller with Hunger Integration**
  Includes proper V5 dice logic—success counting, critical pairs, messy criticals, bestial failures, and difficulty comparison.

* **Local Save and JSON Export**
  Autosaves in browser storage. You can export or import characters as `.json` files for easy sharing or backup.

* **Fillable PDF Export**
  Generates a one-page fillable PDF containing all key character data and dot representations for attributes, skills, and disciplines.

---

## Using the Builder

1. **Identity** – Choose your Clan, Generation, and Predator Type. Add name, concept, chronicle, and sire.
2. **Attributes** – Select one group as Primary, one as Secondary, one as Tertiary, and assign dots according to the point budget.
   If your chronicle uses alternate spreads, enable Free Allocation.
3. **Skills** – Repeat the same structure for Skill groups. Add specialties to individual skills.
4. **Disciplines** – Assign up to three Discipline dots by default, adding powers to match your chosen ratings.
5. **Advantages and Touchstones** – Record Merits, Backgrounds, Convictions, and Touchstones in the provided text areas.
6. **Dice Roller** – Select an Attribute and Skill combination, set modifiers, Hunger, and Difficulty, then roll to view results.
7. **Save or Export** – Progress is saved automatically. Export JSON files for storage or sharing, or generate a fillable PDF for printing or digital play.

---

## Dice System Reference

* **Successes**: Rolls of 6–9 count as 1 success.
* **Criticals**: Every pair of 10s adds +2 successes.
* **Messy Criticals**: Any critical made using Hunger dice.
* **Bestial Failures**: No total successes with one or more Hunger 1s.
* **Difficulty**: Compare total successes to the set difficulty for pass/fail outcomes.

---

## Customization

* **Budgets** – You can edit the default attribute, skill, or discipline point pools directly in the JavaScript constants.
* **Clan and Predator Lists** – Add, remove, or rename entries in the data arrays for homebrew chronicles.
* **PDF Layout** – The fillable sheet can be expanded to a multi-page layout or customized with backgrounds and boxes if desired.

---

## Rule References

This project was built to align with standard V5 creation rules.
Please refer to the official **Core Rulebook**, **Player’s Guide**, and **Companion** for complete mechanics, clan details, and power descriptions.

---

## License and Attribution

* **Code License:** Open for modification and reuse under an MIT-style license.
* **Intellectual Property Notice:**
  *Vampire: The Masquerade*, *World of Darkness*, and related terms are trademarks and copyrights of their respective owners.
  This project is a **fan-made tool** and does not reproduce or distribute any proprietary game text.

---

## Contributing

Pull requests and issue reports are welcome. Potential areas for improvement include:

* Expanded **Discipline power lists** per dot and clan.
* Enhanced **multi-page PDF exports** with preformatted layouts.
* Optional **automatic predator benefits** and background templates.
* Localization support for non-English languages.

---

## Credits

Created as a browser-based utility for storytellers and players who want to quickly design and store Kindred characters for Vampire: The Masquerade 5th Edition.
All data is stored locally in your browser until exported.

---
