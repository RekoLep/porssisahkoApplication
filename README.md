# Seminaarityö: Päivittäisen pörssisähkön hinnan näyttävä React Native -sovellus

## Johdanto
Tavoitteena oli tehdä React Nativella mobiilisovellus hyödyntäen TypeScriptiä. Tämä oli ensimmäinen kerta, kun käytin lähes koko projektissa TypeScriptiä. Projektin tarkoituksena oli oppia TypeScriptin käyttöä React Native -sovelluksessa ja samalla toteuttaa hyödyllinen työkalu sähkön hinnan seuraamiseen.

## Sovelluksen kuvaus
Sovellus näyttää käyttäjälle päivän **pörssisähkön hinnan** selkeässä ja helposti ymmärrettävässä muodossa. Sovellus hakee hinnat verkosta ja esittää ne visuaalisesti, esimerkiksi taulukon tai graafin muodossa.

### Keskeiset ominaisuudet
- Päivittäisen pörssisähkön hinnan näyttö.
- Hinta esitetään tuntikohtaisesti.
- Helppokäyttöinen mobiilikäyttöliittymä.
- TypeScriptin avulla tarkka tyypitys ja virheiden minimointi.

## Projektin rakenne
```
PorssisahkoApplication/
├─ .expo
├─ assets/
├─ node_modules/
├─ src/
│  ├─ api/
│  │  ├─ CurrentPriceApi.ts
│  │  └─ PaticularPrice.ts
│  ├─ CountUp.tsx
│  ├─ DailyPriceChart.tsx
│  ├─ HomeScreen.tsx
│  └─ Style.tsx
├─ .gitignore
├─ app.json
├─ App.tsx
├─ index.js
├─ package-lock.json
├─ package.json
└─ tsconfig.json
```
## Käytetyt teknologiat
- Expo
- React Native
- TypeScript
- JavaScript
### Valmiit komponentit
- Count Up: https://reactbits.dev/text-animations/count-up
- React-native-chart-kit: https://www.npmjs.com/package/react-native-chart-kit

#Pohdintaa TypeScriptistä
JavaScript on joustava, mutta tyypitön kieli, mikä voi johtaa virheisiin vasta tuotannossa. TypeScript tuo statisen tyypityksen, joka auttaa löytämään virheet jo kehitysvaiheessa. Selkeät tyypit tekevät koodista ennustettavaa, luettavaa ja helpommin ylläpidettävää, mikä on erityisen arvokasta tiimityössä ja suurissa projekteissa.

TypeScriptin modernit ominaisuudet, kuten generics ja union-tyypit, mahdollistavat monimutkaisen logiikan selkeän mallintamisen. Vaikka käyttöönotto vaatii aluksi hieman vaivaa, se vähentää virheitä, helpottaa refaktorointia ja tekee koodista kestävää pitkällä aikavälillä.
