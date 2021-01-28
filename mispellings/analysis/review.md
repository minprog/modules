# Analyse: Mispellings

> De analyse van deze opdracht kun je alleen doen, maar het is ook prima om te overleggen met een andere student.

Voor de opdracht "Speller" moet je zelf een datastructuur ontwerpen en deze werkend maken in C. Het komt erop neer dat je vastlegt:

1. Hoe de data (woordenlijst) wordt gevormd in het geheugen van de computer
2. Hoe de functies van jouw spellchecker deze structuur kunnen opbouwen en afbreken

Voor de analyse ga je punt 1 uitwerken in een diagram met voorbeelden. Punt 2 ga je ook bestuderen en over nadenken maar je hoeft nog niet in pseudocode te werken.

## Inlezen

Ga nu eerst de [opdracht](/problems/cs50/speller) doorlezen en goed begrijpen. De bedoeling is dat je elke zin uit de opdrachtomschrijving goed begrijpt. Zo niet, dan kun je bijvoorbeeld de zin citeren op Ed en vragen wat er precies bedoeld wordt (en wat jij denkt). Lees ook goed de aangeleverde code door zodat je de structuur begrijpt van wat er al is, en wat jij moet maken. Daar hoort ook de `Makefile` bij en dergelijke.

Zo bouw je goed begrip op van wat er moet worden gemaakt.

## Datastructuur kiezen

Je kunt voor deze opdracht kiezen tussen het maken van een **hash table** of een **trie**. Beide structuren hebben hun voors en tegens, maar met allebei is ook een razendsnelle spellchecker te bouwen. Snelheid heeft voor nu echter geen prioriteit. Je eerste doel is om een *werkende* spellchecker te bouwen.

Kies of je een hash table of een trie wil bouwen.

## Een ontwerp maken

Je ontwerp voor de gekozen datastructuur bestaat uit twee onderdelen.

- Allereerst enkele schetsen van een structuur die "gevuld" is met een aantal woorden. Teken de structuur uit vanaf de basis. (Bij een hash table begin je bij een array, en bij een trie begin je met een "node".) Voor meer uitleg hierover kijk je het walkthrough-filmpje over de "load"-functie. Daarin laat Zamyla al wat van de structuren zien. Kies een aantal andere voorbeelden van woorden en teken hoe deze in jouw structuur gevat zullen worden.

	- Heb je een hash table gekozen, dan kun je je structuur pas uittekenen als je een hash-functie hebt gekozen. Gebruik om te beginnen een simpele hash-functie, bijvoorbeeld eentje die gebaseerd is op de eerste letter van het woord.

- Daarnaast moet je beschrijft hoe een "node" eruit ziet. Dit is het bouwsteentje van jouw datastructuur. Hoe meer nodes, hoe meer informatie in de structuur past. De vraag is: welke informatie staat opgeslagen in één node? Dat is een belangrijk inzicht. In het videocollege vind je al voorbeelden. Zorg dat jouw definitie van de node consistent is met de structuur die je wil bouwen.

Documenteer beide delen in een PDF, lever deze in en bespreek met een assistent via Zoom.

## Naar implementatie

Als je een heel goed beeld hebt van je structuur dan kun je gaan analyseren, in pseudocode, welke stappen er nodig zijn om de structuur op te bouwen. Dit kun je doen na het bespreken van je structuur en voorbeelden. De walkthrough-filmpjes in de opdracht helpen je de goede kant op.

## Inleveren

Hieronder kun je de PDF met je ontwerp en voorbeelden insturen.
