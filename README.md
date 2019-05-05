Tegu on React Native'ga arendatud Android rakendusega, kuhu saab lisada tegevusi ja märkida neid tehtuks.

Juhendi sain siit: https://egghead.io/courses/build-a-react-native-todo-application
Kuna video vaatamine on privaatne, lisan ka koodi. Kood on leitav sellelt aadressilt: https://github.com/browniefed/examples/tree/todo/editing
Juhend oli üldiselt hea, kuid oli mõeldud vanematele versioonidele, mis tekitas alguses raskusi. Ning juhendi autor rääkis päris kiiresti, nii et vahepeal oli päris keeruline aru saada, mis ja milleks tehakse. Õnneks näitas ta peale igat sammu, milline peaks rakendus hetkeseisuga olema ja see aitas kiiresti probleemid lahendada.

Õppisin kõige rohkem lahendama versioonide konflikte. Koolitus oli tehtud vanemale React-Native versioonile ning peale seda, kui üritasin mõnda aega saada rakendus tööle, otsustasin lõpuks arendada vanema versiooni peal.
Samuti oli mul see esimene lähem kokkupuude React'iga, selle loogika oli täiesti uus.
Omalt poolt lisasin võimaluse märkida tegevust tähtsaks ja filtri tähtsate tegevuste nägemiseks.

Projekti käivitamiseks enda arvutis on vajalik järgida juhiseid sellelt lehelt:
https://facebook.github.io/react-native/docs/getting-started

Tähtsamad sammud:
1. Installeerida Homebrew 
`https://brew.sh/`
2. Installeerida node
```
brew install node
```
3. Installeerida Watchman
```
brew install watchman
```
4. Lisada React Native cli versioon 0.37.0
```
react-native init --version="react-native@0.37.0
```