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

# Instrukcja użytkowania:

Komendy głosowe:
"start" → zeruje licznik, zaczyna nagrywać
"reset" → zeruje powtórzenia
"stop" → kończy, zapisuje sesję do sessions/

Ćwiczenie:
Stań w kadrze cały
Rób przysiady — kąt kolana < 90° = dobre powtórzenie
Na ekranie widać kąt, licznik, błędy

Po sesji:
sessions/session_YYYYMMDD_HHMMSS.mp4 — nagranie ze szkieletem
sessions/stats_YYYYMMDD_HHMMSS.json — błędy per powtórzenie

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
- [x] Zrobić IO dzwiękowe do kontroli i informowania

## Computer Vision
- [x] MediaPipe Pose – wykrywanie szkieletu
- [ ] YOLO v11 – detekcja obiektów (hantle, mata, etc.)
- [ ] Roboflow – dataset + trening własnego modelu
- [x] Algorytmy kątów stawów (własne funkcje numpy)
- [ ] Fuzja obrazu z 2 nagrań video

## Logika trenera
- [x] Liczenie powtórzeń
- [x] Wykrywanie błędów pozy w czasie rzeczywistym
- [ ] Ocena serii po zakończeniu

## Interfejs głosowy
- [x] `speech_recognition` – komendy głosowe od ćwiczącego
- [ ] `pygame` / TTS – feedback głosowy trenera
- [ ] Scenariusze dialogów (użycie poprawne i niepoprawne)

## UI (po/w trakcie serii)
- [ ] Playback nagrania z zaznaczonymi błędami
- [x] Statystyki serii (powtórzenia, błędy, czas)

## Baza danych
- [x] Zapis danych sesji do json

## Testy
- [ ] Dokładność detekcji błędów

## Raport (artykuł naukowy)
- [ ] Abstrakt, wstęp, metodologia
- [ ] Opis algorytmów
- [ ] Wyniki testów
- [ ] Wnioski i ograniczenia    
