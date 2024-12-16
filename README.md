# Napredni-SWE
__Repozitorijum koji ce se koristiti za kacenje materijala koji je potreban za polaganje predmeta napredni SWE__

## Tutorijal za _Webflow_: Razvoj interaktivnih _web_ sajtova bez kodiranja  

## **1. O projektu**

Projekat služi kao tutorijal za korišćenje Webflow-a. Glavni cilj je da se:  
- Ukaže na prednosti ovog moćnog alata.  
- Prikaže kako se _Webflow_ koristi za kreiranje interaktivnih i responzivnih *web*-sajtova.  
- Objasni struktura i način rada sa *Webflow-om* (od instalacija do _publish_-ovanja Vaseg prvog _web_ sajta)

## **2. Šta je Webflow?**

**Webflow** je platforma za vizuelni dizajn i razvoj veb-sajtova koja omogućava korisnicima da kreiraju, dizajniraju, i objavljuju veb sajtove bez potrebe za pisanjem koda. Platforma automatski generiše visokokvalitetan HTML, CSS, i JavaScript kod u pozadini, omogućavajući dizajnerima i programerima da se fokusiraju na kreativne aspekte projekta. Webflow se koristi za kreiranje responzivnih sajtova, e-commerce rešenja, i složenih interakcija i animacija.

### **Istorija Webflow-a**

Webflow je osnovan 2013. godine u San Francisku od strane **Viktora Kjua** i **Peta Loksa**. Ideja za Webflow proizašla je iz potrebe za alatkom koja bi omogućila dizajnerima da stvaraju profesionalne veb sajtove bez potrebe za angažovanjem programera ili učenjem koda. Osnivači su želeli da reše problem u industriji veb dizajna, gde su dizajneri morali da koriste složene alate ili rade u saradnji sa developerima kako bi implementirali njihove dizajnerske ideje.

Kroz prve godine razvoja, Webflow je odjednom postao popularan zbog svoje jedinstvene kombinacije dizajnerskog interfejsa i sposobnosti generisanja čistog koda. Platforma je omogućila profesionalnim dizajnerima da sami kontrolišu kako će sajt izgledati i funkcionisati, a istovremeno su imali pristup tehničkoj strani veb sajtova bez potrebe da budu stručnjaci za kodiranje.

### **Kako je nastao?**
___
Platforma je započela kao alat za dizajn i generisanje HTML koda, ali je brzo evoluirala u sveobuhvatan alat koji uključuje i CMS (sistem za upravljanje sadržajem), hosting, i mogućnosti za kreiranje složenih animacija i interaktivnih efekata. Webflow je brzo postao popularan među dizajnerima zbog svoje fleksibilnosti, vizuelnog pristupa razvoju i činjenice da je omogućavao potpunu kontrolu nad svim aspektima dizajna sajta.

Danas, Webflow je prepoznat kao lider u prostoru no-code i low-code platformi, sa više od 2 miliona korisnika širom sveta, uključujući profesionalne dizajnere, razvojne timove, i preduzetnike.

**Webflow** je napredna platforma za vizuelni dizajn i razvoj veb-sajtova koja kombinuje kreativnu slobodu grafičkog uređivača sa tehničkim mogućnostima alata za programiranje. Omogućava korisnicima da dizajniraju i razvijaju potpuno funkcionalne veb-aplikacije bez potrebe za ručnim pisanjem koda. Platforma automatski generiše visokokvalitetan HTML, CSS i JavaScript kod u pozadini, dok korisnik kroz intuitivan interfejs vizualizuje izgled i funkcionalnost sajta.

Pored toga, Webflow integriše sistem za upravljanje sadržajem (CMS), pruža opcije za pouzdan hosting i podržava napredne funkcionalnosti poput prilagođenih animacija, interaktivnih elemenata i responzivnog dizajna za različite uređaje.
<br>

### **Ključne prednosti Webflow-a**
- **Intuitivan vizuelni interfejs**: Omogućava brzu realizaciju dizajnerskih ideja uz minimalno tehničko predznanje.  
- **Podrška za responzivni dizajn**: Kreiranje sajta koji se prilagođava svim veličinama ekrana, od mobilnih uređaja do desktop računara.  
- **Automatizacija složenih animacija i interakcija**: Pruža alatke za dodavanje dinamičnih prelaza i vizuelnih efekata bez potrebe za programerskim znanjem.  
- **Kompatibilnost za različite korisnike**: Pogodan je i za dizajnere koji žele vizuelnu kontrolu nad izgledom, kao i za programere koji cene kvalitetan kod koji platforma generiše.  
- **Sveobuhvatno rešenje za razvoj veb-sajtova**: Pored dizajna i razvoja, Webflow obuhvata hosting, upravljanje sadržajem i održavanje sajta, što značajno pojednostavljuje ceo proces.  

Ovaj alat je idealan za one koji teže profesionalnim rezultatima, a žele da prevaziđu ograničenja tradicionalnih metoda razvoja.

## **4. Koraci za kreiranje i pokretanje Webflow projekta**

Odmah cemo napomenuti da instalacija koja je potrebna u nekim ddrugim tenhologijama poput Reacta, Angulara, ovde nije potrebna.
Da biste pokrenuli i kreirali Webflow projekat, pratite sledeće korake:

### **1. Registracija i prijava na Webflow**
- Posetite [Webflow zvaničnu stranicu](https://webflow.com).
- Kliknite na "Get Started" ili "Sign Up" ako još nemate nalog.
- Izgled oficijalnog WebFlow sajta ![Webflow official site](assets/WebFlow%20official%20site.png)
- Registrujte se koristeći email adresu ili Google nalog.
- Prijavite se u svoj Webflow nalog.

### **2. Kreiranje novog projekta**
- Kada se prijavite, na početnoj stranici kliknite na **"Create New Project"**.
- ![Izgled WebFlow sajta nakon uspenog prijavljivanja] (assets/Izgled%20sajta%20nakon%20logovanja)
- Izaberite jedan od dostupnih **template-a** (predložaka) ili izaberite **blank project** za kreiranje sajta od nule.
  - Ako koristite predložak, samo odaberite dizajn koji vam se sviđa.
  - Ako birate praznu opciju, bićete preusmereni na prazan radni prostor gde možete početi sa dizajnom.

### **3. Dizajniranje sajta**
- **Dodavanje elemenata**: Koristite panel sa leve strane da dodate različite elemente poput teksta, slika, dugmadi i formulara.
- **Stilizovanje**: Na desnoj strani, možete koristiti opcije za stilizovanje svakog elementa, kao što su boje, margine, padding, veličine fontova i druge opcije.
- **Responzivnost**: Webflow automatski prilagođava dizajn za različite uređaje (mobilne telefone, tablete, desktop), ali možete dodatno prilagoditi dizajn za svaki uređaj putem opcije "Device Preview".

### **4. Dodavanje interakcija i animacija**
- Da biste dodali animacije i interakcije, izaberite element koji želite da animirate.
- U panelu desno izaberite opciju **"Interactions"** i postavite željene animacije kao što su prelazi (transitions), hover efekti ili animacije pri skrolovanju stranice.

### **5. Postavljanje domena (opciono)**
- Ako želite da povežete svoj Webflow projekat sa sopstvenim domenom:
  - Idite na **Project Settings** > **Hosting**.
  - Unesite naziv svog domena u polje **"Custom Domain"**.
  - Slijedite instrukcije da povežete domen i postavite DNS zapise kod svog hosting provajdera.

### **6. Pregled sajta**
- Da biste pregledali svoj projekat, kliknite na dugme **"Preview"** u gornjem desnom kutu ekrana.
- Ovo će omogućiti da vidite kako vaša stranica izgleda pre nego što je objavite.

### **7. Publikovanje sajta**
- Kada ste zadovoljni sa dizajnom, kliknite na **"Publish"** dugme u gornjem desnom kutu.
- Izaberite opciju za objavljivanje na Webflow-ovoj domeni ili na svom prilagođenom domenu (ako ste ga povezali).
- Kliknite na **"Publish"** i vaš sajt će biti objavljen.

### **8. Preuzimanje Webflow fajlova (opciono)**
- Ako želite da preuzmete fajlove sajta (HTML, CSS, JS) i postavite ih na svoj server:
  - Idite na **Project Settings** > **Code Export**.
  - Kliknite na **"Prepare ZIP"** da preuzmete sve potrebne fajlove.

---

Ovo su osnovni koraci za kreiranje i pokretanje Webflow projekta. Nakon što završite sa dizajniranjem, možete dalje prilagođavati sajt, dodavati nove stranice i funkcionalnosti prema potrebi.




