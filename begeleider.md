# Begeleider

De BraillePi start als deze wordt aangesloten. Het gebruikt het bestand word.txt waar de woorden/oefeningen staan. De inhoud hiervan kunt u wijzigen in microft word of een tekst-editor. Het bestand is in een zogenaamd platte tekst formaat.

Door een usb-stick met het bestand word.txt in de BraillePi te steken zal deze de inhoud automatisch gaan kopieren. Een volgende keer hoeft u de memory stick niet in de BraillePi te steken.

Voorbeeld Oefeningen staan in de menu’s aanvankelijk en revalidatie. U kunt natuurlijk ook zelf oefeningen maken.

Elke regel in het bestand word.txt is een activiteit. Hoe de activiteit gedaan moet worden wordt bepaald door het speciale karakter dat voor aan de regel staat.

Er zijn 6 verschillende type oefeningen.

  - lezen (op de leesregel staan letters of woorden lees deze) rechter-duimtoets vooruit, linker-duimtoets achteruit.
  - typen (type over wat op de leesregel staan, sluit af met rechter-duimtoets) karakter=$
  - links rechts (kies linker-duimtoets of recht-duimtoets) karakter < of > afhankelijk van de toets die moet worden ingedrukt. Tekst dat rechts resp. links van het karakter staat komt links, rechts op de leesregel te staan.
  - aanvullen (geef het antwoord, sluit af met rechter-duimtoets), bijvoorbeeld voor sommen. Karakter =
  - zoeken (zoek de cel die voor aanstaat, cursor-routing) karakter = #
  - dictaat (na-typen wat je hoort en afsluiten met rechter-duimtoets, LDT=backspace LMDT=space) karakter = @


Voorbeeld van het bestand word.txt

```
**lezen**
a a a a aap bal
typen $a a a $ba

**luister en typ**
@$aap @$aap bal
@$aap bal kam

**zoeken letters of woorden aap**
#aap aap bal a#aap bal
c#b b b c b b b c b b b c b b c

**luister en zoek letters of woorden**
@a#bal
@a#aap bal
@c#bbbcbbbcbbbcbbc
@aap#aap boom vis vuur

**aanvullen sommen (0 t/m 9999) (alleen numeriek antwoord)**
1 + 1=2
g g g g=4

**true or false**
groter meer
g g g>g g g g g g g g g g
true or false

**kleiner minder**
g g<g g g g g
```

