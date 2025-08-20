# 06 Zadanie projektu

:mag: Vašou úlohou je zostrojiť a naprogramovať štyri samostatné robotické časti, ktoré budú na seba nadväzovať a postupne vykonajú manipulačné úkony na základe popisu nižšie.  

:mag: Každá skupina bude mať na starosti vyriešiť kompletne úlohu pre jeden modul.  

:mag: Dôležité bude dostatočne sa synchronizovať a určiť si jasné rozhranie medzi jednotlivými modulmi - predávanie si objektov vo vami zadefinovanom poradí, stave, a podobne.  

---

<details>
<summary><h1>Manipulované objekty</h1></summary>


Manipulovanými predmetmi budú nasledovné súčiastky:

![OBR](https://github.com/PavolSte/Robotika4/blob/24d6ecba4b28521af8cdc5ca7f0a78b00e6cdc7d/S%C3%BAbory/Objekty%20popis.png)  

</details>  

---

<details>
<summary><h1>Manipulačný robot a jeho moduly</h1></summary>

V tomto projekte je úlohou zostrojiť manipulačného robota pozostávajúceho zo štyroch na seba nadväzujúcich modulov. 

Označenie modulov bude Modul 1, Modul 2, Modul 3 a Modul 4.

Každý modul má jasne zadefinované úlohy a rozhranie s predchádzajúcim, resp. nasledujúcim modulom.

![OBR](https://github.com/PavolSte/Robotika4/blob/ca3e4b46263caa9f762950f71f97d3eefd3a1557/S%C3%BAbory/Moduly%20a%20rozhranie.png)  

</details>  

---

<details>
<summary><h1>Počiatočný stav</h1></summary>

Na začiatku pres spustením celého procesu budú jednotlivé časti va nasledovnom stave:

* Kontajnery sú uložené na sebe v počte 4 - 8 kusov
* Počiatočné miesto uloženia je zadefinované skupinou zodpovednou za Modul 1
* Kontajnery môžu byť v dvoch stavoch:
  * prázdne s farebnou značkou vo vnútri
  * s vloženým blokom
* Farebná značka bude mať vždy jednu z farieb dostupných LEGO blokov
* LEGO bloky, ktoré sa budú vkladať do kontajnerov budú uložené v zásobníku ľubovoľne podľa potreby skupiny zodpovednej za Modul 3

</details>  

---

<details>
<summary><h1>Konečný stav</h1></summary>


Na konci po ukončení manipulačného procesu budú jednotlivé časti v nasledovnom stave:

* Kontajnery s vloženými LEGO blokmi budú uložené na sebe podľa farby, čiže kontajnery s červenými LEGO blokmi budú na sebe, s modrými taktieš ale na inom mieste, a podobne

</details> 

---

<details>
<summary><h1>Manipulačný proces</h1></summary>

Nasledujúca tabuľka opisuje postup manipulačného procesu. 

| Modul 1 | | Modul 2 | | Modul 3 | | Modul 4 |
|---------|---------|---------|---------|---------|---------|---------|
| ![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%201.png)| :arrow_right: |![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%202.png)| :arrow_right:|![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%203.png)| :arrow_right: |![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%204.png)|
|**Prekladanie kontajnerov zo zásobníka na definované miesto.**|| **Prevzatie všetkých kontajnerov a vyradenie plných.** ||**Vloženie LEGO blokov príslušnej farby do kontajnerov**.||**Umiestnenie plných kontajnerov na seba podľa farby vloženého LEGO bloku.**|

</details>  

---

<details>
<summary><h1>Hranice zodpovednosti</h1></summary>

Nasledujúci obrázok definuje hranice zodpovedností každej pracovnej skupiny za konkrétne úlohy v rámci modulu a taktiež zodpovednosť za rozhranie medzi jednotlivými modulmi.

![OBR](https://github.com/PavolSte/Robotika4/blob/63939abf4e43cf46bd3833eb674c175c22780bb0/S%C3%BAbory/Moduly%20rozhranie%20a%20skupiny.png)

</details>  

---

<details>
<summary><h1>Modul 1</h1></summary>

---

| Modul 1 | Rozhranie | Modul 2 |
|---------|---------|---------|
| ![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%201.png)| :arrow_right: |![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%202.png)|
|:green_square: Preloženie kontajnerov umiestnených na sebe na zadefinované miesto pre Modul 2. <br> :green_square: Počet kontajnerov uložených na sebe môže byť v rozmedzí 4-8 kusov <br> :green_square: Kontajnery nesmú počas manipulácie stratiť vložený obsah - blok alebo farebnú značku. |:green_square: Zadefinovať miesto ukladania kontajnerov.|:green_square: Prevziať kontajnery z miesta, kde ich umiestnil Modul 1. |

</details>  


presné rozmery kontanejra , bloku a Lego bloku



