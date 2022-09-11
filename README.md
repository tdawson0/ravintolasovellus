# Ravintolasovellus
Harjoitustyö Helsingin Yliopiston [Tietokantasovellus-kurssia](https://hy-tsoha.github.io/materiaali/) (tsoha) varten. Harjoitustyössä käytetään Pythonia/Flaskia, sekä PostgreSQL-tietokantaa.

Kurssin materiaalissa on annettu seuraava esimerkki ravintolasovelluksen ominaisuuksista:

---
Sovelluksessa näkyy tietyn alueen ravintolat, joista voi etsiä tietoa ja lukea arvioita. Jokainen käyttäjä on peruskäyttäjä tai ylläpitäjä.
- [ ] Käyttäjä voi kirjautua sisään ja ulos sekä luoda uuden tunnuksen.
- [ ] Käyttäjä näkee ravintolat kartalla ja voi painaa ravintolasta, jolloin siitä näytetään lisää tietoa (kuten kuvaus ja aukioloajat).
- [ ] Käyttäjä voi antaa arvion (tähdet ja kommentti) ravintolasta ja lukea muiden antamia arvioita.
- [ ] Ylläpitäjä voi lisätä ja poistaa ravintoloita sekä määrittää ravintolasta näytettävät tiedot.
- [ ] Käyttäjä voi etsiä kaikki ravintolat, joiden kuvauksessa on annettu sana.
- [ ] Käyttäjä näkee myös listan, jossa ravintolat on järjestetty parhaimmasta huonoimpaan arvioiden mukaisesti.
- [ ] Ylläpitäjä voi tarvittaessa poistaa käyttäjän antaman arvion.
- [ ] Ylläpitäjä voi luoda ryhmiä, joihin ravintoloita voi luokitella. Ravintola voi kuulua yhteen tai useampaan ryhmään.
---
Tarkoituksena on myös lisätä seuraavat ominaisuudet:
- [ ] Käyttäjä voi syöttää (ja kirjautunut käyttäjä tallentaa) oman sijaintinsa, ja järjestää ravintolat etäisyyden mukaan.
- [ ] Käyttäjä voi rajata hakutuloksia ravintolan etäisyyden (esim. < 5 km), arvioiden (esim. >= 4 tähteä), aukio-olon tai ryhmän/tyypin (esim. Italialainen, Kiinalainen, Kebab) mukaan.
- [ ] Käyttäjä voi tallentaa ravintoloita omalle suosikkilistalle.

## Alustava hahmotelma sovelluksen käyttämästä tietokantakaaviosta:

![ravintolasovellus](https://user-images.githubusercontent.com/113307391/189547534-e5503721-30ba-4a0a-97d8-06c98aeeb955.png)
