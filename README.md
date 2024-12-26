# Gromada Games app

# Projekat je podeljen u dva dela,Frontend deo se zove Gromada a backend deo se zove Gromada-backend (Directus CMS).

## Prilikom pokretanja celog projekta potrebno je otvoriti dva terminala (cd /gromada , cd /gromada-backend),klonirati sa Gitlab-a,instalirati za oba `npm install` i oba se pokrecu komandom `npm install`,kako za Frontend ('https://gromada.fincoreltd.rs') tako i za backend Directus ('https://gromada-directus.fincoreltd.rs/admin').

## Username i password za pokretanje Directus-a su ivan.marinkovic@fincore.com i finbet01..!!

## Directus dashboard sadrzi 5 kolekcija (About us, Properties, Modal content, Footer i Contact form).

## About us

### About us kolekcija je vezana za About Us stranicu na aplikaciji gde je postavljen wysiwyg editor i cela sekcija ispod slike je postavljena u pomenutom editoru.Taj deo se moze menjati kopiranjem teksta i stavljenjem u editor bez ikakvih dodatnih podesavanja.

## Properties

### Properties klekcija je najvaznija jer sadrzi sve podatke koji su vezani za Video igrice sa svim pratecim podacima.

#### Properties kolekcija (Parent kolekcija nad svim kolekcijama u nastavku) u kojoj se nalaze sve Video igre sa svim podacima vezanjim za nju.Nakon otvaranja te kolekcije prikazuju se sledeca polja i to Order by, Game icon placeholder, Single game placeholder i Single game feature placeholder.

#### Order by polje je polje po kojem se u kolkeciji moze vrsiti menjanje mesta kolonama (reorder) .

#### Game icon placeholder sadrzi polja Game icon, Title i Description i ova kolekcija je prikazana na Home stranici aplikacije Gromada games gde su prikazane sve Video igre.

#### Single game placeholder sadrzi polja background image, Logo, Types select i games description.Ova kolkcija je postavljena na stranici pojedinacne igre.

#### Single game feature placeholder sadrzi tri polja: Single props (sadrzi slike i opis igre koji se nalaze na delu stranice GAME FEATURES za svaku pojedinacnu igru, polje se moze reorder-ovati,bristai i dodavati novo polje),Pdf (polje sadrzi fajl u Pdf formatu svake igre sa uputstvom) i Launch Url (u polju se nalazi url ka igrici).

### Ova kolekcija je podeljena u 3 pod-sekcije i to: Data, Single game feature i Single game property.

### U Data kolekciji se nalaze sve osobine Video igrice koje moze ona sadrzati. (Platform,Volatility,Reels/Rows,Lines ...).Kolone se u ovoj sekciji mogu dodavati,preurediti i obrisati po potrebi.Zamena mesta kolonama se vrsi preko ikone Toggle manual sorting (Polje sa leve strane od ID naziva) gde se klikom na tu ikonu otvaraju sva polja i nakon toga se moze vrsiti zamena mesta kolonama.

### Single game feature je kolekcija o kojoj se nalaze sve karakteristike sa slikama i opisima Video igre.

#### U ovoj kolekciji se nalaze polja Image, Image title i Image description (Wysiwyg editor).Kolekcija je samostalna i sluzi za dodavanje novih feature-a za video igricu.

### Single game property (Parent collection) je kolekcija koja je direktno povezana sa kolekcijom Data(Child collection) i u ovoj kolekciji se nalaze sve osobine upisane za svaku Video igru pojedinacno.Prilikom dodavanja novih osobina igrice otvaraju se dva polja u koje unosimo sve podatke.Prvo polje je Single relation i klikom na input polje otvaraju nam se ponudjene stavke opisane u Data kolekciji.Drugo polje je property content i tu upisujemo vrednost odabrane osobine.

## Modal content

### Modal content kolekcija je vezana za Modal koji se otvara nakon klika na dugme Play koje se nalazi na svakoj stranici pojedinacne igre na Gromada games aplikaciji.Content je postavljen u wysiwyg editor-u i moze se menjati po potrebi.

## Footer

### Footer kolekcija sadrzi polja Logo, Commision Logo, Company name, Address, Privacy link, Description i Gambling Commision link.

### Footer pod-sekcija je Policy privacy kolekcija koja sadrzi Page title, Version, date i Contents wysiwyg editor polje. Verzija,datum i sadrzaj wysiwyg editora se menjaju prilikom dodavanja nove verzije Policy stranice i nakon dodavanja nove verzija staroj verziji je potrebno promeniti status na archived u polju Status na vrhu stranice.

## Contact Form

### Kolekcija Contact Form sadrzi polja name, email, phone, subject i message.Ova kolekcija je direktno povezana sa aplikacijom na stranici Contact gde se nalazi forma. Nakon klika na dugme Send u aplikaciji podaci se salju u ovu kolekciju gde se prikazuju pomenuti podaci za svaku popunjenu formu.
