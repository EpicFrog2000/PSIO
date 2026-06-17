# Inicjalizacja projektu

Odpal se to w jupiterze

Tu masz przygotowanie środowiska jak robisz to na wsl:
```
https://github.com/EpicFrog2000/PSIO.git
cd PSIO
chmod +x setup.sh && ./setup.sh
source venv/bin/activate
code .
```

# TODO

## Wybór ćwiczenia
- [ ] We zdecyduj które ćwiczenia bedą najłatwiejsze i je tu napisz
  - Rozważmy zatem przykłady trudniejsze, mogą to być:
    - podnoszenie sztangi lub hantli
    - joga, tai-chi, karate i inne sztuki walki
    - gimnastyka artystyczna
    - tenis, siatkówka
    - rehabilitacja po operacji, wypadku, w stanach niedowładu.
  - podnoszenie sztangi lub hantli - reszta bez porównania pod względem trudności
  
- [ ] Zdefiniować błędy do wykrywania
  - 

## Setup
- [ ] Nagrać video Ćwiczeń i przekazać je do programu (teraz jest testowo video z kamerki z telefonie)
- [ ] Zrobić IO dzwiękowe do kontroli i informowania

## Computer Vision
- [ ] MediaPipe Pose – wykrywanie szkieletu
- [ ] YOLO v11 – detekcja obiektów (hantle, mata, etc.)
- [ ] Roboflow – dataset + trening własnego modelu
- [ ] Algorytmy kątów stawów (własne funkcje numpy)
- [ ] Fuzja obrazu z 2 nagrań video

## Logika trenera
- [ ] Liczenie powtórzeń
- [ ] Wykrywanie błędów pozy w czasie rzeczywistym
- [ ] Ocena serii po zakończeniu

## Interfejs głosowy
- [ ] `speech_recognition` – komendy głosowe od ćwiczącego
- [ ] `pygame` / TTS – feedback głosowy trenera
- [ ] Scenariusze dialogów (użycie poprawne i niepoprawne)

## UI (po/w trakcie serii)
- [ ] Playback nagrania z zaznaczonymi błędami
- [ ] Statystyki serii (powtórzenia, błędy, czas)

## Baza danych
- [ ] Zapis danych sesji do txt

## Testy
- [ ] Dokładność detekcji błędów

## Raport (artykuł naukowy)
- [ ] Abstrakt, wstęp, metodologia
- [ ] Opis algorytmów
- [ ] Wyniki testów
- [ ] Wnioski i ograniczenia    
