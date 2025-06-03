## Číslo testu: TC007

## Názov:
Registrácia - vyplnené iba meno

## Cieľ:
Overiť, že používateľ sa nemôže registrovať do aplikácie, keď je vyplnené iba meno.

## Predpoklady:
- Používateľ nemá vytvorený účet


## Testovacie kroky:

| Číslo kroku | Názov kroku | Dáta | Očakávaný výsledok |
|---|---|---|---|
| 1 | Prejdi na stránku Prihlasovanie | https://veterinarik.test.aleron.sk/ | Zobrazí sa stránka veterinarik.test.aleron.sk |
| 2 | Klikni na položku "Registrovať sa" | | Otvorí sa stránka https://veterinarik.test.aleron.sk/# |
| 3 | Do položky "Skutočné meno" vpíš meno | | Meno má správny počet znakov XX a je to len reťazec |
| 4 | Klikni na tlačidlo "Registrovať sa" | | Položka Email má červené orámovanie a správa "Zadajte platný email.". Používateľ nie je zaregistrovaný. |


## Očakávaný výsledok:
Používateľ nie je zaregistrovaný a zobrazí sa správa.

## Závislé testy:


## Priorita:
vysoká

## Poznámky:
- Tento scenár testuje negatívny prípad.
- Pozitívny prípad je v scenári TC001
- Negatívne prípady budú v scenároch TC002, TC003, TC004, TC005, TC006
