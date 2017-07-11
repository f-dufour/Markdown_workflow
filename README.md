# Purpose

**Markup** aims to be the all-in-one solution for interpreting long markdown files. It is suitable for academic use and lecture note taking. 

Markup offers multiple features:

*   Automatically correct accuted characters berfore compilation (Les français apprécieront !)
*   Beautify the code, you'll never get in troubles with pandoc rendering.
*   Archive the current version of the markdown with its predecessors in a zip file.
*   Gather all the related media within the projet folder.
*   Web frienfly interpretation with HTML indexing of the different part of your work
*   Support custom CSS formatting

# Process

Choose your file and it will automatically create an HTML index hyperlinking all the H1 level titles (#) in separated files formatted with the CSS style of your choice. The different versions of your work are never lost as a log file and an archive are updated at each parse securing the integrity of your work. All the external media are consolidated within the `Ressource` folder, they will nerver get corrupted.

Markup works as it follows

1. Open the markdown file (and its automatically created log file)
2. Save this version and archive it with the previsous in zip archive
3. Correct accuted characters in the markdown code (optionnal)
4. Beautify the code and make it "pandoc friendly" (optionnal)
5. Gather all the ressources into a "ressource" folder like the images incorporated into the code
6. Split the code at the H1 (#) levels
7. Create an idex relating to all these H1 HTML pages (Table of Contens)
8. Interprete H1 pieces into separated HTML pages with selected CSS style
9. Update the log file with the date of compilation and he work done


# Screenshots

