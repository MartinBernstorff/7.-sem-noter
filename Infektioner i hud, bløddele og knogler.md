---
typora-copy-images-to: ./img
---

[TOC]
# Bakterielle infektioner i knogler, hud og bløddele `707`

##Osteomyelitis
Prævalens: 10/100.000 børn/år i Europa.

Infektiøs inflammatorisk proces i knogle.
Hvis det sidder i ryghvirvlerne: spondylitis eller spondylodiscitis.

Kan inddeles på basis af spredning (hæmatogen, lokalt eller på basis af perifær arteriosklerose) eller på basis af ætiologi (næsten altid pyogene bakterier, efterfulgt af mykobakterier).

###Hæmatogen spredning
S. aureus den dominerende årsag.

Hos børn ses også S. pyogenes, S. agalactiae og S. pneumoniae.

Hos voksne ses i 10-15% af tilfældene G- bakterier som E. coli, Klebsiella, Pseudomonas og Salmonella spp.

####Symptomer
#####Store rørknogler
Hovedsymptomer er bevægeindskrænkning og smerter i ledet.

Godt ==50%== har generelle inflammationssymptomer. *Objektivt* ses ømhed, varme og hævelse over leddet.

#####Spondylitis
Mere snigende, godt 50% er afebrile.

Kan give rodaffektion og tværsnintssyndrom i svære tilfælde.

#### Diagnostik

```mermaid
graph TD;
	1[Mistanke ud fra sygehistorie, objektiv undersøgelse <br>og inflammatoriske markører.]
	2[PET-CT<br>MR<br>Bloddyrkning<br>  <br>  <br>Bloddyrkning er:]
	D+[Diagnosen er stillet]
	4[Aspireres CT-vejledt og dyrkes]
	mon[Monitorér med SR og CRP]
	
	1-->2
	2-- Positiv -->D+
	2-- Negativ -->4
	1-- Mykobakterier eller svampe mistænkes -->4
	4-->D+
	D+-->mon
```

#### Komplikationer

Neurologiske skader og leddestruktion.

Evt. abscesser.

####Behandling
Startes når diagnosen er sikret, og kan i mange tilfælde afvente diagnostisk biopsi.

4 ugers IV efterfulgt af 4-8 ugers oral behandling, i store doser.

Kirurgisk drænage kan være indiceret.

###Lokal spredning
Hyppigst hos voksne over 50.

####Ætiologi
Typisk postoperativt ved operation på knogle.

Typisk S. aureus, sjældnere S. epidermidis.

Symptomer og kliniske fund som ved hæmatologisk spredning, dog oftere ingen generel affektion.

####Diagnose
Gentagne dyrkninger er essentielle, da bakterier der noramlt ses som forurening kan ære ætiologisk agens.


##Bakterielle infektioner i huden
Her omtales kun de infektioner der kan være led i en større, systemisk infektioner.

###Impetigo
`Børnesår`

![Impetigo](img/impetigo.jpg)

Smitsom hudsygdom, karakteriseret ved grupper af vesikler, som brister let og efterlader skorper og større huderosioner.

Kan skyldes både streptokokker og stafylokokker.

Hyppigst hos børn før skolealderen.

####Symptomer
Få mm stor, rød, kløende plet --(Under 1 døgn)--> Vesikler -> Brister med ravgul skorpe. Under skorpen ses en rød overflade.

Regionale lymfeknuder er forstørrede og ømme.

####Diagnose og ddx
**DDX** til varicella og HSV: Skorperne er ved impetigo tykkere og mere gule.

I udvalgte tilfælde kan dyrkning samt PCR være vigtig for DDX.

####Behandling
Daglig vask med sæbe og klorhexidin eller fusidin creme.

Svær impetigo give dicloxacillin p.o.

###Erysipelas
`Rosen`

![Impetigo](img/erysipelas.jpg)

==Skyldes næsten altid S. pyogenes, sjældnere andre streptokokker eller stafylokokker.==

Der kan ikke dyrkes og reinfektioner forekommer hyppigt.

####Symptomer og fund
Hyppigst på crus (75%) eller ansigt (20%).

Starter med en lille rød plet, spreder sig langs lymfekar. Giver en *skarpt afgrænset* kant mod den sunde hud.

Regionale lymfeknuder er forstørrede og ømme.

Mange kliniske infektionssymptomer og typisk voldsomt påvirket almentilstand, der kan endda ses delir.

####Komplikationer
Ved gentagne infektioner kan der ses skader på lymfekar med risiko for kronisk lymfødem.

####Diagnose og DDX
Næsten altid klinisk, kun sjældent er dyrkning positiv.

*Flegmoner (cellulitis)*: Tegn på inflammation ses primært centralt, afgrænsning mindre skarp, ingen bullaer.

*Zoster*: Forudgås af smertefulde paræstesier, almentilstanden mindre medtaget, affektionen typisk ensidig, vesikler bryder frem på én gang.

*Thromboflebitis*: På crus kan de være svære at skelne, ultralyd kan være en hjælp.

*Erysipeloid (svinerosen)*: Oftest på fingrene, og kun hos pt. der arbejder med kød og fisk.

###Flegmone
`Cellulitis`

Akut infektion der hurtigt spreder sig i specielt subcutis.

####Anatomisk lokalisation
==Hyppigste agens varierer alt efter lokalisation==, se `712`.

####Diagnose og DDX
Oftest klinisk, aspiration giver sjældent dyrkningssvar.

Vigtige ddx:

1. Nekrotiserende fasciitis
2. Gasgangræn

###Gasgangræn
Infektion, primært i muskler, hvor der udvikles luftfyldte bullaer.

Hyppigste agens er Clostridium perfringens, kan skyldes andre bakterier.

Sjælden. Skyldes oftest sår eller devitaliseret vær.

####Diagnose
Dyrkning af blod og sårsekret.

CT- og MR-scanning kan give information om udbredelse, men må **ikke** forsinke kirurgisk intervention.

####Behandling
Kirurgisk intervention og antibiotika.

###MRSA
1.000 tilfælde p.a., oftest hos raske.

Ved mistanke om infektion følges sundhedsstyrelsens retningslinjer om eradikationbehandling, se `edok`.


###Nekrotiserende fasciitis og streptokok toxisk shock syndrom
`Toxic shock syndrome | Necrotizing fasciitis`

Type 1: Blandingsinfektion med både aerobe og anaerobe.

Type 2: S. pyogenes

####Nekrotiserende fasciitis type 1
Ses efter kirurgiske indgreb, hos pt. med diabetes eller andre patienter med karlidelser.

#####Diagnose
Stilles klinisk. Skal suppleres med CT- eller MR, for at vise udbredelse og derfor bestemme, om kirurgi er indiceret.

####Streptokok toxic shock syndrom
Incidens 5/100.000/år.

Skyldes bakterielle eksotoksiner der fungerer som superantigener.

#####Symptomer
Udvikler nekrotiserende fasciitis dramatisk hurtigt, udvikling af shock inden for få timer.

Uforklaret hastigt stigende smerter -> feber, myalgier, diaré og anorexi -> bulladannelse.

#####Diagnose
Stilles primært klinisk på basis af hastig udvikling af lokalsymptomer og shock.

Ultralyd viser ofte manglende blodgennemstrømning, men kan ikke udelukke nekrotiserende fasciitis.

#####Behandling
Hurtig og ekstensiv:

- Kirugisk intervention
- Antibiotisk behandling
- Behandling af shock

###Stafylokok toxic shock syndrom (STSS)
`TSS`

Incidens 5 tilfælde årligt.

Skyldes eksotoksin der produceres af visse stammer S. aureus. Sjældens bakteriæmi.

####Symptomer og DDX
Høj feber, hypotension og diffust makulært eksantem som skaller af 1-2 uger efter debut.

Multiorganpåvirkning, karakteristisk:

- Myonekrose
- Sløret sensorium

**DDX**:

- Septisk shock
- Streptokok TSS -> hurtig kirurgisk indsats
- Scarlatina
- Leptospirose
- Kawasakis sygdom
- Svære virusinfektioner, eg. morbillivirus

####Diagnose
Kliniske fund + udelukkelse.

####Behandling
Vigtigste behandling *ikke* antibiotika da sygdommen skyldes præformeret toksin, evt. resterende bakterier behandles dog stadig.

- Behandling af shock
- Evt. sanering
- Antibiotika

###Stafylokok skallet hud syndrom
`Scalded skin syndrome | SSSS`

Generaliseret hudreaktion med epidermolyse pga. toksin.

Primærfukus ses ikke i huden.

Ses næsten udelukkende hos mindre børn.

####Symptomer
Pludselig rødme og ømhed + høj feber `--(mindre end ét døgn)-->` fladeformede bullae og afstødning af hud.

####Diagnose
Stilles klinisk.

####Forløb
Typisk fuld restitution

####Behandling
Antibiotika + omhyggelig væskesubstitution.

##Infektioner overført ved bid `715`
Inddeles efter:

1. Udseende
2. Lokalisation
3. Bidende agens

Risiko er størst ved bid af menneske, dernæst kat (80%), lavest ved bid af hund (5%).

Ved bid af flagermus skal man være opmærksom på evt. rabiesrisiko.

###Diagnose
Der skal altid dyrkes fra inficerede læsioner, både aerobt og anaerobt.

Skriv på rekvisitionssedlen at der er tale om en bidlæsion.

###Behandling
- Rense sår, evt. kirurgisk recision
- Antibiotikabehandling
- Overvej tetanus- og rabiesprofylakse.

###Profylaktisk behandling bør overvejes ved:

- Dybe læsioner, især:
  - ødem eller tegn på vævsskade
  - bid af kat eller menneske
  - mulig penetration til knogle eller led
- Sår på hænder eller i genitalregionen
- Sår i nærheden af led med protese
- Hos immunsvækkede


##Seksuelt overførte sygdomme
###HPV
`Human papilloma virus`
Almindelige vorter: verruca vulgaris
Kondylomer, prævalens 1% blandt seksuelt aktive.

Inkubationstid 3-6 mdr.

#### Diagnose

Ofte klinisk.

For maligne tumorer histologisk med PCR.

###Syfilis
`Treponema pallidum sp. pallidum`
![](img/treponema.jpg)

Overføres typisk ved samleje, kys, oral-genital og oral-anal kontakt kan også give smitte.

Ca. 300 p.a. i DK.

#### Symptomer

##### Primærstadiet:

Inkubation ca. 3 uger (1,5 til 12 uger): 
Chanker, typisk solitært ulcus med eleverede rande.

![](img/chanker.jpg)

Oftest smertefrit.

Oftest seropositiv på dette tidspunkt.

*Sekundærstadiet*: 6-24 uger efter infektion.
Udslet spreder sig til det meste af kroppen.

Mere end halvdelen har almensymptomer.

*Objektivt*: Generaliseret lymfadenopati, forøjede basiske fosfataser.

Ubehandlet udvikler ca. 1/3 tertiær syfilis med:

- Granulomatøs gummaer
- Kardiovaskulær syfilis
- Sen neurosyfilis

####Diagnose
*Primær og sekundærstadiet*: Påvisning af spirokæter ved PCR eller mørkefeltsmikroskopi.
*Tertiærstadiet*: Serologiske undersøgelser af blod og spinalvæske.

####Anmeldelse
Anmeldes skriftligt.

###Gonokokker
`Neisseria gonorrhoeae | N. gonorrhoeae`

####Anmeldelse
Anmeldes skriftligt

###Chlamydia
`Chlamydia trachomatis`

####C. trachomatis
Serovar A-C: Trakom
Serovar: D-K: Urethritis og cervicitis
L1-L3: Lymfogranuloma venerum

Hyppigste årsag til konjunktivitis hos nyfødte.

####C. pneumoniae
Pneumoni, især børn

####C. psittaci
Pneumoni, der smitter fra fugle.

####Diagnose
PCR på prøvemateriale.

#Tuberkulose og andre mykobakterier `719`
`TB | Tuberculosis`
380 p.a. i DK 2011, 2/3 indvandrere, 1/3 danskere.

Smitter via aerosoler, hvorfor pt. skal isoleres.

Kun 5-10% af de inficerede vil udvikle klinisk sygdom.

##Risikofaktorer
![](img/tuberkulose.png)

##Kliniske fund
Udvikler sig typisk over uger til måneder, afhænger af, hvilke organer der især er ramt.

Med tiden ses feber, træthed og vægttab grundet kronisk inflammation.

###Lungetuberkulose
Tør og siden produktiv hoste, evt. med hæmoptyse.

Rtg. thorax: Apikale, småplettede infiltrative forandringer.

![](img/tb_rtg.png)

Der kan ses hilusnær glandelforstørrelse.

Hos immunsupprimerede kan manifæstationerne mangle helt.

###TB uden for lungerne
Afhænger af lokalisation, alvorligste manifæstation er meningit.

###Diagnostik og DDX
DDX:

- Rheumatoide tilstande, især sarkoidose
- Maligne tilstande

####Lungerne
Dyrkning af mindst to ekspektorater
Trachesugning og ventrikelskylning kan være krævet.

Biopsier fra afficeret væv, herunder lymfeglandler.

####Metoder
#####Mikroskopi
Ziehl-Nielsen farvning.
Lav sensitivitet, dog klinisk relevant. Hvis mikroskopi-negativ er pt. ikke-smitsom.

#####PCR
Høj sensitivitet ift. mikroskopi, kan ikke skelne levende fra døde, kan være positiv flere måneder efter behandling.

#####D+R
Den ultimative diagnostiske metode.
Typisk vil bakterier erkendes inden for 2-3 uger, dyrkes dog i 7-8 uger før der gives endeligt svar.

#####IGFR
Kan være negativ ved immunkomprommiterede.

###Behandling
RIPPE

Der skal altid dyrkes for at observere for resistens, og dyrke igen efter 2 måneder, hvor pt. skal være seronegativ.

For yderligere behandlingslinjer, se `e-dok`.

| Stof        | Varighed                       |
| :---------- | :----------------------------- |
| Rifampicin  | 6 mdr.                         |
| Isoniazid   | 6 mdr.                         |
| Pyrazinamid | 2 mdr.                         |
| Pyridoxin   | Så længe der gives pyrazinamid |
| Ethambutol  | 2 mdr.                         |

OBS: Rifampicin er CYP-inducer.

###Anmeldelse
Skal anmeldes til embedslægen, og behandler skal igangsætte kontaktopsporing.

## Lepra `726`



 



























