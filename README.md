# team-eve2
Leerteam bestaande uit: Abdi, Johan, Natan, Rick, Robin

Het doel van dit project is bestanden gemakkelijk te delen en het gebruiken van versiebeheer.

## Werkwijze proces
- OTAP-proces

Ontwikkeling (O): Werk in een aparte feature/user story branch, test lokaal en update documentatie.\
Test & Acceptatie (T&A): Merge requests (MR) naar test-acceptatie, testen en verwerken van feedback.\
Productie (P): Na goedkeuring deploy naar productie.

- Git-workflow

- Branches:

**main:** Stabiele productiecode.\
**test-acceptatie:** Voor testen en integratie.\
**feature/fix:** Voor nieuwe features en fixes.

- Merge requests:

Alleen na lokale tests.\
Minimaal één review vereist.\
Na goedkeuring merge naar test-acceptatie.

- Release:

Code wordt pas naar main gemerged na acceptatie.\
Alleen teamleider of aangewezen persoon mag mergen.\
Change- en releasemanagement\
Feature branches: Elke wijziging in een aparte branch.\
Commits: Beschrijvende berichten, regelmatige updates.\
Code review: Focus op kwaliteit, leesbaarheid en standaarden.\
Test & Acceptatie: Testomgeving moet productie nabootsen.\
Productie: Alleen stabiele en goedgekeurde code wordt gedeployed.\


## Codeconventies
![header](https://miro.medium.com/v2/resize:fit:3676/format:webp/1*Owy1jcyKVYJo4zK9h15oOA.jpeg)
✅ Schrijf duidelijke, goed gedocumenteerde code\
✅ Schrijf commentaar in de code voor verduidelijking\
✅ DRY (Don't Repeat Yourself)\
✅ Gebruik duidelijke en consistente naamgeving (bestandnamen bijv.: main_file.py)\
✅ Volg een vaste code-indeling\
✅ Gebruik versiebeheer correct en commit elke keer als iets redelijk compleet is (Git)\


**MIT License 🟢**

*- Iedereen mag de code gebruiken, aanpassen en delen, zolang ze de originele licentie erbij zetten.*
- Dit is gekozen, omdat het geschikt is als je wilt dat anderen makkelijk kunnen bijdragen zonder restricties.
