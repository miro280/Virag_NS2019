# neuronove_siete_projekt
Zvolený dataset má 4GB https://www.kaggle.com/skihikingkevin/pubg-match-deaths/version/3 obsahuje 4 csv súbory so štatistikami hráčov (koľko zabili, koľko prešli, ako dlho prežili....) 
a 4csv súbory s údajmi o zabitiach (aká zbraň bola použitá, pozícia a mená hráčov....)
Z datasetu bude NS predpokladať či hráč skončil v top 3 na základe údajov o tom koľko prešiel, koľko prejazdil, koľko hráčov zabil a celkovej hodnoty poškodenia iných hráčov. 
Dataset som upravil v Jave, ponechal som len údaje o zápasoch, v ktorých bolo 99 a 100 hráčov aby boli údaje relevantnejšie, následne som v exceli pridal stĺpec či hráč skončil v top 3 alebo nie na základe jeho umiestnenia a upravil pomer údajov. Každá hra v tomto datasete je solo - hráč hrá sám.
Projekt obsahuje grafické zobrazenie kde sú porovnané presnosť a chyba trénovacích a testovacích dát.
Neurónová sieť je schopná predpokladať či sa hráč umiestnil v top 3 na základe jeho výsledkov s 87,5% úspešnosťou, predikcie boli porovnané a zobrazené v exceli (súbor je pridaný) kde je možné vyfiltrovať a zobraziť chybné predikcie. 
