# Arcpy
Skrypty wykorzystujące bibliotekę arcpy służące do analiz przestrzennych i automatyzacji procesów związanych z wprowadzaniem danych.


W pliku APM1_MariaMank znajduje się implementacja analizy wielokryterialnej w celu znalezienia najbardziej optymalnej lokalizacji dla nowego hotelu w Świeradowie Zdroju. 

Można tam znaleźć także znaleźć wykorzystanie biblioteki sys w celu automatycznego zarządzania plikami w oprogramowaniu ArcGIS Pro. Algorytm wybiera potrzebne pliki z folderu z Bazą Danych Obiektów Topograficznych 10k (BDOT10k) dla wybranego powiatu, przycina je do odpowiedniego obszaru na podstawie również zawartej w tym folderze warstwy z granicami administracyjnymiwybierania, nastepnie wyrzuca niepotrzebne pliki i dokonuje dalszych analiz na podstawie otrzymanych warstw.


W drugim pliku (nawigacja.ipynb) znajdują sie róznorakie funkcje wykorzystywane do zarządzania i edycji danych w projekcie z bazą danych zawierającą wnętrza budynków (posegregowane według pięter) oraz grady nawigacyjne do nawigacji po tych budynkach. Funkcje zarówno wykorzystują istniejące narzędzia w oprogramowaniu ArcGIS, ale także kursory (do edycji tabel atrybutów i geometrii obiektów). Zarówno tworzą nowe obekty, jak i uzupełniają tabele atrybutów na podstawie relacji przestrzennych między obiektami.
