PHPackaton2014
==============

Koncepcja konkursu PHPackaton 2014, organizowanego w ramach inicjatywy ![PHPers](http://phpers.pl/bundles/phpersapp/images/logo.png).

#Organizatorzy#

Organizatorami konkursu są przedstawiciele PHPersPL, reprezentowani przez

* Karol Sójko
* Kuba Zalas
* Leszek Krupiński
* Ktoś ze Śląska?
* Ktoś z Wrocławia?

W/w stanowią **Zespół ekspercki**, o którym kawałek niżej.

Michał Łukaszewski (pecado) pełni rolę Communication Officer'a:
* odpowiada na pytania
* pilnuje wysyłania powiadomień 
* stara się nadążyć za chaosem w skrzynce pocztowej.

#Cel#

* Integracja środowiska
* Dzielenie się wiedzą poprzez praktyczne jej wykorzystanie
* Popularyzacja technologii
* Popularyzacja dobrych praktyk programistycznych

#Projekty#

* projekt powinien być napisany w
  * PHP 5.4 lub 5.5
  * lub Hack (HHVM)
  * C - jeśli internal
* projekt powinien być udostępniony jako Free Software, ew. na licencji GPL lub WTFPL.
* repozytoria projektu powinny być publiczne (preferujemy GitHub lub Bitbucket)

Projekty powinny być prowadzone w metodologii Scrum. 

#Zespoły#

Przewidujemy, że w konkursie weźmie udział 4-6 zespołów.

Każdy zespół powinien składać się z 3-5 osób. Nie mniej niż 3 i nie więcej niż 5. Literalnie. Niscy również liczą się jako jedna osoba.

Zakładamy, że udział wezmą następujące zespoły:

* reprezentanci aktualnych ośrodków PHPersPL
    * Warszawa
    * Wrocław
    * Trójmiasto
    * Śląsk
* 2 sloty pozostaną do dyspozycji innych ośrodków, w których zawiąże się zespół i przedstawi projekt.


Jeśli z w/w _regionów_ będzie chciał wystartować więcej niż jeden zespół to....???

Jeśli ktoś z spoza w/w regionów będzie chciał dołączyć do zespołu z regionu to....???



#Ocenianie#

* każdy projekt będzie oceniany przez:
  * społeczność, której ocena stanowi 60% oceny końcowej
  * zespół "ekspercki", którego ocena stanowi 40% oceny końcowej

##Ocena społeczności##

Ponieważ społeczność jest nie do opanowania więc ocenia jak chce, choć fajnie by było gdyby oceniała mądrze.
  
##Zespół ekspercki##

Zespół ekspercki wystawia 4 oceny, każda daje maksymalnie 25% oceny końcowej zespołu
* jakość kodu: w ruch pójdzie analiza statyczna ze wszystkim co mamy do dyspozycji
  * każdy projekt musi mieć testy. 
  * nie ma znaczenia czy BDD czy TDD
  * nie ma wymagania 100% pokrycia kodu
  * jest wymaganie mądrego pokrycia kodu
* łatwość instalacji: 100% dostaje projekt, który działa po
  * wykonaniu composer install
  * wpisaniu lokalnych danych (db, ścieżki) do configa
  * reszta ma obcinane punkty
* jakość dokumentacji
* prowadzenie projektu - realizacja sprintów.


##Obowiązkowe jest stosowanie się do zasad##

* CleanCode
* SOLID
* [PSR-0](http://www.php-fig.org/psr/psr-0/), [PSR-1](http://www.php-fig.org/psr/psr-1/), [PSR-2](http://www.php-fig.org/psr/psr-2/), [PSR-3](http://www.php-fig.org/psr/psr-2/), [PSR-4](http://www.php-fig.org/psr/psr-2/)

**Oceniana będzie tylko aplikacja, nie wybrany framework: sugerujemy próbę podejścia Clean Architecture :)**

