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
2. Open **CHIRP**
3. Ga naar `File` -> `Open`.
4. Selecteer het `.csv` bestand.

## ⚠️ Belangrijke Waarschuwingen

### 1. Juridisch (Zenden)
* **PMR446 & LPD (1-85):** Dit zijn de enige kanalen waarop je **vergunningsvrij** mag zenden. Let op: officieel moet je hiervoor goedgekeurde (niet-programmeerbare) portofoons gebruiken met een vastgezette antenne.
* **OV & Schiphol Bedrijven (101-117 & 373-400):** Alleen luisteren. Zenden verstoort bedrijfskritische processen en is strafbaar.
* **Luchtvaart & Schiphol Air (118-134 & 301-372):** Zenden is **streng verboden**. Dit zijn AM-frequenties. Het verstoren van luchtvaartcommunicatie is een ernstig misdrijf.
* **Amateur Repeaters (201-269):** Alleen zenden indien je in het bezit bent van een geldige zendamateur-licentie (N of F registratie).
* **Marifoon (401-459):** Alleen zenden met een Marifooncertificaat (Basiscertificaat, Marcom-B/A) en een geregistreerd schip. Zenden vanaf het land is niet toegestaan.
* **Reddingsbrigade (460-470):** Alleen voor geautoriseerde hulpverleners tijdens inzet.
* **Nooddiensten & SAR (501-515):** Dit zijn de meest kritieke kanalen. Zenden is **alleen toegestaan in levensbedreigende situaties** wanneer alle andere communicatiemiddelen falen. Onterecht gebruik van deze kanalen wordt zeer zwaar beboet.

### 2. Technisch (AM vs FM)
Een groot deel van deze lijst (Luchtvaart / Schiphol / 118-136 MHz) gebruikt **AM-modulatie**.
* Standaard Baofengs (UV-5R) ontvangen alleen **FM**. Je kunt de frequenties wel horen, maar het geluid zal vervormd zijn.

## 🛠 Compatibiliteit
Deze lijst is nog niet getest

## 🤝 Bijdragen
Fouten gevonden of is er een repeater frequentie gewijzigd? Maak gerust een Issue aan of stuur een Pull Request!

---
*Disclaimer: Gebruik van deze frequentielijst is op eigen risico. De auteur is niet verantwoordelijk voor onjuist gebruik van zendapparatuur.*
