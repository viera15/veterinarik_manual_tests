## Číslo testu: TC006

## Názov:
Registrácia používateľa - nevyplnený formulár

## Cieľ:
Overiť, že používateľ sa nemôže registrovať do aplikácie, keď je nevyplnený formulár.

## Predpoklady:
- Používateľ nemá vytvorený účet
- Nevyplnený formulár

## Testovacie kroky:

| Číslo kroku | Názov kroku | Dáta | Očakávaný výsledok |
|-------------|---------------------------------------|--------------------------------------------------|--------------------------------------------------------------------|
| 1 | Prejdi na stránku Prihlasovanie | https://veterinarik.test.aleron.sk/ | Zobrazí sa stránka veterinarik.test.aleron.sk |
| 2 | Klikni na položku "Registrovať sa" | | Otvorí sa stránka https://veterinarik.test.aleron.sk/# |
| 3 | Do položky "Skutočné meno" nevyplň meno | | Meno je prázdne |
| 4 | Do položky "Email" nevyplň email | | Email je prázdny |
| 5 | Do položky "Heslo" nevyplň heslo | | Heslo je prázdne |
| 6 | Do položky "Potvrď heslo" nevyplň heslo | | Heslo je prázdne |
| 7 | Zaškrtni položku "Zobraz heslo" | | Položka "Heslo" a "Potvrď heslo" nezobrazuje heslo |
| 8 | Klikni na tlačidlo "Registrovať sa" | | Používateľ nie je zaregistrovaný, zobrazí sa správa "Napíšte normálne meno/názov (min 5 znakov)" |


## Očakávaný výsledok:
Používateľ nie je registrovaný a zobrazí sa správa.

## Závislé testy:


## Priorita:
vysoká

## Poznámky:
- Tento scenár testuje negatívny prípad.
- Pozitívny prípad je v scenári TC001
- Negatívne prípady budú v scenároch TC002, TC003, TC004.

