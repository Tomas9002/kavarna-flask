# kavarna-flask

(R8)
Jednoduchý web kavárny vytvořený ve Flasku. Aplikace představuje kavárnu, její nabídku kávy, čaje a sladkostí, otevírací dobu a kontaktní informace.

Web obsahuje dvě stránky:

- úvodní stránku s popisem kavárny
- kontaktní stránku s telefonním číslem a emailem

## Co aplikace dělá

Aplikace je webová stránka kavárny kde je obrázek kavárny a odkaz na kontakty kde je email a telefonní číslo.

(R9)
## Vytvoření virtuálního prostředí

```shell
python -m venv .venv
```

## Jak ji spustit

První se musí aktivovat virtuální prostředí:

```shell
.venv\Scripts\activate.bat
```
Instalace frameworku Flask:

```shell
pip install Flask
```

Poté spuštění aplikace:

```shell
flask --app index run --debug
```
A nakonec do vyhldenávaní v prohlížeči musíte napsat "127.0.0.1:5000".

(R10)
## Jaká je struktura projektu

kavarna-flask

    __pychache__

    .venv

    templates

        base.html

        contact.html

        index.html

    .gitignore

    index.py

    README.md
    
