# AttendanceApp

## Scénář
Mobilní nativní aplikace pro iOS umožňuje zaznamenat příchod a odchod zaměstnance. Uživatel se ověří jménem a heslem a následně zaznamená svůj příchod nebo odchod. Po přihlášení může uživatel vidět seznam svých příchodů a odchodů. Administrátor může registrovat nového uživatele a vidět seznam všech uživatelů.

## Technologie
iOS, SwiftUI, Swift, Firebase Realtime Database

## Plán
1. Project setup, vytvoření administrátorké obrazovky pro registraci nového uživatele
2. Dokončení administrátorké obrazovky pro registraci nového uživatele, vytvoření obrazovky pro přihlášení uživatele
3. DB návrh, napojení na Firebase DB
4. Napojení registrace nového uživatele na DB, napojení přihlášení uživatele
5. Dokončení napojení přihlášení uživatele, vytvoření obrazovky pro zaznamenání odchodu a příchodu
6. Dokončení obrazovky pro zaznamenání odchodu a příchodu, napojení obrazovky na DB
7. Vytvoření seznamu příchodů a odchodů pro konkrétního uživatele
8. Vytvoření seznamu příchodů a odchodů pro konkrétního uživatele
9. Vytvoření přehledu všech uživatelů pro administrátora
10. Základní UI testy

## 22.3. Check
Vývoj jde oproti plánu pomaleji. Prvních 6 bodů je splněno až na napojení registrace uživatele do navigace v aplikaci. Pro registraci uživatele je vytvořen formulář a logika ale aktuálně se v aplikaci nelze zaregistrovat(uživatel se nedokliká do registrace). Pro splnění plánu bude potřeba odstranit z plánu bod 9. a 10.

## Závěr
Jako technologii pro projekt jsem si zvolil SwiftUI, ve kterém jsem doposud neměl žádné zkušenosti. Při začátku práce na projektu jsem se zasekl na při vytváření rozhraní pro přihlášení uživatele. Důvodem byla nezkušenost se SwiftUI a odlišnými principy oproti UIKit. Zde je ponaučení plánovat větší časové nároky pro práci v technologii kterou neznám. Další zaseknutí bylo při napojení na Firebase, se kterým jsem také neměl zkušenosti, zde je stejné ponaučení jako u předchozího problému.
Po těchto zmíněných problémech jsem odstranil z plánu bod 9 a 10 tak, abych alespoň dokončil základní část aplikace. Body 9 a 10 nejsou pro aplikaci v této fázi příliš klíčové. Zbylé body z plánu byly splněny. Sedmý bod - Vytvoření seznamu příchodů a odchodů pro konkrétního uživatele byl naopak méně náročný než jsem původně očekával. V tomto bodu byla práce velmi urychlená díky funkčnosti SwiftUI při práci s tabulkami. V projektu jsem se snažil vyzkoušet si práci s architekturou MVVM, čím byla práce také časově náročnější. Zajímavou zkušeností při práci s projektem byla spolupráce/konzultace s Kristýnou, které dělala uživatelské testování, kdy přinesla zajímavé poznatky k aplikaci, které bych jako vyvíjející vývojář neviděl. Na závěr ve zbylém času jsem si vyzkoušel základní práci s UI testy. Zde jsem ale měl problém s funkčností Xcode. 

