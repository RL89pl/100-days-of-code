# 100 Days Of Code - Log

### Dzień 0: 29 Czerwca, Sobota 


**Dzisiejszy Progres:** Dołączenie do wyzwania i przygotowanie listy projektów, którymi będę się chciał zająć.

**Przemyślenia:** Projekty i zadania do nich najlepiej będzie, gdy wprowadzę do Todoist/Trello.

**Linki:** [100daysofcode](https://www.100daysofcode.com/)


### Dzień 1: 30 Czerwca, Niedziela


**Dzisiejszy Progres:** 
1. Napisałem skrypt na Raspberry Pi w celu monitorowania, czy został podłączony Pendrive USB i dokonania testu prędkości.
2. Napisałem skrypt do obracania etykiet UPS potrzebne do wydruku
3. Rozpocząłem pracę nad automatycznym czyścicielem do Raspberry Pi. Skrypt sprawdza skrzynkę mailową w poszukiwaniu wiadomości od konkretnego nadawcy z ustalonym tematem i tekstem w wiadomości. Gdy takowego odnajdzie, uruchamia proces wysyłki folderu na serwer FTP, następnie kasuje folder wraz z całym skryptem. Ostatecznie kasuje wiadomość email i wysyła potwierdzenie wykonania operacji SMSem. 

**Przemyślenia:** By móc skasować cały folder ze skryptem, najlepszym rozwiązaniem będzie trzymanie rozruchowego skryptu w innym miejscu, który uruchamiany będzie cronem co 5 minut. 

**Linki:**
1. [Tester USB](https://github.com/RL89pl/usb_test)
2. [Etykiety](https://github.com/RL89pl/labels_rotate)


### Dzień 2: 01 Lipca, Poniedziałek


**Dzisiejszy Progres:** 
1. Generator haseł
2. Skrypt do automatycznego tworzenia adresów email dla 5000 utworzonych danych (imię, nazwisko, hasło, nazwa konta email)

**Przemyślenia:** Captcha aktywuje się po kilku próbach, a po kilkunastu następuje tymczasowa blokada na IP. Potrzeba zmiennego IP, lub kilku serwisów


### Dzień 3: 02 Lipca, Wtorek

**Dzisiejszy Progres:** Modyfikacja skryptu do wysyłania zaawansowanych emaili

**Przemyślenia:** Pyautogui ułatwia pracę, gdzie Selenium zawodzi