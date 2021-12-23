Koraci kako generisati svog sertifikat.

1.Otvoriti stranicu.

2.Pritisnuti F12 ili desni klik > Inspect

3.Otvoriti tab "Console"

4.U konzoli pozvati funkciju: enkriptuj() i proslediti string podataka

4.1. Podaci moraju biti u formatu '{"ime": "Pera", "prezime":"Peric", "godina": "01-11-1999", "pol":"MUŠKO", "jmbg": "1111111111111"}'

4.2. Poziv ce izgledati ovako : enkriptuj('{"ime": "Pera", "prezime":"Peric", "godina": "01-11-1999", "pol":"MUŠKO", "jmbg": "1111111111111"}')

4.3. Ovo ce prikazati string u formatu: 'XXAkF3$#OAK4eSF25NjNCK41ADnj#kASFa !ASDA#as3t!#JjSA21esdfzddSFF='

5. Ovako dobijeni string dodati na vec postojeci url u formatu: eupraua.github.io/gov/?id=XXAkF3$#OAK4eSF25NjNCK41ADnj#kASFa !ASDA#as3t!#JjSA21esdfzddSFF=


6. Ukoliko je sve odradjeno kako treba polja ce se popuniti kako treba
