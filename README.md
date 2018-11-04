# Introducere

..* Produsul vizeaza trei aspecte: gestionarea filmelor vizionate de utilizator, mentinerea unei evidente a celor 
pe care acesta doreste sa le vizioneze in viitor si prezentarea filmelor ce se afla in trending. In prezent exista 
o gama larga si variata de filme pentru toate
gusturile, uneori devenind greu sa retii ce filme ai vazut si ce doresti sa vezi in viitor. Utilizatorii vor avea posibilitatea
de a salva filmele vazute intr-o lista si de a-si crea "movie wishlists" unde sa adauge filemele pe care doresc sa le vada.
De asemenea, vor putea fi inspirati de filmele aflate in BoxOffice, la detaliile carora vor avea acces prin intermediul site-ului.

..* Filmele sunt o metoda placuta de petrecere a timpului liber, motiv pentru care produsul se adreseaza unei categorii
largi de utilizatori. De la tineri, studenti, pana la adulti, orice utilizator pasionat de cinematografie poate beneficia 
de produs, acesta fiind usor de folosit si deductibil.

..* Printre cele mai cunoscute platforme dedicate industriei cinematografice se numara IMDb, site ce pune la dispozitie
utilizatorilor posibilitatea de a adauga intr-un watchlist filme pe care doresc sa le vada. Cu toate acestea, IMDb nu 
se axeaza strict pe nevoile utilizatorului, prezentand in mare parte detalii despre filme, top-uri realizate de alti
utilizatori si noutati din domeniu.
Un alt produs asemanator de pe piata este Letterboxd, site ce permite utilizatorului crearea unui cont si mentinerea
unui "jurnal" in care va adauga filmele vizionate...

# Interfete aplicatie

![alt text](https://github.com/ioanabutoescu/trial/blob/master/45166329_347506286056168_388786542782447616_n.jpg "Photo 1")


# API Rest

Request:
```
POST /list
https://api.themoviedb.org/3/list?api_key=ba356a92fe0ee4b7fd13499d648a6d1e
```
Response:
```
201 Created
{
  "status_code": 1,
  "status_message": "The item/record was created successfully.",
  "success": true,
  "list_id": 95075
}
```