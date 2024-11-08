```
"Formulák és termek"
```
```js
Egy elsőrendű logikai nyelvben kétféle kifejezést különböztetünk meg:

A "formula" – esetleges paramétereitől függő – állítás, melyet az érvelés leírására
használunk. Legegyszerűbb (paramétermentes) formája az ítéletváltozó, amely
egyetlen – logikai értelemben atomi – állítást jelöl.

A "termek" ezzel szemben objektumokat jelölnek. Ezek legegyszerübb formája
az individuumváltozó vagy a konstans szimbólum, de objektum leírás is készülhet
összetett formában.

A nulladrendű nyelvek szerkezete ennél egyszerűubb, (többek között) termeket nem
találunk benne.
```

```
"Formulák építése"
```
```js
Az atomi formulákból logikai szimbólumok segítségével összetett formulák építhetőek
A logikai szimbólumok lehetnek logikai összekötő jelek:
(Feltéve hogy A és B formulákat jelölnek)

\neg a negáció jel ahol \neg A olvasata "nem A".
\wedge a konjukció jel ahol (A \wedge B) olvasata "A és B".
\vee a diszjunkció jel ahol (A \vee B) olvasata "A vagy B".
\supset az implikáció jel ahol (A \supset B) olvasata "Ha A akkor B".
\equiv az ekvivalencia jel ahol (A \equiv B) olvasata "Pontosan akkor A ha B"
```
