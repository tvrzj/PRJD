# IMDB analysis

Tato repozitoř obsahuje kód k anaýze dat filmové databáze [IMDB](www.imdb.com). To konkrétně na periodicky zvěřejňovaném [datasetu](https://developer.imdb.com/non-commercial-datasets/) určenému k nekomerčnímu užití. Konkrétně `title.basics.tsv.gz`, který obsahuje základní údaje.

Soubor obsahující kód je pojmenovaný `code.ipynb`. V něm je použito knihoven Pandas, matplotlib, requests a pymannkendall.

Hlavní částí je definovaná funkce `mov_period_analysis()`. Tato funkce umožňuje analyzovat vývoj délky filmů v čase na základě zvoleného časového období. Je mo6n0 volitelně zadat počáteční a koncový rok analýzy. Funkce provede:

- filtrování dat podle zadaného období,
- vizualizaci délky filmů pomocí boxplotu pro jednotlivé roky
- výpočet a zobrazení trendu průměrné délky filmů v čase
- statistický test trendu pomocí Mann-Kendallova testu
- výpis průměrné délky filmů v daném období a informace o zjištěném trendu

## Zadání:
Nejpozději 2 týdny před konáním zkoušky student odevzdá podklady ve formě odkazu na vlastní veřejný gitový repozitář (GitHub nebo GitLab). Repozitář musí obsahovat funkční kód k ucelenému projektu, zaměřenému na aplikaci programování v oblasti studijního programu.

Projekt musí povinně obsahovat:

	1.	alespoň jednu vlastnoručně definovanou funkci (proceduru/metodu),
	2.	kód pro načtení dat z externího souboru (např. CSV, JSON, XML),
	3.	kód pro vizualizaci dat,
	4.	uložení výstupů do vhodných datových formátů (např. PNG, CSV, JSON).

Součástí repozitáře musí být také stručný popis projektu (README) a případné datové soubory nebo návod na jejich získání.