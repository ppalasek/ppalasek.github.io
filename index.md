# COVID 19 u Hrvatskoj: Pregled broja zaraženih po županijama

### (generirano 02.02.2022. 14:38:52 h)

#### NAPOMENA (04.11.2021.): Stranica se generira automatski. Ako ima grešaka u strojno čitljivim podacima objavljenim na koronavirus.hr, prikazani grafovi neće biti točni. U tom slučaju pokušat ću ih ispraviti čim nađem vremena.

#### NAPOMENA (15.01.2022.): Od danas se koriste podaci iz popisa stanovništva 2021. u svim prikazima u kojima je to moguće. U prikazima po dobnim skupinama i dalje se koriste podaci iz 2019. jer detaljniji podaci još nisu dostupni. Promijenjene su skale na nekim grafovima kako bi bili informativniji.

#### NAPOMENA (24.01.2022.): Promijenjene su skale na nekim grafovima kako bi bili informativniji.

Interaktivni prikazi dostupni su na sljedećim linkovima:

- [Standardni prikaz](html/index.html) (zadnjih 100 dana)
- [Prikaz na logaritamskoj skali](html/index_log.html) (zadnjih 100 dana)
- [Prikaz na karti](html/index_map.html) (tjedna promjena, zadnjih 7 i 14 dana na 100000 stanovnika)
- [Prikaz po dobnim skupinama](html/index_per_age.html) (zadnjih 180 dostupnih dana)
- [Prikaz po dobnim skupinama i spolu](html/index_pyramid.html) (zadnjih 7 dostupnih dana, na 100000 stanovnika)
- [Prikaz procijepljenosti na karti](html/index_vaccination.html) (zadnji dostupni podaci, ne osvježava se automatski)

-----

## Pregled broja zaraženih po županijama

![](img/2022_02_01_line_plots.png)

## Pregled tjedne promjene broja zaraženih po županijama

![](img/2022_02_01_map.png)

## Kretanje broja COVID-19 slučajeva, hospitalizacija i umrlih

(napomena: podaci o hospitalizacijama i broju osoba na respiratorima se ne objavljuju svakodnevno, prikazani su zadnji dostupni podaci)

![](img/2022_02_01_cases_hospitalisations_deaths.png)

![](img/2022_02_01_cases_hospitalisations_deaths_log.png)

![](img/2022_02_01_cases_hospitalisations_deaths_log_age.png)

## Kretanje udjela pozitivnih testova

(zadnji dostupni podaci s HZJZ, plavom bojom prikazani su podaci s koronavirus_hr twittera)

![](img/2022_02_01_percentage_positive_tests.png)

## Kretanje broja COVID-19 slučajeva na 100 tisuća stanovnika po dobnim skupinama

![](img/2022_02_01_cases_per_age_group_lines.png)

![](img/2022_02_01_cases_per_age_group_lines_log.png)

## Animirani prikaz kretanja broja COVID-19 slučajeva na 100 tisuća stanovnika po dobnim skupinama

![](img/2022_02_01anim_aug_1200.gif)

![](img/anim_cases_2022_02_01_vs_2020.gif)

![](img/2022_02_01all_counties_dots.png)

## Ukupan broj zaraženih u zadnjih 7 dana na 100000 stanovnika

![](img/2022_02_01_map_7_day_per_100k.png)

## Ukupan broj zaraženih u zadnjih 14 dana na 100000 stanovnika

![](img/2022_02_01_map_14_day_per_100k.png)

## Ukupan broj zaraženih u zadnjih 14 dana na 100000 stanovnika po regijama

(napomena: kod ECDC-a boja regije ovisi i o postotku pozitivnih testova, ovdje je prikazan samo broj slučajeva)

![](img/2022_02_01_map_14_day_per_100k_region.png)

(Trend kretanja 14-dnevnog broja slučajeva na 100k stanovnika opisan eksponencijalnom krivuljom n(t) = a * e^(b * t) po regijama. Krivulja aproksimira podatke zadnjih 7 dana, izračunate iz podataka objavljenih na koronavirus.hr, koristeći broj stanovnika po županijama iz 2019. s dzs.hr. Krivulja se prikazuje ukoliko je R^2 aproksimacije > 0.95, prikazana je narančastom bojom. Zelena krivulja prikazuje vrijednosti aproksimacijske krivulje 7 dana u budućnosti (deblja linija), dok su tanjom zelenom linijom prikazane vrijednosti krivulje do dana u kojem bi vrijednost mogla doći do praga od 75/200 zaraženih na 100k stanovnika. Generirano automatski, nakon objave službenih podataka na koronavirus.hr.)

![](img/2022_02_01_current_Jadranska_Hrvatska.png)

![](img/2022_02_01_current_Panonska_Hrvatska.png)

![](img/2022_02_01_current_Grad_Zagreb.png)

![](img/2022_02_01_current_Sjeverna_Hrvatska.png)

![](img/2022_02_01_current_Republika_Hrvatska.png)

![](img/2022_02_01_cases_hospitalisations_deaths_Republika_Hrvatska.png)

## Procijepljenost po županijama

(ne osvježava se automatski)

![](img/2022_02_01_vaccination.png)

## Pregled broja zaraženih po dobnim skupinama na 100000 stanovnika

(Podaci kasne par dana, prikazano stanje nije finalno.)

![](img/2022_02_01_per_age_group.png)

![](img/2022_02_01_per_age_group_all_0.png)

![](img/2022_02_01_per_age_group_all_1.png)

## Pregled broja zaraženih po dobnim skupinama i spolu (u zadnjih 7 dostupnih dana) na 100000 stanovnika

(Podaci kasne par dana, prikazano stanje nije finalno.)

![](img/2022_02_01_pyramid.png)

-----

- [Kod](https://github.com/ppalasek/covid_plots_croatia)

