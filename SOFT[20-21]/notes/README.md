# Bitno za vezbe - projekat

Bitno je uociti da podaci korisceni za procenu kvaliteta modela ni na koji nacin ne smeju biti upotrebljeni prilikom treninga.

Ovo deluje kao trivijalna stvar, ali zapravo je lako mozemo prekrsiti. 
Npr. u slucaju ako radimo normalizaciju, i ako normalizaciju uradimo nad celim skupom podataka, u sustini cemo dobiti bolje rezultate nad nasim trening skupom.
Stoga jeste trivijalna stvar ali o kojoj se treba voditi racuna !

## Kako evaluirati model ?

Test skup treba cuvati dok ne dobijemo idealan model nad nasim trening skupom, kada to dobijemo onda u okviru jedne evaluacije mozemo iskoriti taj test skup i ne vise !
