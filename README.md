# Projekt_1
kodowanie makiety z figmy

Design projektu w aplikacji Figma znajdziesz pod tym adresem: https://www.figma.com/file/DGyuGsapuc5gGf5KMEEGG3/Projekt-zaliczeniowy-1

Czcionka, której używamy to Roboto i jest do znalezienia na portalu Google Fonts (https://fonts.google.com)

Ikony, z których będziesz korzystać znajdziesz w paczce FontAwesome (https://fontawesome.com/)

Przygotuj kontener o rozmiarze 960px (szerokość), który będzie zawsze na środku - to w nim umieszczaj treść

Pierwsza z sekcji powinna zajmować 100% wysokości okna przeglądarki (vh) 

Po najechaniu na przycisk na stronie głównej (z tłem), spraw, że jego tło stanie się białe, a tekst czarny (border pozostaje bez zmian). Zmiana powinna być płynna i trwać sekundę. Przycisk po kliknięciu powinien nas przenieść do sekcji “oferta”. transition;

Spraw aby przyciski w nawigacji “o nas” oraz “oferta” przenosiły użytkownika w odpowiednie miejsce na stronie przy zachowaniu płynnego scrolla. Przycisk “kontakt” powinien być “disabled” czyli nieaktywny (ustaw odpowiedni kursor). cursor: not-allowed

Zdjęcie w tle na stronie tytułowej może być dowolnym zdjęciem o rozmiarze maksymalnie 1920x1080 i wadze nieprzekraczającej 400 KB (możesz użyć Lorem Picsum). Pamiętaj, że musisz nałożyć na nie kolejnego diva, który je częściowo przykryje - będzie “cieniem”. Robi się to po to aby tekst na zdjęciu był bardziej czytelny (kontrast).

Zdjęcia “pracowników” powinny być zdjęciami przedstawiającymi osoby o rozmiarze maksymalnie 500x500. Twoim zadaniem jest ustawić je jako zdjęcie tła diva, który jest okrągły. Pamiętaj, że zdjęcie powinno dopasować się rozmiarem do diva oraz wycentrować w pionie i poziomie.

W zakładce “o nas” elementy z pracownikami powinny mieć wspólną klasę, ale mieć jeden modyfikator, który sprawia, że każdy nieparzysty zaczyna się zdjęciem z lewej, a każdy parzysty zdjęciem z prawej strony. nth-of-type(odd) / nth-of-type(even)

Paddingi we wszystkich sekcjach powinny być ujednolicone (górny i dolny powinny być takie same, a treść sekcji powinna zaczynać się i kończyć w tej samej linii).

W boksach, nieważne jaką ilość treści podamy, powinna być zawsze wyśrodkowana w pionie i poziomie.

Po najechaniu na boxy, spraw aby powiększyły się o 5% przy pomocy funkcji transform: scale(1.05). Spraw aby animacja była płynna i trwała pół sekundy
