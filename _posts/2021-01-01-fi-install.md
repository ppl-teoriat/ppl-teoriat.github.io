---
layout: page
title: Asennusohjeet
slug: asenna
---

## Esivaatimukset

Anki-sovelluksen käyttöönottoa varten tulet tarvitsemaan:
- Tietokoneen tai kannettavan
- Verkkoyhteyden

Sekä sovellus että kysymyspankki ovat ilmaisia.

> **Huom:** ensimmäisen käyttöönoton jälkeen voit harjoitella kysymyksiä pelkällä puhelinsovelluksella tai selaimessa.
> Ensimmäistä käyttöönottoa varten tulet kuitenkin tarvitsemaan tietokoneen tai kannettavan (Windows, Mac, tai Linux kaikki kelpaavat).

## Vaihe 1: Tilin luonti

1. Avaa <https://ankiweb.net/about> selaimessasi
1. Paina `Sign Up`-nappia
1. Luo itsellesi käyttäjätili
1. Hyväksy käyttöehdot
1. Varmista sähköpostiosoitteesi

## Vaihe 2: Sovelluksen lataus

1. Avaa <https://apps.ankiweb.net/> selaimessasi
1. Rullaa sivun alalaitaan
1. Paina `Download`-nappia
    - Valitse Qt6-versio
1. Asenna sovellus koneellesi

Jos tarvitset apua asennuksessa, voit klikata nappia jossa lukee `Installation & troubleshooting guide` latauslinkin alta.
Jos Qt6 versio ei toimi, kokeile myös Qt5-versiota.

5. Avaa Anki ja klikkaa `Sync`-nappia sovelluksen yläosassa
1. Kirjaudu sisään aiemmin luomillasi AnkiWeb-tunnuksillasi

## Vaihe 3: Lisäosa

Kysymyspankki on toteutettu käyttämällä `Multiple Choice for Anki`-lisäosaa.
Ladataan se nyt.

1. Klikkaa ylälaidassa olevaa `Tools`-valikkoa
1. Valitse `Add-ons`
1. Valitse `Get Add-ons`
1. Syötä `Code`-kenttään numero `1566095810`
    - Tämä on Multiple Choice for Anki -lisäosan ID, joka löytyy [tästä](https://ankiweb.net/shared/info/1566095810)
1. Paina `OK`-nappia kahdesti
1. Käynnistä Anki-sovellus uudelleen

Monelle käyttäjälle tämän lisäosan värit ovat hieman hämmentäviä.
Niitä pystyy konfiguroimaan seuraavasti:

1. Klikkaa ylälaidassa olevaa `Tools`-valikkoa
1. Valitse `Add-ons`
1. Klikkaa `Multiple Choice for Anki` -tekstiä
1. Vaihda tekstikentässä olevan `DEFAULT_COLOURING`-tekstin `ALTERNATE_COLORING`-tekstiksi
1. Tallenna painamalla `OK`

## Vaihe 4: Kysymyspankin lataus ja asennus

1. Avaa <https://ankiweb.net/shared/by-author/365788332> selaimessasi
    - Sivulta löytyy kaikki kysymyspankin kysymykset ja vastaukset jaettuna koealueisiin
    - `FI`-alkuiset koealueet ovat suomeksi, kun taas `EN`-alkuiset ovat englanniksi
1. Klikkaa haluamasi koealueen nimeä
1. Rullaa alas ja paina `Download`-nappia
    - Tämä lataa Ankin `.apkg` tiedoston
1. Avaa tietokoneesi latauskansio
1. Tuplaklikkaa lataamasi tiedostoa
    - Tiedosto avautuu Anki-pöytäsovelluksessa
1. Paina `Import`-nappia
1. Toista kohtia 2-6 kunnes saat asennettua kaikki haluamasi koealueet

Lopuksi **paina vielä `Sync`-nappia** yhdistääksesi lataamasi kysymyspankki AnkiWeb-palvelimeen.

> **Huom:** jos et jostain syystä pääse lataamaan kysymypankkia AnkiWebistä
> voit ladata sen suoraan [GitHub-repositoriosta](https://github.com/ppl-teoriat/ppl-teoriat.github.io/tree/main/questionbank/apkg). 

## Valmista tuli!

Nyt voit harjoitella ilmailun teoriakokeisiin Anki-pöytäsovelluksella.

Jos haluat ottaa käyttöön myös mobiilisovelluksen, jatka sen konfigurointiin: [**Mobiilisovelluksen asennusohjeet**](/mobiili)

Jos haluat harjoitella vain koneellasi tai selaimessasi, ohita mobiilisovellusosio ja jatka harjoitteluohjeisiin: [**Anki-käyttöohje**](/kaytto)
