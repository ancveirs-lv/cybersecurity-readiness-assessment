# Kiberdrošības gatavības pašnovērtējums uzņēmumam

> Šis novērtējums ir gatavības un pierādījumu nepilnību instruments. Tas nav atbilstības konstatējums, sertifikācija, audits vai nozares specifisko prasību aizstājējs.

## Atbilžu stāvokļi

- `UNKNOWN` — Nezināms / nav pierādījumu
- `CLAIMED` — Apgalvots
- `DOCUMENTED` — Dokumentēts
- `IMPLEMENTED` — Ieviests
- `VERIFIED` — Verificēts
- `NOT_APPLICABLE` — Nav attiecināms

## Novērtējums

### Pārvaldīt

#### C01

Kiberdrošības mērķi ir sasaistīti ar organizācijas misiju, kritiskajiem pakalpojumiem un ieinteresēto pušu vajadzībām.

**Ieteiktā darbība:** Dokumentē rezultātus, kas kiberdrošībai jāaizsargā, un kas no tiem ir atkarīgs.

**Avoti:** `nist_csf20`

#### C02

Kiberdrošības lomas, lēmumu tiesības un riska īpašumtiesības ir skaidras.

**Ieteiktā darbība:** Piešķir atbildīgos īpašniekus un definē, kurš drīkst pieņemt būtisku kiberrisku.

**Avoti:** `nist_csf20`, `nis2`

#### C03

Vadība definē vai apstiprina kiberdrošības riska toleranci un prioritātes.

**Ieteiktā darbība:** Fiksē riska toleranci un izmanto to konfliktējošu lēmumu risināšanai.

**Avoti:** `nist_csf20`, `nis2`

#### C04

Būtiskas kiberdrošības politikas ir ieviestas, pārskatītas un piesaistītas atbildīgajiem īpašniekiem.

**Ieteiktā darbība:** Katrai politikai nosaki īpašnieku, ieviešanas pierādījumu un pārskatīšanas datumu.

**Avoti:** `nist_csf20`

#### C05

Piegādātāju un regulatīvie kiberdrošības pienākumi ir identificēti un sasaistīti ar kontrolēm un īpašniekiem.

**Ieteiktā darbība:** Izveido pienākumu un piegādātāju risku karti, sasaistot to ar īpašniekiem un pierādījumiem.

**Avoti:** `nist_csf20`, `nis2`

### Identificēt

#### C06

Organizācija uztur sistēmu, pakalpojumu, ierīču un būtisku programmatūras atkarību uzskaiti.

**Ieteiktā darbība:** Izveido minimāli pietiekamu uzskaiti un identificē aktīvus, kas atbalsta kritiskos pakalpojumus.

**Avoti:** `nist_csf20`

#### C07

Ir zināmi kritiskie dati, to atrašanās vietas, īpašnieki un sensitivitāte.

**Ieteiktā darbība:** Identificē kritiskās datu kopas, īpašniekus, atrašanās vietas un apstrādes prasības.

**Avoti:** `nist_csf20`

#### C08

Kritiskiem pakalpojumiem ir identificētas ārējās atkarības un vienpunktu atteices.

**Ieteiktā darbība:** Kartē kritiskos trešo pušu, savienojamības un platformu atkarību punktus pret pakalpojumiem.

**Avoti:** `nist_csf20`, `nis2`

#### C09

Ievainojamības un nedrošas konfigurācijas tiek atklātas ar definētiem procesiem.

**Ieteiktā darbība:** Definē, kā vājumi tiek atrasti, reģistrēti un piešķirti atbildīgajiem.

**Avoti:** `nist_csf20`

#### C10

Kiberriski tiek reģistrēti ar biznesa ietekmi, pieņēmumiem, īpašniekiem un apstrādes lēmumiem.

**Ieteiktā darbība:** Izmanto risku reģistru, kas nošķir pierādījumus, pieņēmumus un apstrādes statusu.

**Avoti:** `nist_csf20`

### Aizsargāt

#### C11

Piekļuve svarīgām sistēmām ievēro mazāko privilēģiju principu un stipru autentifikāciju.

**Ieteiktā darbība:** Vispirms pārskati privileģēto un attālināto piekļuvi; noņem nevajadzīgas tiesības.

**Avoti:** `nist_csf20`, `nis2`

#### C12

Atbalstītām sistēmām tiek pārvaldīti drošības atjauninājumi un konfigurāciju bāzes līnijas.

**Ieteiktā darbība:** Definē atjauninājumu un konfigurāciju prasības pēc kritiskuma un uzskaiti izņēmumus.

**Avoti:** `nist_csf20`, `nis2`

#### C13

Rezerves kopijas ir aizsargātas pret to pašu atteici vai kompromitāciju, kas var skart produkcijas sistēmas.

**Ieteiktā darbība:** Atdali kritiskās rezerves kopijas un pārbaudi tās reālistiska kompromitācijas scenārija gadījumā.

**Avoti:** `nist_csf20`

#### C14

Personāls saņem lomai atbilstošas kiberdrošības vadlīnijas un apmācību.

**Ieteiktā darbība:** Prioritizē augsta riska lomas un sasaisti apmācību ar reāliem procesiem.

**Avoti:** `nist_csf20`, `nis2`

#### C15

Sensitīvi dati tiek aizsargāti glabāšanā, pārsūtē un iznīcināšanā atbilstoši riskam.

**Ieteiktā darbība:** Definē minimālos aizsardzības noteikumus un pārbaudi ieviešanu.

**Avoti:** `nist_csf20`

### Atklāt

#### C16

Kritiskām sistēmām ir drošībai būtiski žurnāli, kas tiek glabāti pietiekami ilgi incidentu izmeklēšanai.

**Ieteiktā darbība:** Identificē minimālos žurnālus, kas vajadzīgi augstas ietekmes incidentu atklāšanai un rekonstrukcijai.

**Avoti:** `nist_csf20`

#### C17

Monitoringam ir definēti īpašnieki, brīdinājumu ceļi un reaģēšanas prasības.

**Ieteiktā darbība:** Definē saņēmēju, reakcijas laiku un eskalāciju kritiskiem brīdinājumu avotiem.

**Avoti:** `nist_csf20`

#### C18

Organizācija spēj atpazīt būtiskas anomālijas kritiskos pakalpojumos un identitātēs.

**Ieteiktā darbība:** Definē augstas vērtības anomālijas un pārbaudi, ka tās ir atklājamas.

**Avoti:** `nist_csf20`

#### C19

Atklāšana ietver būtiskus trešo pušu un mākoņpakalpojumu signālus, ja organizācija no tiem ir atkarīga.

**Ieteiktā darbība:** Identificē piegādātāju un mākoņpakalpojumu signālus, kam jānonāk incidentu procesā.

**Avoti:** `nist_csf20`, `nis2`

#### C20

Atklāšanas pārklājums tiek pārbaudīts ar reālistiskiem scenārijiem, nevis pieņemts no rīku ieviešanas fakta.

**Ieteiktā darbība:** Veic kontrolētus atklāšanas testus un fiksē sagaidītos un novērotos brīdinājumus.

**Avoti:** `nist_csf20`

### Reaģēt

#### C21

Izmantojams incidentu reaģēšanas plāns definē lomas, pilnvaras un eskalācijas ceļus.

**Ieteiktā darbība:** Veido plānu ap reālām lēmumu tiesībām un kontaktu ceļiem.

**Avoti:** `nist_csf20`, `nis2`

#### C22

Iekšējās, klientu, piegādātāju un regulatīvās komunikācijas pienākumi ir definēti pirms incidenta.

**Ieteiktā darbība:** Iepriekš definē komunikācijas īpašniekus, apstiprināšanas ceļus un vajadzīgo informāciju.

**Avoti:** `nist_csf20`, `nis2`

#### C23

Organizācija spēj ierobežot ietekmētos kontus, ierīces vai pakalpojumus, neimprovizējot pamata piekļuves.

**Ieteiktā darbība:** Sagatavo un pārbaudi ierobežošanas darbības ticamiem augstas ietekmes incidentiem.

**Avoti:** `nist_csf20`

#### C24

Incidentu pierādījumi tiek saglabāti pietiekami izmeklēšanai, mācībām un nepieciešamajai ziņošanai.

**Ieteiktā darbība:** Definē minimālos pierādījumu saglabāšanas soļus pirms incidenta.

**Avoti:** `nist_csf20`, `nis2`

#### C25

Mācības pārbauda reālus cilvēkus, lēmumus un atkarības, ne tikai plāna esamību.

**Ieteiktā darbība:** Veic scenāriju, kas prasa eskalāciju, ierobežošanu, komunikāciju un piegādātāju koordināciju.

**Avoti:** `nist_csf20`

### Atjaunot

#### C26

Kritiskām sistēmām un datiem ir pārbaudītas atjaunošanas procedūras.

**Ieteiktā darbība:** Veic pilna cikla atjaunošanas testu un saglabā pierādījumus.

**Avoti:** `nist_csf20`

#### C27

Atjaunošanas prioritātes un laika/datu zuduma mērķi ir definēti no biznesa vajadzībām.

**Ieteiktā darbība:** Saskaņo pakalpojumu atjaunošanas secību un pieļaujamo laika/datu zudumu ar biznesa īpašniekiem.

**Avoti:** `nist_csf20`

#### C28

Kritiskiem procesiem ir definēts degradēts vai alternatīvs darbības režīms.

**Ieteiktā darbība:** Definē minimāli dzīvotspējīgu pakalpojumu, kad parastās sistēmas nav pieejamas.

**Avoti:** `nist_csf20`

#### C29

Atjaunošanas plāni ņem vērā kritiskos piegādātājus un ārējās atkarības.

**Ieteiktā darbība:** Pārbaudi atjaunošanu, ja kritisks piegādātājs nav pieejams vai ir kompromitēts.

**Avoti:** `nist_csf20`, `nis2`

#### C30

Pēcincidenta mācības rada atbildīgas uzlabošanas darbības, kas vēlāk tiek verificētas.

**Ieteiktā darbība:** Sasaisti mācības ar īpašniekiem, termiņiem un verifikācijas pierādījumiem.

**Avoti:** `nist_csf20`
