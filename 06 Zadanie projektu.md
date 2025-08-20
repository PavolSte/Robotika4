# 06 Zadanie projektu

:mag: Vašou úlohou je zostrojiť a naprogramovať štyri samostatné robotické časti, ktoré budú na seba nadväzovať a postupne vykonajú manipulačné úkony na základe popisu nižšie.  

:mag: Každá skupina bude mať na starosti vyriešiť kompletne úlohu pre jeden modul.  

:mag: Dôležité bude dostatočne sa synchronizovať a určiť si jasné rozhranie medzi jednotlivými modulmi - predávanie si objektov vo vami zadefinovanom poradí, stave, a podobne.  

---

## Manipulované objekty

Manipulovanými predmetmi budú nasledovné súčiastky:

![OBR](https://github.com/PavolSte/Robotika4/blob/24d6ecba4b28521af8cdc5ca7f0a78b00e6cdc7d/S%C3%BAbory/Objekty%20popis.png)  

---

## Manipulačný robot a jeho moduly

V tomto projekte je úlohou zostrojiť manipulačného robota pozostávajúceho zo štyroch na seba nadväzujúcich modulov. 

Označenie modulov bude Modul 1, Modul 2, Modul 3 a Modul 4.

Každý modul má jasne zadefinované úlohy a rozhranie s predchádzajúcim, resp. nasledujúcim modulom.

![OBR](https://github.com/PavolSte/Robotika4/blob/ca3e4b46263caa9f762950f71f97d3eefd3a1557/S%C3%BAbory/Moduly%20a%20rozhranie.png)  

---

## Počiatočný stav

Na začiatku pres spustením celého procesu budú jednotlivé časti va nasledovnom stave:

* Kontajnery sú uložené na sebe v počte 4 - 8 kusov
* Počiatočné miesto uloženia je zadefinované skupinou zodpovednou za Modul 1
* Kontajnery môžu byť v dvoch stavoch:
  * prázdne s farebnou značkou vo vnútri
  * s vloženým blokom
* Farebná značka bude mať vždy jednu z farieb dostupných LEGO blokov
* LEGO bloky, ktoré sa budú vkladať do kontajnerov budú uložené v zásobníku ľubovoľne podľa potreby skupiny zodpovednej za Modul 3

---

## Konečný stav

Na konci po ukončení manipulačného procesu budú jednotlivé časti v nasledovnom stave:

* Kontajnery s vloženými LEGO blokmi budú uložené na sebe podľa farby, čiže kontajnery s červenými LEGO blokmi budú na sebe, s modrými taktieš ale na inom mieste, a podobne

---

## Manipulačný proces

Nasledujúca tabuľka opisuje postup manipulačného procesu. 

| Modul 1 | | Modul 2 | | Modul 3 | | Modul 4 |
|---------|---------|---------|---------|---------|---------|---------|
| ![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%201.png)| :arrow_right: |![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%202.png)| :arrow_right:|![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%203.png)| :arrow_right: |![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%204.png)|
|**Prekladanie kontajnerov zo zásobníka na definované miesto.**|| **Prevzatie všetkých kontajnerov a vyradenie plných.** ||**Vloženie LEGO blokov príslušnej farby do kontajnerov**.||**Umiestnenie plných kontajnerov na seba podľa farby vloženého LEGO bloku.**|

---

## Pracovná skupina a jej zodpovednosti

Nasledujúci obrázok definuje hranice zodpovedností každej pracovnej skupiny za konkrétne úlohy v rámci modulu a taktiež zodpovednosť za rozhranie medzi jednotlivými modulmi.

![OBR](https://github.com/PavolSte/Robotika4/blob/63939abf4e43cf46bd3833eb674c175c22780bb0/S%C3%BAbory/Moduly%20rozhranie%20a%20skupiny.png)


Moduly

zodpovednosti za jednotlivé robotické moduly:


Modul 1
Modul 2
Modul 3
Modul 4

---

| Modul 1 | | Modul 2 | | Modul 3 | | Modul 4 |
|---------|---------|---------|---------|---------|---------|---------|
| ![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%201.png)| :arrow_right: |![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%202.png)| :arrow_right:|![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%203.png)| :arrow_right: |![OBR](https://github.com/PavolSte/Robotika4/blob/d5d17f7a90e56e8c825b775b20b6f948949a6b17/S%C3%BAbory/Robot%20-%20modul%204.png)|
|:green_square: Preloženie kontajnerov umiestnených na sebe, uloženie kontajnerov na zadefinované miesto pre Modul 2. <br> :green_square: Výška kontajnerov môže byť v rozmedzí 4-8 <br> :green_square: Niektoré kontajnery budú obsahovať vložený blok, ktorý pri manipulácii nesmie vypadnúť. ||:green_square: Previzať kontajnery z miesta, kde ich umiestnil Modul 1. |||||


presné rozmery kontanejra , bloku a Lego bloku


<details>

<summary>Tips for collapsed sections</summary>

### You can add a header

You can add text within a collapsed section.

You can add an image or a code block, too.

```ruby
   puts "Hello World"
```

</details>
