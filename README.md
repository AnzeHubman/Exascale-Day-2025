
# Exascale Day 2025: Simulacija POPC membrane

V tem direktoriju najdete vse potrebno za samostojno MD simulacijo modelne lipidne membrane. 

## 1. Operacijski sistem in Miniconda
Potrebovali boste operacijski sistem [Ubuntu Linux](https://ubuntu.com/) in okolje [Miniconda](https://docs.anaconda.com/miniconda/). Najvarneje je, če za Ubuntu Linux uporabite virtualni operacijski sistem znotraj vašega osnovnega operacijskega sistema. Priporočam uporabo [VirtualBox](https://www.virtualbox.org/), na spletu pa najdete vrsto nasvetov kako vzpostaviti virtualni OS. Za namestitev Miniconde sledite navodilom na priloženi povezavi. Miniconda je uspešno nameščena, če se ob odprtju novega terminala pred imenom naprave pojavi `(base)`.

## 2. Namestitev
Po uspešni namestitvi Miniconde prenesite ta GitHub repozitorij (pritisnite zeleni gumb z napisom Code in nato Download ZIP). Najdete ga med Prejemi (Downloads) v obliki .zip datoteke. Odprite nov terminal (`Ctrl + Alt + T`) in izvršite sledeče ukaze:

`cd Prejemi/`

`unzip Exascale-Day-2024-main`

`cd Exascale-Day-2024/` .

Med drugim je v direktoriju prisotna datoteka environment.yml. V terminal vpišite:

`conda env create --name membrana --file environment.yml`

in ko vas sistem pozove še `y + Enter`.

Aktivirajte okolje tako, da v terminal vpišete:

`conda activate membrana`

Opazite, da na mestu (base) sedaj stoji (membrana).

## 3. Izvedba simulacije
Poteku dela boste sledili z uporabo [Jupyter Notebook-a](https://jupyter.org/). V terminal z okoljem (membrana) vpišite: 

`jupyter-notebook simulacija-membrane.ipynb`. 

V brskalniku se vam kot zavihek odpre naš Notebook, kjer najdete nadaljnja navodila. Z delom z Jupyter Notebook se lahko seznanite npr. [tukaj](https://www.dataquest.io/blog/jupyter-notebook-tutorial/). V primeru težav lahko Notebook resetirate s klikom na Kernel > Restart Kernel And Clear Output All Cells.

V primeru težav, ali če vas zanima več: anze.hubman@ki.si.
