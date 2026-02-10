# 📌 1. Toiminnan ja kriittisten resurssien kartoitus

Jäätelövaunun toiminta perustuu seuraaviin digitaalisiin ja fyysisiin resursseihin:

### **Tekniset resurssit**

*   **Maksupääte**
    *   Korttimaksut
    *   Mahdollinen mobiilimaksu
*   **Käteiskassa**
*   **Sähköverkkoon kytketty pakastin**
*   **Mahdollinen mobiilinetti– tai WiFi‑yhteys maksupäätteelle**
*   **Mahdollinen kassajärjestelmä/tabletti**

### **Tietovirrat**

*   Korttimaksujen maksutapahtumadata (maksupalveluntarjoajan kautta)
*   Sähköiseen kassaan tallentuvat myyntitiedot
*   Mahdolliset kuitit (paperi tai sähköinen)

### **Henkilöt**

*   Sinä itse tai työntekijät, jotka
    *   käyttävät maksupäätettä
    *   käsittelevät käteistä
    *   valvovat vaunua ja pakastinta

***

# 📌 2. Uhka- ja haavoittuvuusanalyysi

Alla on vaunuun soveltuva lista:

### **Kyberturvallisuusuhat**

| Uhka                                              | Kuvaus                                                                              |
| ------------------------------------------------- | ----------------------------------------------------------------------------------- |
| **Maksupäätteen väärinkäyttö**                    | Esim. maksupääteen varastaminen, luvaton käyttö tai huijaus maksun peruutuksilla.   |
| **Tietoliikenteen häiriö**                        | Mobiilidata ei toimi → korttimaksut eivät onnistu.                                  |
| **Maksupäätteen tai kassalaitteen haittaohjelma** | Harvinainen mutta mahdollinen, erityisesti jos laitteeseen saa asentaa sovelluksia. |
| **Tietojen vuotaminen**                           | Myynti- tai maksudata voi paljastua, jos laitetta ei suojata.                       |
| **Kortin väärinkäyttö / chargeback-huijaukset**   | Asiakas väittää, ettei ole tehnyt maksua.                                           |

### **Fysikaaliset ja ympäristöriskit (NIS2 painottaa myös näitä)**

| Uhka                         | Kuvaus                                       |
| ---------------------------- | -------------------------------------------- |
| **Sähkökatko**               | Pakastin sulaa → tuotteet pilaantuvat.       |
| **Laitteiden rikkoutuminen** | Maksupääte tai pakastin hajoaa.              |
| **Varkaus tai ilkivalta**    | Maksupäätteen tai käteiskassan varastaminen. |
| **Sääolosuhteet**            | Laitteet kastuvat tai ylikuumenevat.         |

### **Toiminnalliset ja henkilöstöön liittyvät riskit**

*   Työntekijä ei osaa käyttää maksupäätettä → virheitä tapahtuu
*   Puutteellinen käteiskassan käsittely
*   Avainten / vaunun lukituksen hallintapuutteet

***

# 📌 3. Riskien arviointi ja luokittelu

Käytetään yksinkertaista NIS2‑henkistä riskimatriisia:

*   **Todennäköisyys**: Matala / Keskitaso / Korkea
*   **Vaikutus**: Vähäinen / Merkittävä / Vakava

Esimerkkiarvioita:

| Riski                         | Todennäköisyys | Vaikutus   | Riskitaso   |
| ----------------------------- | -------------- | ---------- | ----------- |
| Sähkökatko                    | Keskitaso      | Vakava     | Korkea      |
| Maksupäätteen varkaus         | Keskitaso      | Merkittävä | Keskikorkea |
| Mobiilidatan katkeaminen      | Korkea         | Merkittävä | Korkea      |
| Haittaohjelma kassalaitteessa | Matala         | Merkittävä | Kohtalainen |
| Käteiskassan ryöstö           | Matala         | Vakava     | Keskikorkea |

***

# 📌 4. Riskienhallintatoimenpiteet (NIS2:n periaatteet sovellettuna)

NIS2 edellyttää **teknisiä ja organisatorisia** suojatoimenpiteitä. Tässä vaunuun sopiva, kevyt mutta kattava lista:

***

## 🔒 **Tekniset kontrollit**

### **1. Maksupäätteen turvallisuus**

*   Käytä **PIN-koodilla lukittua maksupäätettä**
*   Ota käyttöön **maksupalveluntarjoajan suojaukset** (Salaus, PCI-DSS-standardit – nämä hoituvat automaattisesti)
*   Älä anna maksupäätettä ulkopuolisten käsiin

### **2. Laitteiden päivitykset**

*   Pidä maksupääte ja mahdollinen tabletti **päivityksin ajantasalla**
*   Rajoita sovellusasennukset (vain viralliset sovellukset)

### **3. Tietoliikenteen varmistaminen**

*   Hanki **kahden operaattorin SIM-kortti** tai varalaite  
    → korttimaksut toimivat myös ruuhkaisina tapahtumapäivinä

### **4. Fyysinen turvallisuus**

*   Lukittavat säilytyslaatikot maksupäätteelle ja käteiselle
*   Vaunun ovien lukot kunnossa
*   Valvonta (myös yksinkertainen liiketunnistin tai kameratarra toimii pelotteena)

***

## 🔋 **Toiminnan jatkuvuus**

### **1. Sähkökatkon hallinta**

*   Erillinen **lämpötilahälytin** pakastimeen (SMS tai app)
*   Varaudu lyhyisiin katkoihin:  
    → lämpötila pysyy hyvänä, kun pakastin pidetään kiinni
*   Mahdollinen **varavoima (pieni generaattori)** jos olet tapahtumissa, joissa sähkönluotettavuus vaihtelee

### **2. Varasuunnitelma maksamiseen**

*   "Sähkökatko / verkko poikki" -tilanteessa:
    *   Hyväksy käteinen
    *   Jos käteistä ei ole: ota asiakkaan yhteystiedot ja rahastonumerosi laskua varten (avaintieto kirjattuna)

***

## 👥 **Henkilöstökontrollit**

### **1. Selkeät ohjeet työntekijöille**

*   Maksupäätteen käyttö
*   Käteisen käsittely
*   Vaunun lukitseminen ja avainten hallinta
*   Hätätilanteiden toimintamalli (sähkö, varas, sairaskohtaus)

### **2. Tietoturvatietoisuus**

*   Älä koskaan kirjoita maksupäätteen PIN-koodeja näkyville
*   Hyvä salasanojen hallinta (jos käytössä tabletteja)
*   Myyntitietojen luottamuksellinen käsittely

***

## 📄 **Dokumentointi (NIS2:n vaatimus)**

Lyhyt “riskienhallintasuunnitelma” riittää, ja sen voi pitää esimerkiksi Wordissa tai OneNotessa:

Sisältö:

1.  **Kriittiset resurssit**
2.  **Riskikartoitus**
3.  **Hallintatoimenpiteet**
4.  **Vastuuhenkilö** (sinä tai työntekijä)
5.  **Tarkistuspäivämäärä** (esim. 1× vuodessa)

***

# 📌 5. Jatkuva parantaminen

NIS2 korostaa jatkuvaa riskiperustaista toimintaa:

*   Päivitä suunnitelma 1× vuodessa
*   Tarkista laitteet ja suojaukset kauden alussa
*   Kirjaa ylös poikkeamat (esim. sähkökatko, maksupääteongelma)
*   Tee parannuksia havaintojen perusteella

***

# 🎉 Yhteenveto

Vaikka jäätelökioski ei kuulu NIS2:n velvoittamien toimijoiden joukkoon, tämän **kevyen NIS2‑mallin** avulla:

*   Vähennät keskeytyksiä
*   Suojaat maksutapahtumia
*   Turvaat tuotteet ja kylmäketjun
*   Huolehdit datasta ja laitteista
