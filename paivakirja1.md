# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Minulla ei ollut paljon vaikeuksia ensimmäisten tehtävien kanssa, koska minulla on ollut muutama kurssi missä olemme tehneet projekteja githubin kautta, mutta tuli paljon uusiakin asioita vastaan. Suurin osa asioista olivat minulle tuttuja, mutta pääsin myös syventymään eri komentoihin esimerkiksi "git init" on aina tullut minulle käytettyä vain, koska GitHub suosittelee, kun tekee projektin, mutta en oikeasti tiennyt, mitä se tekee ennen kuin syvennyin asiaan paremmin. 

Minulle uusia asioita olivat git log:in käyttö, en ikinä tiennyt, että voin katsoa sieltä "historian" muutoksista, ja se oli mielestäni aika kätevä komento. Samalla minä en aikaisemmin käyttänyt git restore tai git revert, jotka olisivat olleet minulle aika käteviä vanhemmissa projekteissa, koska olen muutaman kerran joutunut manuaalisesti poistamaan kaikki tekemäni asiat. 

Minulla ei ollut suurta ongelmaa, mutta esimerkiksi git revert ja git restore olivat uusia, jolloin kävin myös netissä tutustumassa niihin tästä linkistä: https://git-scm.com/docs. 

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git init | Luoo tyhjän repositorion hakemistoon |
| git add | Lisää tiedoston lähetettäväksi repositorioon |
| git clone | Cloonaa repositorion omaan koneeseen |
| git commit -m | kirjoitetaan viesti kun lähetetään repositorioon |
| git push | Lähettää muutokset repositorioon |
| git log | näyttää minkälaisia muutoksia on tehty |
| git revert | Palauttaa viimeisimmän commitin |
| git restore | Palauttaa sen jälkeen kun on tehty git add, mutta ennen git pushia |
| git status | Katsotaan status, eli nähdään esimerkiksi mitä tiedostoja ollaan lähettämässä repoon |
| git checkout -b | Tehdään uusi branch |
| git switch | Vaihdellaan branchien välillä |
| git push origin | Pushataan tiettyyn haluamaan branchiin |
| git branch | Katsotaan missä branchissä ollaan |
