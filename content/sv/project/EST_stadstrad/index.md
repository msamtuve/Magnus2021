---
title: Synliggöra trädens ekosystemtjänster utan inventering!
authors:
- admin
categories: 

tags: 
- demokrati
- ekosystemtjänster
- träd
- digital hållbarhet
- stadsträd.se
image:
  caption: 'Photo: Magnus Tuvendal'
  focal_point: ""
  placement: 2
  preview_only: false

# Summary for listings and search engines
summary: Nu är det möjligt att med en knapptryckning beräkna trädens ekosystemtjänster för en fastighet, en park eller en stadsdel. 
# Link this post with a project
projects: []
# Date published
date: "2022-04-18"
# Date updated
lastmod: ""
# Is this an unpublished draft?
draft: no

---

Med [stadsträd.se](http://www.stadstrad.se) är det möjligt att beräkna urbana träds reglerande ekosystemtjänster utan at först inventera områdets alla träd! Med finansiering från Boverket har vi byggt ett verktyg för att beräkna ekosystemtjänster. Detta är inte trolleri. Beräkningar bygger på det stora arbete som ligger bakom [iTreeECO](http://www.itreetools.org). 

Det som omedelbart beräknas är:

* **Retention av vatten**: interception av lövverk.

* **Lagrat kol:** kol som finns bundet i trädets biomassa 

* **Kolinbindning:** inlagring av kol på årlig basis. 

* **Reduktion av luftföroreningar**: ozon, svaveldioxid, kväve dioxide, kolmonoxid och partiklar mindre är 2.5 microns.

* **Återanskaffningskostnad (USA)**: ”… the Council of Tree and Landscape Appraisers, which uses tree species, diameter, condition, and location information”

Det som behövs för att beräkna ekosystemtjänster är en [trädkartläggning utifrån laserdata](https://info.stadstrad.se/kartlggning) (LiDAR). 

Vi gör vissa antagande och har tränat modellen med statistisk analys av träd från en svensk tätort där vi med data från 17000 träd. Resultatet är en approximation av det resultat man skulle få efter en fullständig inventering av områdets alla träd (som är både kostsam och tidsödande) och beräkning av ekosystemtjänster med iTreeECO. 

{{< figure src="EST_utan_inventering.png" title="Stadsträd.se har byggt in en funktion för *Rapid assessment of ecosystem services* - omedelbar beräkning av ekosystemtjänster från urbana träd." >}}

Projektet redovisas i rapporten [Nationell kartläggning av trädtäckning i städer och tätorter](https://www.boverket.se/sv/om-boverket/publicerat-av-boverket/publikationer/2021/nationell-kartlaggning-av-tradtackning-i-stader-och-tatorter/). 

Vill man gå djupare in i en analys av trädens ekosystemtjänster så är nästa steg att använda stadsträd.se för inventera platsens alla träd (mall för inventering enligt iTree finns). Data från kan enkelt exporteras ut och importeras in i iTreeECO (som är en fristående programvara fri att ladda ned). Dessa beräkningar görs inte lokalt i programvaran iTree utan skickas till en server i USA och tillbaka kommer en fullständig rapport. 

{{< figure src="EST_itree_inventering.png" title="Med stadsträd.se kan du inventera träd, exportera u din data och ta in dem i iTreeECO för vidare bearbetning." >}}

> Det kan vara en tröskel att använda iTreeECO. En kort kurs går att arrangera.
