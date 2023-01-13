# Google1
Erste Schritte
Wär des ohne den Maestro möglich?

## Unser erstes GAS-Script

Unser erstes Beispiel:

```js
function onLoad(){
  let ui = SpreadsheetApp.getUi();
  // Or DocumentApp or FormApp.
  ui.createMenu('Haushalt')
      .addItem('Monat kopieren', 'triggerMonatKopieren')
      .addItem('Datei sichern', 'triggerDateiSichern')
      .addItem('Monat löschen', 'triggerMonatLöschen')
      .addItem('Jahr löschen', 'triggerJahrLöschen')
      .addToUi();
}
```