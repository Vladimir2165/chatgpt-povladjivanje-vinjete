# chatgpt-povladjivanje-vinjete
Eksperimentalne vinjete korišćene u istraživanju povlađujućih odgovora ChatGPT-a i procenjene usklađenosti sa HHH principima.

Eksperimentalne vinjete za istraživanje povlađivanja ChatGPT-a

Ovaj repozitorijum sadrži eksperimentalni materijal korišćen u master radu:

„Preferencija prema povlađujućim odgovorima ChatGPT-a i implikacije na procenu principa usklađenosti HHH“

Istraživanje ispituje način na koji stepen povlađivanja u odgovorima ChatGPT-a i kontekst korisničkog upita (subjektivni i objektivni) utiču na procenu njihove usklađenosti sa principima korisnosti (helpfulness), iskrenosti (honesty) i bezopasnosti (harmlessness).

Vinjete su korišćene kao instrument za prikazivanje primera interakcije između korisnika i veštačke inteligencije. Kompletan skup materijala dostupan u ovom repozitorijumu obuhvata 100 vinjeta generisanih za pilot istraživanje, od kojih je 32 zadržano za glavno istraživanje.

## Dizajn vinjeti

Vinjete su dizajnirane tako da budu usklađene sa opštom strukturom i vizuelnim dizajnom konverzacijskog korisničkog interfejsa.

Svaka vinjeta prikazuje interakciju u formi **upit–odgovor**. Korisnički upit i odgovor veštačke inteligencije vizuelno su razdvojeni različitim pozicijama, bojama i identifikacionim ikonicama, čime se jasno označavaju uloge učesnika u konverzaciji. Dizajn je prilagođen postojećem iskustvu korisnika sa konverzacijskim interfejsima, sa ciljem smanjenja potencijalne konfuzije i kognitivnog opterećenja prilikom obrade materijala.

Vinjete su dizajnirane u programu **Figma**.

## Kontekst korisničkih upita

Vinjete su podeljene u dve kategorije u zavisnosti od mogućnosti objektivne evaluacije sadržaja korisničkog upita:

### Subjektivni kontekst

Subjektivni kontekst obuhvata upite koji se odnose na lične preferencije, stavove i dileme interpersonalnog karaktera, pri čemu njihov sadržaj nije moguće jednoznačno proceniti kao tačan ili netačan.

Za konstrukciju subjektivnih vinjeti korišćena je baza podataka **Open-Ended Questions (OEQ)**, koja sadrži pitanja namenjena personalnom savetovanju.

Upiti su birani tako da budu relativno kratki, razumljivi i dovoljno opšti da ne zahtevaju specifično iskustvo ili znanje za njihovo razumevanje. Pojedini upiti su redigovani radi uklanjanja irelevantnih informacija i postizanja veće jasnoće i nedvosmislenosti.

### Objektivni kontekst

Objektivni kontekst obuhvata upite koji sadrže tvrdnje ili pretpostavke koje je moguće proceniti kao tačne ili netačne na osnovu objektivnih kriterijuma i postojećeg znanja.

Za konstrukciju objektivnih vinjeti korišćena je baza **TruthfulQA: Benchmark for Evaluating Language Models**. Odabrani su primeri koji se odnose na relativno poznate teme i ne zahtevaju specifična stručna znanja.

Objektivni upiti formulisani su tako da jasno izražavaju pogrešnu pretpostavku korisnika. U tu svrhu korišćen je originalni upit zajedno sa odgovarajućim sadržajem iz kategorije `incorrect_answers`, uz prilagođavanje formulacije prirodnom tonu korisničkog upita.

## Generisanje odgovora

Pre izrade eksperimentalnog materijala testirano je više dostupnih GPT modela. Modeli su procenjivani prema prirodnosti generisanih odgovora na srpskom jeziku i sposobnosti prepoznavanja implicitnih karakteristika korisničkih upita i konstruisanja koherentnih odgovora.

Za potrebe istraživanja odabran je **GPT-5.3-chat-latest**, koji je u trenutku izrade materijala pokazivao zadovoljavajući nivo prirodnosti na srpskom jeziku i sposobnosti razumevanja relevantnih karakteristika korisničkih upita.

Odgovori su generisani putem **OpenAI Playground-a**. Svakom generisanju prethodila je sistemska instrukcija (*system message*) kojom su definisana pravila ponašanja i karakteristike odgovora modela.

U generisanju je korišćen **zero-shot pristup**, odnosno modelu nisu davani primeri odgovora koji bi predstavljali željeni način odgovaranja. Ovakav pristup omogućio je direktnu manipulaciju stilom odgovaranja putem sistemske instrukcije, bez dodatnog uticaja demonstracionih primera.

## Eksperimentalni materijal

Za pilot istraživanje izdvojeno je **10 subjektivnih i 10 objektivnih korisničkih upita**. Svaki upit je prošao kroz pet varijacija odgovora, što je rezultovalo sa ukupno **100 generisanih vinjeta**.

Nakon pilot istraživanja, za glavno istraživanje odabrane su **32 vinjete** na osnovu unapred definisanih kriterijuma.

U ovom repozitorijumu dostupne su vinjete korišćene u procesu razvoja eksperimentalnog materijala, uključujući kompletan skup od 100 vinjeti generisanih za pilot istraživanje.

## Organizacija fajlova

Vinjete se nalaze u direktorijumu `vignettes`.

Nazivi fajlova sadrže kodiranje eksperimentalnih karakteristika vinjeti i omogućavaju njihovo povezivanje sa odgovarajućim uslovima eksperimenta i istraživačkim podacima.

## Autor

**Vladimir Ćurčić**

Master akademske studije kliničke psihologije  
Filozofski fakultet Univerziteta u Beogradu

## Napomena o dostupnosti materijala

Kompletan eksperimentalni materijal dostupan je u ovom repozitorijumu kako bi se omogućio uvid u stimuluse korišćene u istraživanju. Zbog obima materijala, kompletan skup vinjeti nije prikazan u prilozima verzije master rada.
