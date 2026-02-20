Pattern Cut Generator for FreeCAD (v0.9) 🇬🇧 / 🇵🇱

(Scroll down for Polish version / Polska wersja poniżej)
🇬🇧 English
Introduction

Pattern Cut Generator is a highly optimized FreeCAD macro designed to generate complex patterned cutouts on flat surfaces. Built for performance and usability, it bypasses the heavy calculations of the FreeCAD Sketcher by utilizing direct Constructive Solid Geometry (CSG) boolean operations.
Features

    5 Pattern Types: Hexagons (honeycomb), Circles, Diamonds, Slotted (horizontal/vertical), and Triangles.

    Extreme Performance: Uses Part.Compound and bulk common boolean operations to process hundreds of cutouts without melting your CPU.

    Real-time 3D Preview: Instantly see the pattern overlay on your selected face before generating the final cut.

    Bilingual UI: Fully translated interface (English and Polish) with dynamic switching and online flag icons.

    Persistent Settings: Automatically saves and loads your last used parameters (size, gap, border, depth) using FreeCAD's user parameters.

    Rock-solid Stability: Safe memory handling and background timer termination ensure FreeCAD remains stable (no Access Violation errors) after the macro is closed.

Installation

    Download the PaterrnGenerator_NEW.FCMacro file.

    Place it in your FreeCAD Macro directory (usually ~/.local/share/FreeCAD/Macro/ on Linux or C:\Users\YourUser\AppData\Roaming\FreeCAD\Macro\ on Windows).

    Open FreeCAD, go to Macro -> Macros..., select the file, and click Execute.

Usage

    Select a flat face in the 3D view.

    Run the macro.

    Click Get selected face.

    Adjust the Shape, Size, Gap, Border, and Depth parameters.

    Click GENERATE CUT and wait for the progress bar to finish.

🇵🇱 Polski
Wprowadzenie

Generator Wycięć Wzorów to wysoce zoptymalizowane makro do programu FreeCAD, służące do generowania złożonych wzorów na płaskich powierzchniach. Zaprojektowane z myślą o wydajności i komforcie użytkownika, omija ciężkie obliczenia środowiska Szkicownika (Sketcher), wykorzystując bezpośrednie operacje logiczne CSG na bryłach.
Główne cechy

    5 typów wzorów: Heksagony (plaster miodu), Okręgi, Romby, Fasolki (poziome/pionowe) oraz Trójkąty.

    Wysoka wydajność: Wykorzystuje obiekty Part.Compound oraz zbiorcze operacje logiczne (common), aby przetwarzać setki otworów bez zawieszania procesora.

    Podgląd 3D na żywo: Pozwala natychmiast zobaczyć nakładkę wzoru na wybranej ścianie przed wygenerowaniem ostatecznego cięcia.

    Dwujęzyczny interfejs: W pełni przetłumaczony interfejs (Polski i Angielski) z dynamicznym przełączaniem i ikonami flag.

    Zapisywanie ustawień: Automatycznie zapisuje i wczytuje ostatnio używane parametry (rozmiar, odstęp, ramka, głębokość) w rejestrze FreeCAD.

    Pancerna stabilność: Bezpieczne zarządzanie pamięcią i ubijanie timerów w tle gwarantuje, że FreeCAD pozostaje stabilny (brak błędów Access Violation) po zamknięciu makra.

Instalacja

    Pobierz plik PaterrnGenerator_NEW.FCMacro.

    Umieść go w swoim folderze Makr FreeCAD (zazwyczaj ~/.local/share/FreeCAD/Macro/ na Linux lub C:\Users\TwójUżytkownik\AppData\Roaming\FreeCAD\Macro\ na Windows).

    Otwórz FreeCAD, przejdź do Makro -> Makra..., wybierz plik z listy i kliknij Wykonaj.

Jak używać

    Zaznacz płaską ścianę w widoku 3D.

    Uruchom makro.

    Kliknij Pobierz zaznaczoną ścianę.

    Dostosuj parametry: Kształt, Rozmiar, Odstęp, Ramkę i Głębokość.

    Kliknij GENERUJ WYCIĘCIE i poczekaj na wypełnienie paska postępu.
