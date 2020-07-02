
## Drink App (Hemuppgift)

En sista inlämning blir hemuppgiften där vi kommer bedöma era kunskaper inom det vi har lärt oss i kursen. För att klara kursen måste man klara hemuppgiften. (Max betyg G). 

Inlämningen förväntas göras på de sättet vi har lärt oss i kursen. 

- Komponenter
- Bra uppdelningar i mappstrukturer
- Hooks (useState, useEffect etc)
- React Router
- Class Components (om de behövs)
- Stateless/functional components
- Props

Uppgiften går ut på att bygga en webbapplikation som hjälper till användaren att söka på olika cocktails. Användaren ska enkelt kunna söka på vad den vill och resultat ska visas upp bereonde på inmatningen. Finns inget resultat så ska detta också visas upp via en text.

Utöver att jobba med de principer vi har lärt oss är det också viktigt att inlämningen sker via Github. Ni ska jobba aktivt med Github och göra commits så vi kan sedan kolla hur ni har jobbat. **OBS: Inga commits efter inlämnigstiden är över!**


Tips: 
- Gå vidare om ni fastna på något
- Dela upp så mycket det går
- Jobba aktivt med commits i Github
- Övertänk inte

# Steg 1 
Skapa ett helt nytt projekt med något av följande sätt.

### Yarn

Öppna upp terminalen och kör  `yarn create react-app namnet-på-din-app`

### [](https://github.com/molndal-react/week-3-exercise#npm)NPM

Öppna upp terminalen och kör  `npm init react-app namnet-på-din-app`

Koppla projektet mot ett nytt Github projekt. 

# Steg 2
Installera React Router samt börja bygga upp din mappstruktur på de sättet du vill ha det. (Components, data, styling osv..)

# Steg 3 
Ladda in JSON filen som finns på Github och använd den som din datakälla. I JSON filen finns flera olika sorters drinkar och den datan du behöver för att visualisera ut den till användaren.

# Steg 4

Börja bygga på appen. Applikationen ska ha två sidor

 1. Home
 2. Explore

Home blir själva sidan användaren kommer först in på. ([Se bild](https://ibb.co/H4Z1MMf))
Explorer är sidan där användaren söker på drinkar ([Se bild](https://ibb.co/nQZcS5m)) 

Användaren ska kunna söka på vad som helst och det ska inte finnas några begräsningar på minst antal tecken i sökordet. Exempel på en sökning ([Se bild](https://ibb.co/f2c08Pb)) där användaren sökte på ordet *"te"* och fick fram alla drinkar som innehöll den söktexten.

Finns inte drinken så ska användaren få någon text som indikerar att inget kunde hitta i databasen med som innehöll den angvina texten.

Användaren ska sedan kunna trycka på dessa drinkar och då ska man navigeras till en ny undersida där man får lite mer information om drinken. ([Se bild](https://ibb.co/4wb2HqY))

# Steg 5

När användaren är inne på en drink T.ex "Americano" så ska den personen se en bild och instructions hur man gör drinken. Användaren ska också se följande funktionaliteter

1) En vänster pil samt en höger pil. Användaren ska kunna trycka på pilarna. Om pil vänster är tryckt då ska föregående drink visas upp och ifall pil höger så ska nästkommande drink visas upp. 

Ifall det inte finns förgående drink så ska pil vänster vara oklickbar (disable) och samma sak för höger. 

2) Användaren ska kunna lägga anonyma kommentarerer på drinkarna. Bygg ett enkelt kommenterasfält där användaren kan skriva sitt namn, rubrik och själva texten. Användaren ska sedan skicka på "Submit" knappen och så ska inlägget publiceras under drinken. 

När kommentaren är upplagd så ska man först se namnet, sedan tidpunkten, under namnet och tidpunkten ska rubriken komma sedan under den kommer själva texten. Likt Facebook, Instagram osv... 

OBS: Ni behöver ej koppla något mot databasen och detta ska endast funka lokalt. Ni behöver inte hellre tänka på att ha advancerad CSS i er kod. Gör den endast användarvänlig.


