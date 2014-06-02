PHPackaton2014
==============

Koncepcja konkursu PHPackaton 2014, organizowanego w ramach inicjatywy ![PHPers](http://phpers.pl/bundles/phpersapp/images/logo.png).

#Organizatorzy#

Organizatorami konkursu są przedstawiciele PHPersPL, reprezentowani przez

* Kacper Gunia
* Leszek Krupiński
* Karol Sójko
* Kuba Zalas
* Ktoś z Wrocławia?

W/w stanowią **Zespół ekspercki**, o którym kawałek niżej.

Michał Łukaszewski (pecado) pełni rolę Communication Officer'a:
* odpowiada na pytania,
* pilnuje wysyłania powiadomień,
* stara się nadążyć za chaosem w skrzynce pocztowej,
* ogarnia bieżącą dokumentację konkursu.

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
* projekt powinien być udostępniony jako Free Software, na licencji GPL lub WTFPL.
* repozytoria projektu powinny być publiczne (preferujemy GitHub lub Bitbucket)
* projekt powinien zawierać dokumentację na Wiki (tym samym ew. readme.md mogą na to wiki wskazywać, nie ma co powielać)
* ponieważ projekty zostaną w sieci sugerujemy dokumentację angielską, ale najważniejsze, żeby była aktualna, wyczerpująca i precyzyjna.

Projekty powinny być prowadzone w metodologii Scrum. Zarówno GitHub jak i Bitbucket dostarczają darmowego Issue Trackera i przestrzeń na Wiki projektu. Reszta to kwestia organizacji :>

#Obowiązkowe jest stosowanie się do zasad#

* CleanCode
* SOLID
* [PSR-0](http://www.php-fig.org/psr/psr-0/), [PSR-1](http://www.php-fig.org/psr/psr-1/), [PSR-2](http://www.php-fig.org/psr/psr-2/), [PSR-3](http://www.php-fig.org/psr/psr-2/), [PSR-4](http://www.php-fig.org/psr/psr-2/)

**Zespół eskpercki postara się, aby oceniana będzie tylko aplikacja, nie wybrany framework: sugerujemy próbę podejścia do Clean Architecture :)**

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

Zespół powinien mieć stałą strukturę w trakcie trwania projektu. Niemniej nie ma przeciwskazań, aby zespół korzystał z konsultacji, tak w zakresie technologii, konfiguracji narzędzi, prowadzenia projektu. Prosimy tylko o odnotowanie takiego wsparcia, wraz z czasem jego trwania, w dokumentacji na Wiki projektu.

Nie ma problemu, aby konsultacji udzielił członek Zespołu eksperckiego, o ile będzie wprost wymieniony w dokumentacji Sprintu/projektu. Wiedza ma płynąć, a nie być narzędziem terroru :)

Jeśli z w/w _regionów_ będzie chciał wystartować więcej niż jeden zespół to....???

Jeśli ktoś z spoza w/w regionów będzie chciał dołączyć do zespołu z regionu to....???

#Terminy#

##Zgłaszanie zespołów i projektów##

* Zespół wraz z projektem przedstawia się do 30.06.2014
* W zgłoszeniu zawarty jest
 * skład zespołu i jego nazwa kodowa :)
 * nazwa projektu i jego opis w 200 znakach (spacje się liczą)
 * link do repo
 * opcjonalnie link do CI
* do 05.07.2014 przedstawiona jest lista zatwierdzonych projektów (chyba, żeby bierzemy wszystkie jak leci)

##Czas trwania projektu##

* projekty można prowadzić do 31.08.2014 włącznie
* każdy push po tej dacie będzie traktowany jako złamanie zasad i oznacza dyskwalifikację
* Ankieta dla społeczności i zespołu eksperckiego zostaną uruchomione 1.09.2014
* Podsumowanie wyników i oficjalne ogłoszenie zwycięzców będzie miało miejsce na PHPConPL, 27.09.2014, Szczyrk _(nie żebym kogoś pytał, to taki pomysł :D )_

#Ocenianie#

* każdy projekt będzie oceniany przez:
  * społeczność, której ocena stanowi 60% oceny końcowej
  * zespół "ekspercki", którego ocena stanowi 40% oceny końcowej

##Ocena społeczności##

Ponieważ społeczność jest nie do opanowania więc ocenia jak chce, choć fajnie by było gdyby oceniała mądrze.

##Zespół ekspercki##

Zespół ekspercki wystawia 5 ocen, każda daje maksymalnie 20% oceny końcowej zespołu
* jakość kodu: w ruch pójdzie analiza statyczna ze wszystkim co mamy do dyspozycji
  * każdy projekt musi mieć testy. 
  * nie ma znaczenia czy BDD czy TDD
  * nie ma wymagania 100% pokrycia kodu
  * jest wymaganie mądrego pokrycia kodu
* łatwość instalacji: 100% dostaje projekt, który działa po
  * osadzeniu na maszynie (zip i/lub clone i/lub composer - wedle uznania, byleby działało!): 50%/10%
  * wpisaniu lokalnych danych (db, ścieżki) do configa: 50%/10%
* jakość dokumentacji
* prowadzenie projektu - realizacja sprintów.
* wykorzystanie narzędzi CI - preferujemy otwarte rozwiązania, ale jak ktoś się uprze na Jenkinsa to do niego też mamy dostęp ;)
  * Przy wykorzystaniu CI obowiązuje ta sama zasada co przy instalacji: po wciśnięciu guzika dostaję produkt przetestowany i gotowy do instalacji - w wybranej formie.

Oczywiście mamy świadomość, że jest rok 2014 i sporo się dzieje na warstwie Front Endu. Zachęcamy do wykorzystania tych możliwości. Prosimy jednak pamiętać, że główna wartość aplikacji powinna leżeć po stronie Back Endu. 

Niemniej Zespół ekspercki ma prawo do powołania "konsultantów": będą to osoby powszechnie znane i uznawane za biegłe np. w JS, CSS, Scrum, itp. Pomogą one ocenić jakość poszczególnych fragmentów aplikacji lub sposobu prowadzenia projektu. Może to wpłynąć na ocenę jednego z w/w obszarów.

##Jawność##

* każda ocena jest jawna i podpisana
* służyć temu będzie konieczność zalogowania się przez FB/G+/Tw/GitHub/Bitbucket aby oceny dokonać.
* nie będziemy się szczególnie napinać na blokady, mające na celu zapewnienie 1głos-1osoba, bo i tak znajdziecie na to sposób
* wierzymy, że nie będzie siary i podpisanie się pod swoją oceną oznacza poważnego człowieka, który wie na czym polega zabawa społecznościowa.



