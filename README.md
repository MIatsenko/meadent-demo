# Predlog veb-sajta — Stomatološka ordinacija MEA:DENT

Demo (predlog) nove početne strane za stomatološku ordinaciju **MEA:DENT**,
Jurija Gagarina 247, Blok 45, Novi Beograd.

Stranica je napravljena na materijalima ordinacije — fotografije ordinacije i tima, tekstovi
o uslugama, radno vreme i kontakt podaci preuzeti su sa javnog sajta meadent.com.
Ovo nije zvaničan sajt ordinacije i nije javna ponuda: prikazuje kako bi početna strana mogla
da izgleda, pre bilo kakvog dogovora.

## Šta sadrži

- prvi ekran sa fotografijom prijemnog dela ordinacije i pozivom na zakazivanje;
- traka sa činjenicama: Google ocena, broj oblasti, broj stomatologa, radno vreme;
- dvanaest oblasti stomatologije, od implantologije i protetike na implantima do ortodoncije,
  oralne hirurgije i lečenja parodontopatije;
- tim: šest stomatologa (uključujući specijalistu parodontologije), sestra i administracija;
- galerija ordinacije;
- **forma za zakazivanje termina** (ime, telefon, usluga, željeni datum) sa proverom broja
  telefona i potvrdom posle slanja — na postojećem sajtu postoji samo opšta kontakt forma
  (ime, mejl, naslov, poruka), bez telefona, usluge i datuma;
- kontakt blok sa adresom, prevozom, parkingom i načinima plaćanja.

## Tehnički

Jedna statička stranica (`index.html`), bez eksternih biblioteka i bez mrežnih zahteva ka
trećim servisima. Prilagođena telefonu, tabletu i desktopu. `<meta name="robots" content="noindex">`.

Generisano iz šablona `demo_build.py` (jedna HTML stranica + `config.json` u izvornom projektu).
