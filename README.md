## Mikä?
Kiljusta kertovan vihkosen LaTex-lähdekoodit ja muu oheismateriaali

## Miten?

### PDF:n luominen
Tarvitset `pdfpages`-paketin ja toimivan LaTex-asennuksen. Kääntäminen pdf:ksi tapahtuu komentoriviltä
```pdflatex basepdf_1.tex && pdflatex basepdf_2.tex && pdflatex kiljukirja.tex```
Valmista vihkosta voi levittää tulostettuna ympäriinsä esim. puistoissa, baareissa, illanistujaisissa jne. Pull requestit uusilla resepteillä ja/tai asiallisilla muutoksilla ovat aina tervetulleita.

### Muokkaaminen
Muokkaukset tehdään tiedostoon `basepdf_1.tex`, josta koko kirjanen koostetaan.