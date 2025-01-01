# Calculator
Kalkulačka-projekt na kurzu JS


Tato kalkulačka je jednoduchá webová aplikace napsaná v HTML, CSS a JavaScriptu, umožňující provádět základní matematické operace. Aplikace navíc ukládá výrazy a poslední výsledek do localStorage, což umožňuje obnovit data při opětovném otevření stránky.

Funkcionality

Matematické operace:

Sčítání (+)

Odčítání (-)

Násobení (*)

Dělení (/)

Uložení výrazu a výsledku:

Kalkulačka automaticky ukládá aktuální stav výrazu a poslední výsledek do localStorage.

Při obnovení stránky se výběr dat obnoví.

Mazání:

Tlačítko "clear" resetuje výsledek i výběr výrazu.

Použíté technologie a koncepty

1. HTML

Vytvoření struktury tlačítek pro čísla a operace pomocí button elementů.

Vstupní pole (<input>) pro zobrazení aktuálního výrazu nebo výsledku.

2. CSS

Definování tříd pro styling tlačítek a rozložení kalkulačky.

3. JavaScript

Funkce pro kalkulace:

calculation(input) - Přidává číslo nebo operaci do aktuálního výrazu a ukládá jej do localStorage.

calResult() - Vypočítá výsledek pomocí funkce eval(), uloží ho do localStorage a zobrazuje ho na obrazovce.

reset() - Vymaže aktuální výraz i výsledek.

localStorage:

Data jsou ukládána jako JSON stringy do localStorage.

Při načtení stránky jsou hodnoty obnoveny pomocí JSON.parse().

4. Interakce s HTML elementy

Používání atributu onclick pro volání JavaScriptových funkcí přímo z tlačítek.

Dynamické aktualizace hodnoty vstupního pole (input) pomocí document.getElementById().value.


Možné vylepšení

Pokročilé funkce: Implementovat další matematické operace, jako je mocnina nebo odmocnina.
