## Helpen en bijdragen aan ROSA

We zijn blij dat je er bent en erg blij dat je dit leest. We hebben feedback
en bijdragen nodig om ROSA beter en bruikbaarder te maken. 

Er zijn een paar manieren waarop je kunt bijdragen aan het verbeteren van 
ROSA. 
- De makkelijkste manier is om een [issue](https://github.com/edustandaard/rosa/issues) 
  in te vullen in github. 
  De beheerders van ROSA zien dit en kunnen de vraag inplannen in het 
  onderhoudsproces.
- Als je een uitbreiding gemaakt hebt op ROSA en je wil deze overdragen
  aan Bureau Edustandaard voor opname in de ROSA, neem dan contact op
  met [Bureau Edustandaard](mailto:info@edustandaard.nl).
- Als je mee wil helpen met de ontwikkeling van het archimate model en de
  [ROSA wiki](https://www.wikixl.nl/wiki/rosa/index.php/Hoofdpagina), neem 
  dan vooral contact op met [Bureau Edustandaard](mailto:info@edustandaard.nl).

### Issue invullen
Ok, je hebt een issue met het model of met de wiki. We hebben een paar templates 
gemaakt om ons te helpen met het begrijpen van je issue en van de actie die je 
van ons wil:
 - **Bug**. Er staat iets op de [ROSA wiki](https://www.wikixl.nl/wiki/rosa/index.php/Hoofdpagina)
  en je weet zeker dat het niet klopt. Vul het template zo volledig mogelijk in, 
  wij pakken het zo snel mogelijk op.
 - **Feature request**. Er staat iets niet op de wiki, maar het is wel relevant 
  om het toe te voegen. Ook hiervoor geldt, vul het template zo volledig mogelijk 
  in. Het is belangrijk om hierbij contactinformatie op te nemen, het is voor 
  ons namelijk vaak lastig om de expertise te vinden die nodig is om bepaalde 
  zaken op te lossen.
 - **Vraag**. Er is iets onduidelijk, of het valt niet in een van bovenstaande 
  categorieën. Stel de vraag, vergeet niet om contactinformatie in te vullen 
  als je persoonlijk antwoord wil. 

### Ontwikkelen van het ROSA model
Ok, je helpt met de ontwikkeling van het ROSA model. Er zijn een paar code 
conventies in het model om rekening mee te houden. Zie hiervoor onze 
[CODING GUIDELINE](CODINGGUIDELINE.md).

### Oplossen issue
Ok, je hebt een issue opgelost. Dit willen we melden in onze Changelog, 
zodat we de belanghebbenden van ROSA periodiek kunnen informeren over de 
aangebrachte wijzigingen. Gebruik hiervoor de volgende commit message 
template:

bug/feature: Samenvatting in ongeveer 50 letters of minder.

Gedetailleerdere uitleg, als het nodig is. Hou een lege regel tussen 
de bovenste regel en de nadere uitleg, daarmee kunnen we automatisch 
samenvattingen genereren. 

Leg uit wat het probleem is dat je met deze commit oplost. Focus op wat en 
waarom, niet op 'hoe' (dat zien we wel in de views). Heeft je wijziging 
(mogelijk) impact op andere delen of bij-effecten? Vermeld dat dan ook.

 - Gebruik opsommingen als je wil
 - Als deze commit gerelateerd is aan een issue, neem je het issue-nummer
   op in de laatste regels van het commentaar. Gebruik hiervoor de 
   [autolink](https://help.github.com/articles/autolinked-references-and-urls/) 
   features van github.
 - Geef de relatie tussen je commit en het issue aan met "Fix \#123", 
   "Closed \#123", "Resolve \#123", "See also \#123".

Fix: #123
See also: #456
