# Kako napraviti pivot tablicu?


```{infonote}
**Četiri osnovna elementa pivot tablice**

- **Redovi (*Rows*)** - Kategorije koje se prikazuju s lijeve strane tablice.
- **Stupci (*Columns*)** - Kategorije koje se prikazuju u gornjem dijelu tablice.
- **Vrijednosti (*Values*)** - Brojevi koji se izračunavaju (zbroj, broj, prosjek…).
- **Filtri (*Filters*)** - Omogućuju prikaz samo dijela podataka.
```

## Kreiranje pivot tablice - korak po korak

### Korak 1: Označite tablicu s podacima
Kliknite na bilo koju ćeliju tablice i na tipkovnici pritisnite kombinaciju tipki *Ctrl + A*


![Korak 1](images/pivot1_sr.png)

### Korak 2: Pokrenite kreiranje pivot tablice
Kliknite na *Insert* (1), *PivotТable* (2) i odaberite opciju *From Table/Range* (3)

![Korak 2](images/pivot2_sr.png)

### Korak 3: Odaberite gdje želite da se nalazi vaša pivot tablica
Možete odabrati novi radni list (*New Worksheet*) ili lokaciju na istom radnom listu (*Existing Worksheet*) (4) (u tom slučaju potrebno je da kliknete na ćeliju unutar koje će se nalaziti gornji lijevi ugao vaše pivot tablice) (5). Potvrdite klikom na *Ok*. (6)

![Korak 3](images/pivot3_sr.png)

### Korak 4: Upoznajte uređivač pivot tablica
Postavke pivot tablice vršite povlačenjem polja (7) u određene zone (8).

![Korak 4](images/pivot4_sr.png)

### Korak 5: Dodajte retke (*Rows*) i vrijednosti (*Values*)
Za prvi primjer iz uvoda u zonu *Rows* povukli smo polje *voće*. U zonu *Values* povukli smo polje *količina [kg]*

![Korak 5](images/pivot5_sr.png)

```{infonote}
Način izračuna u području Values možemo promijeniti preko opcije Value Field Settings. Osim zadanog zbroja (Sum), dostupni su i Average (prosjek), Count (broj unosa), Min i Max. Važno je znati da će, ako se u područje Values postavi tekstualno polje, pivot tablica umjesto zbroja automatski prikazati broj pojavljivanja tog teksta (Count).

```

### Korak 7: Dodajte stupce (opcionalno)
Tablicu u kojoj se vidi i na koji način su kupci plaćali dobili smo dodavanjem polja *način plaćanja* u zonu Stupci (*Columns*) (10)

![Korak 6](images/pivot6_sr.png)

```{infonote}
Ako se dogodi da vam se zatvori prozor s desne strane koji omogućuje podešavanje prikaza pivot tablice, možete ga ponovno otvoriti tako da kliknete na bilo koju ćeliju pivot tablice i odaberete opciju Show field list.

```
### Korak 8: Dodajte filtre (opcionalno)
Dodavanje filtara omogućit će vam da iz velike količine podataka brzo izdvojite i prikažete samo one vrijednosti koje su vam u danom trenutku potrebne, bez izmjene početne tablice i dodatnih izračuna. 
 

```{infonote}
Iako je pivot tablica povezana s originalnom tablicom, izmjene u njoj se ne ažuriraju automatski. Nakon svake izmjene potrebno je desnim klikom na pivot tablicu odabrati opciju Refresh, kako bi se svi rezultati osvježili.

```
## Pivot grafikon

Podaci iz pivot tablice mogu se prikazati i grafički. Na taj način rezultati postaju pregledniji i lakše se uočavaju razlike i odnosi.

Pivot grafikon se izrađuje na sljedeći način:

Kliknite unutar pivot tablice i iz izbornika odaberite opciju *PivotChart*. Odaberite vrstu grafikona i potvrdite izbor.


![Pivot grafikon](images/chart1_sr.png)

```{infonote}
Grafikon je povezan s pivot tablicom, što znači da se svaka promjena u tablici automatski prikazuje i na grafikonu. Prilikom grafičkog prikaza, prednosti primjene filtara posebno dolaze do izražaja.

```

![Pivot grafikon](images/chart2_sr.png)