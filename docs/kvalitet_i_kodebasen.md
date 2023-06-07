# ✨ Kodekvalitet: Transparens og kultur for kontinuerlig forbedring

For mig drejer kvalitet i en kodebase sig primært om transparens og kultur, og i mindre grad et enøjet fokus på et måltal fra bug-trackeren. 
Her her er mine vigtigste erfaringsbaserede pointer der italesætter hvordan man kan arbejde med at forbedre kvaliteten i en kodebase:


---

#### Det drejer sig om mennesker og kultur.
De første gevinster man bør høste er ved at opfordre til en kultur med par-programmering, code-reviews og hyppig refactoring i fælleskab.

---

#### Kodekvalitet er en aftale, ikke et måltal.
Anvendes det kun som et måltal skades innovationen og teamets forskelligheder risikerer at skabe konflikter istedet for at skabe sammenhold og fremdrift.

---

#### Lav aftaler om Definition of Done.
Lad være med at formulere tekniske mål, men registrer User Stories og lav aftaler med modtageren om hvornår storien er opfyldt. Det forhindrer myter om lav kvalitet.

---

#### Skab tillid med åbenhed og mange små leverancer
Når alle er enige om hvad der IKKE bliver leveret i denne omgang og kan se mening i de aftale prioteringer fremadrettet, øges tilliden til kodekvaliteten.

---

#### Fejl er ikke pinlige, de er kilder til læring og forbedring.
Isoler fejl til testmiljøer og skab en åben kultur hvor dialog, nysgerrighed, eksperimenter og humor omkring bugs skaber en tryg base for alle udviklere på teamet.

---

Men indrømmet, teknik og metoder spiller naturligvis også ind. 
Udvikling af nye metoder og værktøjer på dette område er efter min mening en af de afgørende byggesten, for at sikre succes for open source. Det er en rivende udvikling der primær drives som åbne økosystemer med bæredygtige forretningsmodeller omkring open source. Jeg ser dermed ikke disse metoder og værktøjer som døgnfluer, men som potentielle til at blive de-facto standarder for udvikling og leverance af digital infrastruktur og digitale ydelser. Det er for omfattende at beskrive alle økosystemerne her, men jeg har udvalgt min egen top 3 over afgørende indsatser der kan forbedre kvalitet i både kodebasen men også igennem hele softwarens livscyklus:

---

#### Automatiser og implementer moderne værktøjer.
Mange iterationer skaber øget arbejde med administration og klargøring af kode. Let denne byrde fra udviklernes skuldre med [automatiseret integration og udrulning](https://opensource.com/article/18/8/what-cicd). Dette frigører tid til at skrive kode af højere kvalitet og det er min erfaring at det giver en større arbejdsglæde hos udviklerne. 
For yderligere kvalitet kan statiske kode-analyseværktøjer integreres efter behov.

---

#### Vend strømmen
Udnyt mulighederne i de moderne automatiserede udrulningsworkflows og begynd at anvende deklarativt erklærede software udrulninger i et pull mønster fremfor push med [GitOps](https://www.weave.works/technologies/gitops/).
Mulighederne for automatiseret understøttelse af sikkerhedstjek, kvaliteteskontrol og compliance kan dramatisk forbedre ikke kun kodekvaliteten, men kvaliteten i hele leverancen!

---

#### Stil et færdigt udviklermiljø til rådighed.
Opsætning og vedligehold af udviklermiljøer er en tidsrøver og en fokusdræber.  Standardiserede udviklermiljøer med indbygget kvalitetssikring frigører tid, øger kvaliteten og gør det nemt for teamet at samarbejde.

---
