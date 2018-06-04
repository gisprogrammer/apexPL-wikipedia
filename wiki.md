{{Oprogramowanie infobox
 | nazwa               = Oracle Application Express
 | rodzaj              = [[Baza danych|Bazy Danych]]
 | logo                = 
 | grafika             = APEX 18.1.png
 | opis grafiki        = Oracle APEX 18.1 – narzędzie tworzenia aplikacj
 | autor               = [[Oracle Corporation|Oracle]]
 | platforma sprzętowa = 
 | system operacyjny   = [[Microsoft Windows]], [[Linux]],[[Oracle Solaris on SPARC (64 bit)]],[[Oracle Solaris x86-64 (64 bit)]],[[HP-UX Itanium]]
 | język programowania = [[PL/SQL]], [[SQL]], [[JavaScript]]
 | pierwsze wydanie    = 
 | wersja stabilna     = 18.1.0.00.45/ {{Data wydania|2018|05|24}}
 | licencja            = Oracle Technical Network License
 | wikibooks           = 
 | commons             = 
 | www                 = http://apex.oracle.com
}}
'''Oracle Application Express''' (Oracle APEX, w poprzednich wersjach Oracle HTML-DB) – udostępniane przez firmę [[Oracle Corporation|Oracle]] darmowe środowisko do tworzenia [[Aplikacja internetowa|aplikacji internetowych]] w oparciu o [[baza danych|bazę danych]] Oracle począwszy od wersji 9.2. Środowisko dostępne jest bezpłatnie w ramach [[Licencja oprogramowania|licencji]] bazy danych Oracle.

Dzięki wykorzystaniu Oracle APEX możliwe jest tworzenie aplikacji internetowych bez znajomości języków [[HTML]], [[JavaScript]] oraz [[język programowania|języków]] i [[framework]]ów powszechnie wykorzystywanych do programowania logiki programu ([[PHP]], [[Java Platform, Enterprise Edition|Java EE]], [[.NET]], itp.). Application Express instalowany jest na bazie danych Oracle (także darmowej Oracle XE) zapewniając automatyczne połączenie pomiędzy aplikacją i bazą. Aplikacje publikowane są na wbudowanym w bazę [[serwer aplikacji|serwerze]] [[Apache HTTP Server|Apache]] lub serwerze użytkownika (oficjalnie wspierane są [[Oracle WebLogic|Weblogic]], [[Apache Tomcat|Tomcat]] i [[GlassFish|Glassfish]]) z zainstalowanym komponentem [[Oracle REST Database Services]].

APEX oferuje zbiór gotowych komponentów do budowy strony WWW, możliwość zmiany wyglądu poprzez specjalnie przygotowane szablony (podobne w działaniu do tzw. skórek) oraz narzędzia do pobierania, dodawania i modyfikacji danych z bazy bez znajomości języka [[SQL]]. Pozwala na kontrolę autoryzacji użytkowników na wielu poziomach aplikacji. Cały proces tworzenia aplikacji może przebiegać bez konieczności pisania kodu. Zaawansowani programiści mają możliwość pisania skryptów (JavaScript), procedur [[PL/SQL]] oraz integracji tworzonych aplikacji z zewnętrznymi źródłami (np. biblioteki JS, [[usługa sieciowa|usługi sieciowe]], serwery druku) bez ingerencji w kod samego APEXa.

APEX może być zainstalowany na każdej platformie współpracującej z bazą danych Oracle. Jednakże tworzenie i używanie aplikacji odbywa się przez [[Przeglądarka internetowa|przeglądarkę WWW]] i jest całkowicie niezależne platformowo.

Wadą APEX-a jest zamknięty kod, trudności z tworzeniem własnych szablonów wyglądu oraz niedostatecznie rozbudowany proces wykrywania błędów ([[Debugowanie|debugging]]) i brak [[System kontroli wersji|narzędzia kontroli wersji]].

Wersja (5.0) została rozbudowana m.in o nowy Page Designer, ulepszone interaktywne oraz mobilne raportowanie, obsługę deklaratywną okien modalnych i szablony wyglądu zgodne z [[HTML5]] i [[Responsive web design|Responsive Web Design]].

Wraz z nową wersją (5.2) została zmieniona numeracja na 18.1, oznaczającą rok i numer kwartału wydania. Zmiana ta związana jest z nową nomenklaturą numeracji Oracle.


##App Builder
Główne narzędzie do wizualnego tworzenia, rozwoju, monitorowania użycia i publikacji aplikacji. Poza utworzeniem czystej aplikacji, możliwe jest także przygotowanie gotowej aplikacji zawierającej szereg najczęściej wykorzystywanych funkcjonalności za pomocą wbudowanego kreatora (blueprint). Możliwe jest również skorzystanie z kreatora tworzącego aplikację na podstawie istniejących danych zawartych w plikach csv lub xls.

##SQL Workshop
Klient SQL umożliwiający wszelkie operacje na danych zawartych w bazie, tworzenie i modyfikację struktur danych, oraz programowanie w języku pl/sql.

##Quick SQL
Generator kodu SQl, oraz pl/sql umożliwiający szybkie tworzenie struktur danych, oraz obsługujących je API zgodnie z zasadami najlepszych praktyk programistycznych.

##RESTful Service
Wizualny interfejs do konfigurowania web-serwisów RESTowych umożliwiających udostępnianie danych poprzez sieć.

##TeamDevelopment
Zestaw wbudowanych narzędzi umozliwiających zarządzanie rozwojem aplikacji, pracą programistów, śledzeniem błędów i kamieni milowych. Użytkownicy aplikacji mogą również przekazywać w czasie rzeczywistym informacje zwrotne, które następnie można zakwalifikować do czynności do zrobienia, błędów lub funkcji.

##Packaged Apps
Zestaw bezpłatych aplikacji gotowych do instalacji i bezpłatnego użytku. Wśród nich znajdują się aplikacje demonstracyjne, pokazujące możliwości środowiska APEX oraz pełnoprawne aplikacje biznesowe, które z powodzeniem mogą zostać wykorzystane w firmie.

== Linki zewnętrzne ==
* [http://apex.oracle.com Strona domowa Oracle Application Express] {{lang|en}}
* [http://apex.world Strona społeczności Oracle APEX na świecie] {{lang|en}}
* [http://translate-apex.com Strona społeczności Oracle APEX zawierająca tłumaczenia na inne języki (w tym j. polski)] {{lang|en}}
* [http://forumapex.dbe.pl Polskie forum Oracle APEX] {{lang|pl}}

[[Kategoria:Systemy baz danych]]
[[Kategoria:Narzędzia wspomagające tworzenie oprogramowania]]
