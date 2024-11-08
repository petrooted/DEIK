```
"Formulák és termek"
```
```js
Elsőrendű logikai nyelvben két fő elemet különböztetünk meg:

1. **Formulák**: Ezek állításokat jelölnek, például *P(x)* jelentheti azt, hogy "*x zöld*." 
A legegyszerűbb formula az **ítéletváltozó**, 
amely egy konkrét állítást jelöl, mint például "*A*" (ami azt jelentheti, hogy "*esik az eső*").

2. **Termek**: Ezek objektumokat jelölnek. 
Egy egyszerű term például egy változó, mint "*x*", vagy egy konstans, mint "*a*" (mondjuk, hogy "*Alma*"). 
Összetett termek lehetnek, mint például "*f(x)*," ahol "*f*" egy függvény, amely egy objektumot leír.

A nulladrendű logikában egyszerűbb a nyelv: 
nincsenek benne termek, 
így nem használunk objektumokat – csak kijelentéseket, mint "*A igaz*" vagy "*B hamis*."
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

```
"Kvantorok"
```
```js
A logikai szimbólumok lehetnek kvantorok:

"Az univerzális kvantor" (egy jelölése a "minden" kifejezésnek)
\forall az jele és (\forall x A) olvasata "minden x-re érvényes A"

"Egzisztenciális kvantor" (egy jelölése a "létezik olyan" kifejezésnek)
\exists a jele és (\exists x A) olvasata "létezik olyan x hogy A"

Ezen esetekben x egy individuumváltozó és A egy tetszőleges (de az x-et általában mint paramétert tartalmazó) formula.

Az "individuum" szó jelentése egyén, egyed. A szót gyakran az egyediség, egyéniség értelemben használják.
Forrás: https://lexiq.hu

Mivel az egyszerűbb nulladrendű nyelvekben nincsenek termek, ezért nincsenek individuum változól sem, és kvantorokat sem használunk.
```
