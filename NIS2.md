# 🧭 Johdatus hallittuun riskiajatteluun (NIS2-henkisyys)

## Miksi tästä puhutaan?

Tietoturvassa ja kyberturvallisuudessa keskustelu ajautuu usein yhteen hetkeen:

* *“Mitä tapahtui?”*
* *“Kuka teki virheen?”*
* *“Miten tämä olisi voitu estää?”*

NIS2-direktiivi lähestyy asiaa toisin.

Se ei kysy ensisijaisesti **miksi jotain tapahtui**, vaan:

> *Oliko riski tunnistettu, hallittu ja käsitelty oikein silloin, kun se tapahtui?*

---

## Riskit eivät ole poikkeus → Ne ovat lähtökohta

NIS2 ja moderni riskienhallinta lähtevät yhdestä perusolettamuksesta:

> **Kaikki merkityksellinen toiminta sisältää riskejä.**

* Digitaaliset maksut sisältävät riskejä
* Pilvipalvelut sisältävät riskejä
* Verkkoon kytketyt järjestelmät sisältävät riskejä

Täydellinen turvallisuus ei ole realistinen tavoite → **hallittu turvallisuus on**.

---

## Fokus ei ole hetkessä, vaan prosessissa

Tässä ei keskitytä yksittäiseen tapahtumaan tai virheeseen. Sen sijaan keskitytään **jatkuvaan prosessiin**, jossa:

1. Riskit tunnistetaan etukäteen
2. Riskiä pienennetään järkevin keinoin
3. Osa riskistä hyväksytään tietoisesti
4. Vaikutuksia rajataan ennakkoon
5. Varaudutaan siihen, että jokin riski **eskaloituu ennemmin tai myöhemmin**

👉 Tämä ei ole pessimististä ajattelua, vaan **ammatillista realismia**.

---

## Eskalaatio ei tarkoita epäonnistumista

Yksi tärkeimmistä NIS2-ajattelun muutoksista on tämä:

> **Riskin toteutuminen ei automaattisesti tarkoita epäonnistunutta turvallisuutta.**

Epäonnistuminen tapahtuu vasta, jos:

* riskiä ei tunnistettu
* vaikutuksia ei ollut rajattu
* reagointia ei ollut mietitty etukäteen
* vastuita ei ollut määritelty

Jos prosessi toimii, eskalaatio on **hallittu tapahtuma**, ei kriisi.

---

## Mitä tässä kokonaisuudessa opitaan?

Tämän esimerkin kautta opitaan, että:

* riskienhallinta ei ole yksittäinen toimenpide
* turvallisuus ei ole “kaikki tai ei mitään”
* hyvä malli kestää myös silloin, kun jokin menee pieleen

> **Hyvä prosessi ei estä kaikkea → Se estää vahingon kasvamisen.**

---

## Ajattelutapa, joka kannattaa muistaa

Jos tästä materiaalista jää mieleen vain yksi asia, se on tämä:

> *Kyberturvallisuudessa ei mitata sitä, tapahtuiko jotain – vaan sitä, oltiinko siihen valmiita.*

---

## Linkkejä

* https://www.kyberturvallisuuskeskus.fi/fi/toimintamme/saantely-ja-valvonta/nis-2-euroopan-unionin-kyberturvallisuusdirektiivi/tarkeaa-tietoa


* [Artikla 20 – Johdon vastuu](https://eur-lex.europa.eu/eli/dir/2022/2555/oj?locale=fi#art_20)
* [Artikla 21 – Riskienhallintatoimenpiteet (ydinartikla)](https://eur-lex.europa.eu/eli/dir/2022/2555/oj?locale=fi#art_21)
* [Artikla 23 – Poikkeamien raportointi](https://eur-lex.europa.eu/eli/dir/2022/2555/oj?locale=fi#art_23)
* [Artikla 32 ja 33 – Valvonta ja auditointi](https://eur-lex.europa.eu/eli/dir/2022/2555/oj?locale=fi#art_32)
* [Artikla 34 – Seuraamukset ja sanktiot](https://eur-lex.europa.eu/eli/dir/2022/2555/oj?locale=fi#art_34)

---

# 🧭 Case: Luottokorttitietojen varkaus

NIS2-direktiivi perustuu ajatukseen, että **riskit ovat jatkuva prosessi**, eivät yksittäinen tapahtuma. Tämä case kattaa koko elinkaaren.

---

## 🎯 Tapaus lyhyesti (lähtötilanne)

* Luottokortti **on välttämätön** (liiketoiminta / arki / palveluiden käyttö)
* Korttitiedot **varastettiin**
* Kortilla tehtiin **8 × 11,99 € huijausostot** → nostoraja täyteen
* Toimet:

  * yhteys myyjään
  * yhteys pankkiin → kortti suljettu
  * rikosilmoitus
  * reklamaatio korttiyhtiölle
* **Taloudellinen vahinko korvattiin**

👉 Tämä ei ole epäonnistuminen → Tämä on **toimiva riskienhallintamalli käytännössä**.

## 🧩 Riskiperusteinen ajattelu (NIS2 Artikla 21)

### 1️⃣ Omaisuus (Asset)

* Luottokortti
* Korttitiedot
* Maksukyky / taloudellinen turvallisuus

### 2️⃣ Uhka (Threat)

* Korttitietojen vuoto
* Korttitietojen väärinkäyttö verkossa

### 3️⃣ Haavoittuvuus (Vulnerability)

* Korttitietoja käytetään kolmansien osapuolten palveluissa
* Verkkomaksujen globaali luonne
* Ihmisen rajallinen kyky havaita vuoto etukäteen

---

## 🛡️ Riskienhallintatoimet (Controls)

Tässä kohtaa NIS2 alkaa *hymyillä*.

| Kontrolli                   | NIS2-tulkinta                          |
| --------------------------- | -------------------------------------- |
| **Nostoraja**               | Riskin vaikutuksen rajaaminen          |
| **Korttiyhtiön vastuu**     | Riskin siirto (risk transfer)          |
| **Reaaliaikainen seuranta** | Havaitseminen                          |
| **Nopea kortin sulku**      | Incident response                      |
| **Rikosilmoitus**           | Oikeudellinen ja organisatorinen vaste |
| **Reklamaatio**             | Taloudellisen vaikutuksen palautus     |

👉 Riski **realisoitui**, mutta **ei eskaloitunut**.

---

## 🔄 Incident management → NIS2:n mukainen

NIS2 ei odota nollahyökkäyksiä → Se odottaa **hallittuja tapahtumia**:

1. **Detection**
   → huijausostot havaittu

2. **Response**
   → kortti suljettu välittömästi

3. **Containment**
   → nostoraja esti suuremman vahingon

4. **Recovery**
   → rahat palautettiin

5. **Lessons learned**
   → riski tunnistettu ja ymmärretty paremmin


## ⚖️ Vastuunjako (erittäin keskeinen NIS2:ssa)

Tässä näkyy **shared responsibility model**:

| Toimija       | Vastuu                       |
| ------------- | ---------------------------- |
| Kortinhaltija | Ilmoittaa nopeasti           |
| Pankki        | Sulkee kortin                |
| Korttiyhtiö   | Korvaa väärinkäytön          |
| Kauppias      | Reagoi ilmoitukseen          |
| Poliisi       | Rikosoikeudellinen käsittely |

👉 NIS2:n näkökulmasta tämä on **kypsä ekosysteemi**, ei yksittäinen epäonnistuminen.

---

## 🧠 Yhteenveto

> **Luottokorttia tarvitaan, vaikka siihen liittyy riskejä.**
> NIS2 ei kiellä riskin ottamista – se vaatii riskin **tiedostamista, rajaamista ja hallintaa**.

---

# 🧱 Luottokortticase tarkemmin NIS2:n mukaisina vaiheina

## 1️⃣ Välttämättömyyden tunnistaminen (Business need)

**Tilanne**

* Maksukorttia tarvitaan arjen ja palveluiden käyttöön
* Vaihtoehdot (käteinen, lasku, manuaalinen maksaminen) eivät ole realistisia

**NIS2-näkökulma**

* Digitaalinen palvelu on **toiminnan kannalta kriittinen**
* Riskin ottaminen on perusteltua

👉 **NIS2 ei kiellä kortin käyttöä → Se vaatii tietoisen päätöksen**

---

## 2️⃣ Riskien tunnistaminen (Risk identification)

**Tunnistetut riskit**

* Korttitietojen vuoto verkossa
* Fyysisen kortin katoaminen tai anastus
* Lähimaksun väärinkäyttö
* Taloudellinen vahinko väärinkäytöstä

**NIS2-näkökulma**

* Riskit tunnistetaan realistisesti, ei teoreettisesti
* Fokus on todennäköisissä uhkissa

👉 **Tietoinen ymmärrys ennen incidenttiä**

---

## 3️⃣ Ennaltaehkäisevät kontrollit (Preventive measures)

**Vertaa**:
- Preventive measures → Ehkäisevät toimenpiteet
- Corrective measures → Korjaavat toimenpiteet
- Detective measures → Havaitsevat (tai tunnistavat) toimenpiteet

---

### Measure vs. Control

*   **Measure (toimenpide):** Konkreettinen teko riskin pienentämiseksi. → *Esim.* varmuuskopiointi, palomuuri.
*   **Control (kontrolli):** Mekanismi, jolla varmistetaan että toimenpiteet toimivat ja toteutuvat. → *Esim.* lokien seuranta, käyttöoikeuksien valvonta.

👉 **Measure = mitä tehdään**  
👉 **Control = miten varmistetaan**

---

**Tekniset ja käyttäytymiseen liittyvät kontrollit**

* Korttitietoja annettu vain harvoihin ja luotettuihin palveluihin
* PIN-koodi vain muistissa, ei missään tallennettuna
* Korttia ei kuljeteta mukana ilman tarvetta
* Kortti säilytetään fyysisesti suojaisessa paikassa
* Mukana kuljettaessa:

  * käden ulottuvilla
  * RFID/NFC-suojakotelossa

**NIS2-näkökulma**

* Hyökkäyspinnan minimointi
* Defense-in-depth (käyttäytyminen + fyysinen + tekninen)

👉 **Riskiä pienennetään ennen kuin mitään tapahtuu**

---

## 4️⃣ Riskin hyväksyminen ja rajaaminen (Risk acceptance & limitation)

**Hyväksytyt realiteetit**

* Kaikkia riskejä ei voi poistaa
* Korttitietojen väärinkäyttö on mahdollista

**Käytettyjä kontrolleja**

* Nostorajat
* Ilmoitukset puhelimeen
* Korttiyhtiön vastuu ja reklamaatiomallit

**NIS2-näkökulma**

* Riski hyväksytään **hallittuna**
* Vaikutus rajataan etukäteen

👉 **Tämä on kypsää riskienhallintaa**

---

## 5️⃣ Incidentin toteutuminen (Risk materialization)

**Mitä tapahtui**

* Korttitietoja käytettiin väärin
* 8 × 11,99 € huijausostot
* Nostoraja täyttyi → Ilmoitus puhelimeen

**NIS2-näkökulma**

* Incident ≠ epäonnistuminen
* Tämä on odotettu skenaario riskienhallinnassa

👉 **Riski realisoitui, mutta ei eskaloitunut**

---

## 6️⃣ Havaitseminen ja reagointi (Detection & response)

**Toimenpiteet**

* Huijaus havaittiin nopeasti (Kiitos ilmoituksen)
* Yhteys myyjään
* Kortti suljettiin välittömästi
* Yhteys pankkiin
* Rikosilmoitus tehtiin
* Reklamaatio korttiyhtiölle

**NIS2-näkökulma**

* Nopea reagointi
* Selkeä toimintamalli
* Ei viivettä tai epäröintiä

👉 **Incident response toimii kuten pitää**

---

## 7️⃣ Vaikutuksen hallinta ja toipuminen (Impact & recovery)

**Tulokset**

* Taloudellinen vahinko rajautui (Kiitos nostorajan)
* Väärinkäytetyt summat korvattiin (Kiitos korttiin liittyvän vakutuuksen)
* Ei pitkäaikaista taloudellista tai toiminnallista haittaa
* Lyhytaikainen → Joutuu odottamaan uutta korttia ja päivittämään tiedot eri palveluntarjoajille.
* Huom! Maksusovellus oli heti käytössä vaikka fyysistä korttia ei ollut.

**NIS2-näkökulma**

* Recovery onnistui
* Liiketoiminnan jatkuvuus säilyi (Kiitos maksusovelluksen)

👉 **Kontrollit toimivat käytännössä**

---

## 8️⃣ Vastuunjako ja ekosysteemi (Shared responsibility)

**Toimijat**

* Kortinhaltija → nopea ilmoitus
* Pankki → kortin sulku
* Korttiyhtiö → korvaus
* Kauppias → reagointi
* Poliisi → rikosprosessi

**NIS2-näkökulma**

* Kypsä ja toimiva ekosysteemi
* Vastuu ei ole yksin käyttäjällä

👉 **NIS2 korostaa yhteistyötä, ei syyllistämistä**

---

## 9️⃣ Jälkikäteinen arviointi (Lessons learned)

**Johtopäätös**

* Ennaltaehkäisevät kontrollit olivat asianmukaisia
* Reagointi oli oikea-aikaista
* Riskitaso pysyi hyväksyttävänä

**NIS2-näkökulma**

* Case vahvistaa olemassa olevien kontrollien toimivuuden
* Ei tarvetta ylireagoida

👉 **Incident vahvistaa mallin, ei riko sitä**

---

## 🧠 Koko case yhdessä lauseessa

> Tämä tapaus havainnollistaa NIS2-direktiivin riskiperusteista lähestymistapaa käytännössä: riskit tunnistettiin, niitä lievennettiin, osa hyväksyttiin tietoisesti, niitä rajoitettiin, havaittiin, käsiteltiin tehokkaasti ja niistä toivuttiin ilman eskaloitumista.

---

# 🧩 NIS2-case → ISO 27005 -mapping (vaiheittain)

## Ydinajatus

* **NIS2** kertoo *mitä pitää tehdä*
* **ISO 27005** kertoo *miten riskit käsitellään järjestelmällisesti*

Tämä case osuu poikkeuksellisen siististi ISO-malliin.

---

## 1️⃣ Kontekstin määrittely

**ISO 27005: Context establishment**

**Case**

* Maksukortti on välttämätön päivittäiselle toiminnalle
* Digitaaliset maksut ovat osa normaalia toimintaympäristöä

**ISO-tulkinta**

* Riskienhallinnan konteksti määritelty (talous, maksaminen, digipalvelut)
* Riskin ottaminen on perusteltua liiketoiminnan/arkitoiminnan kannalta

➡️ *Riskienhallinta alkaa ymmärtämällä, miksi omaisuus on olemassa.*

---

## 2️⃣ Omaisuuden tunnistaminen

**ISO 27005: Asset identification**

**Case**

* Maksukortti (fyysinen)
* Korttitiedot
* PIN-koodi
* Taloudellinen turvallisuus

**ISO-tulkinta**

* Sekä **ensisijaiset** (raha, maksukyky) että **tukevat** omaisuudet (kortti, tiedot) tunnistettu

---

## 3️⃣ Uhkien tunnistaminen

**ISO 27005: Threat identification**

**Case**

* Korttitietojen väärinkäyttö verkossa
* Fyysinen anastus
* Lähimaksun väärinkäyttö
* Taloudellinen vahinko

**ISO-tulkinta**

* Realistiset ja todennäköiset uhkat
* Ei hypoteettisia “kaikki on mahdollista” -uhkia

---

## 4️⃣ Haavoittuvuuksien tunnistaminen

**ISO 27005: Vulnerability identification**

**Case**

* Korttitietoja käytetään ulkoisissa palveluissa
* Ihmisen rajallinen ennakkohavaintokyky
* Globaali maksujärjestelmä

**ISO-tulkinta**

* Haavoittuvuudet tunnistetaan ilman syyllistämistä
* Fokus järjestelmissä ja toimintamalleissa, ei käyttäjässä

---

## 5️⃣ Riskien arviointi

**ISO 27005: Risk analysis & evaluation**

**Case**

* Todennäköisyys: matala–keskitaso
* Vaikutus ilman kontrollia: korkea
* Vaikutus kontrollien kanssa: rajattu

**ISO-tulkinta**

* Riski arvioitu **kontrollien kanssa**, ei ilman niitä
* Riskitaso todetaan hyväksyttäväksi

➡️ *This is a critical maturity indicator*

---

## 6️⃣ Riskien käsittely (preventiivinen)

**ISO 27005: Risk treatment – mitigation**

**Case**

* Korttitiedot vain luotettuihin palveluihin
* PIN vain muistissa
* Korttia ei kuljeteta turhaan
* RFID-suojakotelo
* Fyysinen hallinta

**ISO-tulkinta**

* Useita lieventäviä kontrollikerroksia
* [Defense-in-depth](https://en.wikipedia.org/wiki/Defense_in_depth_(computing))
* Käyttäytymiseen perustuvat kontrollit hyväksytty osaksi riskienhallintaa

---

## 7️⃣ Riskin hyväksyminen ja siirto

**ISO 27005: Risk acceptance & risk transfer**

**Case**

* Nostorajat
* Korttiyhtiön vastuu ja reklamaatiomalli

**ISO-tulkinta**

* Riski hyväksytään hallitussa muodossa
* Osa riskistä siirretään kolmannelle osapuolelle

➡️ *Tyypillinen ISO‑standardien mukainen riskipäätös*

---

## 8️⃣ Riskin toteutuminen (incident)

**ISO 27005: Risk occurrence**

**Case**

* 8 × 11,99 € huijausostot
* Nostoraja täyttyy

**ISO-tulkinta**

* Ennalta tunnistettu riski realisoituu
* Ei yllättävä tapahtuma riskimallin näkökulmasta

---

## 9️⃣ Incident response ja vaikutuksen hallinta

**ISO 27005 (linkittyy ISO 27035): Incident handling**

**Case**

* Nopea havaitseminen
* Kortin sulku
* Ilmoitukset
* Rikosilmoitus
* Reklamaatio

**ISO-tulkinta**

* Selkeä reagointimalli
* Ajoissa tehty vaste estää eskalaation

---

## 🔟 Toipuminen ja oppiminen

**ISO 27005: Monitoring & review**

**Case**

* Rahat palautettu
* Ei pitkäaikaista vahinkoa
* Kontrollit todettu toimiviksi

**ISO-tulkinta**

* Riskienhallintaa ei tarvitse kiristää paniikissa
* Case vahvistaa nykyisen mallin tehokkuuden

---

## 🧠 Tiivistetty ISO-yhteenveto

> Tapaus osoittaa kypsän ISO/IEC 27005 ‑standardin mukaisen riskienhallintaprosessin, jossa riskit tunnistettiin, arvioitiin, lievennettiin, hyväksyttiin tietoisesti, seurattiin ja käsiteltiin onnistuneesti niiden realisoituessa ilman eskaloitumista.

---

> **ISO 27005 ei mittaa, tapahtuiko incident – vaan oliko organisaatio valmis siihen.** → Tässä casessa vastaus on yksiselitteisesti *kyllä*.

---

# 💳 Mitä opittiin → Luotiin Maksukorttipolitiikka (Payment Card Policy)

## 1. Tarkoitus ja soveltamisala

Tämän politiikan tarkoituksena on varmistaa maksukorttien turvallinen käyttö, säilytys ja hallinta sekä minimoida maksukortteihin liittyvät taloudelliset ja tietoturvariskit. Politiikka koskee kaikkia organisaation käyttämiä maksukortteja ja kortinhaltijoita.

Politiikka tukee NIS2-direktiivin riskiperusteista ja suhteutettua lähestymistapaa.

---

## 2. Riskiperusteinen lähtökohta

Organisaatio tunnistaa, että:

* maksukortit ovat toiminnan kannalta **välttämättömiä**
* maksukorttien käyttöön liittyy **väistämättömiä riskejä**
* kaikkia riskejä ei voida poistaa, mutta ne voidaan **hallita, rajoittaa ja siirtää**

Tavoitteena ei ole riskittömyys, vaan **hallittu ja hyväksyttävä riskitaso**.

---

## 3. Korttitietojen käsittely

* Maksukorttitietoja saa antaa **vain rajattuun määrään luotettavia ja tunnettuja palveluntarjoajia**
* Korttitietoja ei saa tallentaa tarpeettomasti kolmansien osapuolten järjestelmiin
* Korttitietojen jakaminen impulsiivisesti tai tuntemattomille palveluille on kielletty

➡️ *Riskien minimointi hyökkäyspintaa pienentämällä*

---

## 4. Tunnusluvun (PIN) suojaus

* Tunnuslukua ei saa kirjata ylös fyysisesti tai digitaalisesti
* Tunnusluku on pidettävä vain kortinhaltijan muistissa
* Tunnuslukua ei saa jakaa kenellekään

➡️ *Henkilökohtainen ja organisatorinen tietoturvakontrolli*

---

## 5. Fyysinen korttien säilytys

* Maksukorttia ei tule kuljettaa mukana ilman perusteltua tarvetta
* Kun korttia ei käytetä, se säilytetään yhdessä, suojaisessa ja valvotussa paikassa
* Korttia ei jätetä näkyville tai helposti anastettavaksi

➡️ *Fyysinen turvallisuus ja omaisuuden suojaus*

---

## 6. Kortin mukana kuljettaminen

Kun maksukorttia on tarpeen kuljettaa mukana:

* kortti pidetään **aina kortinhaltijan välittömässä hallinnassa**
* kortti suojataan **radioaaltoja estävällä (RFID/NFC) suojakotelolla**
* korttia ei säilytetä taskuissa tai paikoissa, joissa hallinta voi hetkellisesti kadota

➡️ *Defense-in-depth: tekninen + fyysinen suojaus*

---

## 7. Taloudellisten riskien rajaaminen

* Maksukortille asetetaan **nosto- ja käyttörajat**, jotka rajaavat mahdollisen väärinkäytön vaikutusta
* Organisaatio hyödyntää korttiyhtiöiden tarjoamaa **vastuunsiirtoa ja reklamaatiomenettelyjä**

➡️ *Riskin vaikutuksen rajaaminen ja riskin siirto*

---

## 8. Poikkeamat ja incident-tilanteet

Mikäli epäillään maksukortin väärinkäyttöä:

1. Kortti suljetaan välittömästi
2. Asiasta ilmoitetaan pankille ja korttiyhtiölle
3. Tarvittaessa tehdään rikosilmoitus
4. Käynnistetään reklamaatioprosessi
5. Tapaus dokumentoidaan riskienhallinnan kehittämiseksi

➡️ *NIS2:n mukainen incident response ja recovery*

---

## 9. Jatkuva parantaminen

Kaikki maksukortteihin liittyvät poikkeamat hyödynnetään:

* riskien uudelleenarviointiin
* kontrollien parantamiseen
* käyttäytymismallien kehittämiseen

---

## 10. Yhteenveto

Maksukorttien käyttö perustuu tietoiseen riskin hyväksymiseen, ennaltaehkäiseviin kontrolloihin ja selkeään vastuunjakoon. Politiikka varmistaa, että riskit tunnistetaan, rajoitetaan ja hallitaan NIS2-direktiivin edellyttämällä tavalla.

---

# 📋 Mitä opittiin → Luotiin riskirekisteri maksukortin käytölle (NIS2 / ISO 27005)

| Risk ID | Omaisuus (Asset)             | Uhka (Threat)                        | Haavoittuvuus (Vulnerability)                  | Todennäköisyys | Vaikutus  | Nykyiset kontrollit                                                    | Riskin käsittely       | Jäännösriski | Tila       |
| ------- | ---------------------------- | ------------------------------------ | ---------------------------------------------- | -------------- | --------- | ---------------------------------------------------------------------- | ---------------------- | ------------ | ---------- |
| R01    | Korttitiedot                 | Korttitietojen väärinkäyttö verkossa | Korttitietoja käytetään ulkoisissa palveluissa | Keskitaso      | Korkea    | Korttitiedot vain luotettuihin palveluihin, seuranta, reklamaatiomalli | Lieventäminen + siirto | Matala       | Hyväksytty |
| R02    | Maksukortti (fyysinen)       | Kortin katoaminen tai anastus        | Kortti voi joutua vääriin käsiin               | Matala         | Korkea    | Korttia ei kuljeteta turhaan, säilytys suojaisessa paikassa            | Lieventäminen          | Matala       | Hyväksytty |
| R03    | Maksukortti (fyysinen)       | Lähimaksun väärinkäyttö              | NFC/RFID mahdollinen                           | Matala         | Keskitaso | RFID-suojakotelo, fyysinen hallinta                                    | Lieventäminen          | Matala       | Hyväksytty |
| R04    | PIN-koodi                    | PIN-koodin paljastuminen             | Inhimillinen virhe, kirjaaminen                | Matala         | Korkea    | PIN vain muistissa, ei tallennuksia                                    | Lieventäminen          | Matala       | Hyväksytty |
| R05    | Taloudellinen turvallisuus   | Taloudellinen tappio väärinkäytöstä  | Täysi luottoraja käytettävissä                 | Keskitaso      | Korkea    | Nostorajat, korttiyhtiön vastuu                                        | Rajaaminen + siirto    | Matala       | Hyväksytty |
| R06    | Maksukyky                    | Pitkittynyt taloudellinen haitta     | Hidas reagointi                                | Matala         | Korkea    | Reaaliaikainen seuranta, välitön kortin sulku                          | Lieventäminen          | Matala       | Hyväksytty |
| R07    | Luottamus maksujärjestelmään | Incidentin hallinnan epäonnistuminen | Epäselvät toimintamallit                       | Matala         | Keskitaso | Selkeä toimintaketju (pankki, kauppias, poliisi)                       | Lieventäminen          | Matala       | Hyväksytty |

---

## 🧠 Miten reksteriä luetaan

* **Todennäköisyys ei ole nolla** → siksi riski on olemassa
* **Vaikutus on korkea** → siksi kontrollit ovat kriittisiä
* **Jäännösriski on matala** → siksi riski voidaan hyväksyä

👉 ISO- ja NIS2-maailmassa tämä on **täydellinen riskiperustelu**.

---

### Mitä tarkoittaa *jäännösriski*?

**Jäännösriski** on se **riski, joka jää jäljelle**, vaikka olemme jo yrittäneet vähentää riskiä kaikin järkevin keinoin.

👉 Eli: **Vaikka teemme asiat oikein, jotain voi silti mennä pieleen.**

> *“Mitä voi vielä tapahtua, vaikka olemme varautuneet?”*

---

**Esimerkki tietoturvasta**
* **Riski**: Tietomurto
* **Toimenpiteet**: Palomuurit, monivaiheinen tunnistautuminen, käyttäjäkoulutus
* **Jäännösriski**: Hyökkääjä löytää uuden haavoittuvuuden tai käyttäjä tekee virheen

---

## 🎯 Riskirekisterin yhteenveto (audit-lause)

> Tunnistetut maksukortteihin liittyvät riskit on arvioitu, lievennetty, rajoitettu ja osittain siirretty. Jäännösriskit ovat hyväksyttävällä tasolla ja niitä seurataan jatkuvasti. Toteutunut tapaus vahvistaa toteutettujen kontrollien tehokkuuden eikä osoita riskienhallinnan epäonnistumista.

---

## 💡 Muista

> **Hyvä riskirekisteri ei estä tapahtumia → Se estää vahingot.**

---

# 🧠 Mitä opittiin → Uusi ajattelumalli

NIS2-direktiivi perustuu jatkuvaan riskiajatteluun, ei yksittäisten tapahtumien optimointiin.

---

## 1️⃣ Lähtöoletus: Jotain menee joskus pieleen

**Ajattelun muutos**

❌ *“Miten estämme kaiken?”*  
✅ *“Mitä tapahtuu, kun jokin toteutuu?”*

* Riskien olemassaolo ei ole epäonnistuminen
* Eskalaatio on **ajan kysymys**, ei jos-kysymys

👉 Ammattilainen ei kysy *tapahtuuko*, vaan *milloin ja miten hallitusti*.

---

## 2️⃣ Arvo ennen riskiä

**Kysy aina ensin:**

* Miksi tätä tarvitaan?
* Mitä menetetään, jos tätä ei käytetä?

**Esimerkki:**

* Maksukortti → mahdollistaa normaalin toiminnan
* Ilman korttia → toiminta hidastuu tai estyy

👉 **Riski syntyy arvosta**, ei huolimattomuudesta.

---

## 3️⃣ Riskit tunnistetaan ennen kuin ne realisoituvat

**Hyvä ajattelumalli ei vaadi täydellistä tietoa**

**Riittää, että:**

* tunnistat todennäköiset uhkat
* hyväksyt inhimilliset ja tekniset rajoitteet

**Tärkeää:**

* riskit kirjataan *ennen* incidenttiä
* mitään ei arvioida jälkiviisaasti nollatoleranssilla

👉 *“Tiesimme tämän olevan mahdollista”* on vahva lause auditoinnissa.

---

## 4️⃣ Kaikkia riskejä ei poisteta → Ne käsitellään

Ajattelumalli käyttää **neljää päätöstä**, ei yhtä:

* 🛡️ **Lievennä** (mitigate)
* ✂️ **Rajoita vaikutusta** (limit)
* 🔁 **Siirrä** (transfer)
* ✅ **Hyväksy** (accept)

Täydellinen suoja = epärealistinen
Tasapainoinen suoja = ammattimainen

---

## 5️⃣ Kontrollit ovat kerroksia, eivät muureja

**Defense-in-depth ajattelutapana**

* käyttäytyminen
* tekniset ratkaisut
* fyysiset ratkaisut
* sopimukset ja vastuunjako

Yksittäinen kontrolli voi pettää. Useampi kontrolli **ostaa aikaa ja pienentää vahinkoa**

👉 Turvallisuus = *aikaa reagoida*.

---

## 6️⃣ Incident on testi, ei tuomio

Kun riski realisoituu, ajattelumalli kysyy:

* Havaittiinko se ajoissa?
* Toimiko reagointi?
* Rajautuiko vaikutus?
* Palautuiko toiminta?

❌ *“Miksi tämä tapahtui?”*  
✅ *“Toimiko prosessi?”*

---

## 7️⃣ Onnistumisen mittari ei ole nolla incidenttiä

**Kypsyyden mittari:**

* vaikutus jäi pieneksi
* toiminta jatkui
* vastuut olivat selkeitä
* paniikkia ei syntynyt

👉 Hyvä prosessi kestää myös huonon päivän.

---

## 🧩 Ajattelumalli yhdessä lauseessa

> **Emme suunnittele järjestelmiä välttääksemme kaikki häiriöt — vaan kestämään häiriöt hallitusti.**

---
