# HANGMAN
![proposal sketch](https://cloud.githubusercontent.com/assets/15455490/11338312/a4c94a8a-91f3-11e5-9030-bb0c25531bc7.jpg)

# Desciption
Kort verslag hoe je door de app heen komt:
De application begint op het startscherm.  Er zijn 3 button’s op dit start scherm die mogelijkheden geven om door de app heen te manoevreren.  Settings zal het Settingscherm openen, History zal het High Score scherm openen en Play zal u naar de game verwijzen. Deze 3 schermen die te bereiken zijn door deze 3 knoppen hebben allemaal een back button om terug te komen op het start scherm.

De knop settings zal je verwijzen naar het settings scherm. Hier wordt bepaalt wat de settings van de game zijn. Twee text fields die mogelijkheid geven om het spel makkelijk of moelijk te maken. De laatste Segmented Fault button geeft jouw de mogelijk om het spel  evil of niet evil te maken. Evil betekent dat het word veranderd wordt als je het goed zou hebben geraden.  Niet evil zal het nooit veranderen.
Terug naar het Start scherm. 

De knop History/High Score zal je verwijzen naar het High score scherm. Hierop heb je een tabel (misschien wel een table met allemaal labels, geen table view, ik ben hier nog niet over uit) die de waardes van afgelopen games bevatten. Ook als de game wordt afgesloten en daarna word heropend zullen de waardes blijven staan. Terug naar het start scherm. 

De knop Play laat je naar het Game scherm gaan. Hier zal de game bespeeld worden. Er is een Guess button met een text field erbij die de mogelijkheid geeft om letter te raden. Als een letter geraden is zal er een * veranderen in de letter die is geraden.
Als je het woord goed hebt geraden zal de changing label aangeven dat het spel gewonnen is anders zal het vertellen dat er verloren is.

# Vereisten van de app  Title: HANG THE EVILMAN.

De handelingen die uit te voeren zijn op de schermen
Start scherm 1.
-	3 buttons:
o	Button 1 = settings 
o	Button 2 = history/High score 
o	Button 3 = play 

-	Label
-	Image view

Setting scherm 2.

-	3 labels:
o	Label 1 = Setting title
o	Label 2 = word length
o	Label 3 =  maximum geusses

-	2 text fields:
Text field 1 = length text field (between 1 – 46, longest word on earth)
Text field 2  = maximum geusses text field (between 1 -26)

-	Seg mented fault button:
o	Evil or not evil

-	Back button

High score scherm 3.

-	Table met name en score

-	Back button

Game scherm.

-	2 button’s:
Back button
New game button

-	2 label’s
Changing label ( if you won or lost)
Geusses to go label

-	Image view
-	X aantal * caracters
