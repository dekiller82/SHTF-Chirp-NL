# 🇳🇱 NL SHTF & Scanner Frequentielijst (CHIRP)

Een uitgebreide frequentielijst voor Nederland, geoptimaliseerd voor import in [CHIRP](https://chirp.danplanet.com/). Deze lijst is samengesteld voor communicatie in noodsituaties (SHTF), radioamateurs en luisteramateurs (scanners).

De lijst bevat o.a. PMR, LPD, Marifoon, Luchtvaart (Schiphol), Repeaters en Nooddiensten, netjes gegroepeerd op kanaalnummer.

## 📋 Inhoudsopgave (Kanaalindeling)

De kanalen zijn logisch ingedeeld in blokken om navigatie op de portofoon makkelijker te maken:

| Kanaal (Loc) | Groep | Beschrijving | Modulatie |
| :--- | :--- | :--- | :--- |
| **1 - 16** | **PMR446** | Vergunningsvrije portofoonkanalen (Analoog) | NFM |
| **17 - 85** | **LPD** | Low Power Device (Vergunningsvrij) | FM |
| **101 - 117** | **OV** | Combofoon (Arriva, Connexxion, busdiensten) | NFM |
| **118 - 134** | **Luchtvaart** | Sportvliegerij, Ballonvaart, Zweefvliegen | **AM** |
| **201 - 269** | **Repeaters** | Radioamateur Repeaters (2m & 70cm) | FM |
| **301 - 400** | **Schiphol** | Toren, Radar, Grondpersoneel, Beveiliging | **AM** / NFM |
| **401 - 459** | **Marifoon** | Scheepvaart, Bruggen, Sluizen, Havendienst | NFM |
| **460 - 470** | **Reddingsbrigade** | KNBRD landelijke kanalen | NFM |
| **501 - 515** | **Nood / SAR** | Rode Kruis, KNRM, SAR, Noodkanalen | NFM / AM |
| **601 - 604** | **Ruimtevaart** | ISS (International Space Station), Satellieten | NFM/WFM |

## 🚀 Hoe te gebruiken

1. Download het bestand `shtf_chrip_nl.csv` uit deze repository.
2. Open **CHIRP** en verbind je portofoon.
3. Ga naar `File` -> `Import`.
4. Selecteer het `.csv` bestand.

## ⚠️ Belangrijke Waarschuwingen

### 1. Juridisch (Zenden)
* **PMR446 & LPD (1-85):** Dit zijn de enige frequenties waarop je **vergunningsvrij** mag zenden (mits met goedgekeurde apparatuur en max. vermogen).
* **Marifoon & Luchtvaart:** Zenden is **strenge verboden** zonder de juiste certificaten. Inbreuk hierop kan leiden tot hoge boetes en gevaarlijke situaties.
* **Amateur (200-reeks):** Alleen zenden met een geldige zendamateur-licentie. Luisteren is legaal.

### 2. Technisch (AM vs FM)
Een groot deel van deze lijst (Luchtvaart / Schiphol / 118-136 MHz) gebruikt **AM-modulatie**.
* Standaard Baofengs (UV-5R) ontvangen alleen **FM**. Je kunt de frequenties wel horen, maar het geluid zal vervormd zijn.

## 🛠 Compatibiliteit
Deze lijst is nog niet getest

## 🤝 Bijdragen
Fouten gevonden of is er een repeater frequentie gewijzigd? Maak gerust een Issue aan of stuur een Pull Request!

---
*Disclaimer: Gebruik van deze frequentielijst is op eigen risico. De auteur is niet verantwoordelijk voor onjuist gebruik van zendapparatuur.*
