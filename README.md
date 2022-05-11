# WarStar
PROJEKT: GRA SIECIOWA- STATKI W PRZESTRZENI KOSMICZNEJ


Celem projektu jest napisanie gry dwuwymiarowej-sieciowej (multiplayer), zręcznościowej w uniwersum Sci-Fi- biblioteka SFML.


    1. Założenia:
    • Funkcjonalne połączenie z serwerem. 
    • Przyjmowanie połączenia od klientów.
    • Analizowanie ruchów kolizji oraz trafienia- cała rozgrywka będzie się toczyła na serwerze.
    • Gra będzie zawierała informacje o wszystkich graczach, wyposażeniu graczy, głazach czyli obiektach od których nasze pociski się niszczą, natomiast statki się odbijają.
    • Implementacja systemów dźwięku np. przy kolizji statku z głazem.
    • Autorskie grafiki statków.
    • 
    2. Mechanika gry
    • Losowo wystrzelony pocisk leczy przeciwnika
    • Losowo wystrzelony pocisk zadaje większa ilość obrażeń przeciwnikowi
    • Ilość pocisków jest ograniczona oraz posiada czas odnowienia 
    • Pociski, które odbijają się od głazów ulegają zniszczeniu, natomiast pociski które odbijają się od krawędzi planszy nadal w niej pozostają
    • Pocisk doznaję przyspieszenia jeżeli użytkownik jest na przyspieszeniu
    • Działko z pociskami można obracać i strzelać w 4 cztery strony 
    • Możliwość gry multiplayer

    3. Grafika i dzwięki
    • Dwa rodzaje tekstur i animacji dla statków
    • Wizualne różnice między pociskami o różnych dziłaniach
    • Dzwięki strzału, obrotu działka, braku naboi, uleczenia, kolizji, zadania obrażeń przeciwnikowi!
    [graf](https://user-images.githubusercontent.com/87263429/167850514-52b8417c-74e2-4135-bd6d-29dfe1e02d0b.png)
    
![graf2](https://user-images.githubusercontent.com/87263429/167850639-27ba9ca4-843a-47a2-9be4-6175180c7ccc.png)
