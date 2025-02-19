
# Topologie Sieci

## Sieci Fizyczne
Sieci fizyczne odnoszą się do fizycznego ułożenia kabli, urządzeń i połączeń. Przykłady:
- **Topologia magistrali** (Bus) : jest to jedna z topologii fizycznych sieci komputerowych charakteryzująca się tym, że wszystkie elementy sieci są podłączone do jednej magistrali. 
  - Wady:  minimalna odporność na awarie, lokalizacja usterek jest trudna, tylko jedna możliwa transmisja w danym momencie
  - Zalety: małe użycie kabla, brak dodatkowych urządzeń, małe koszty produkcji
  - Gdzie stosowane: głównie stosowana w przypadku prostego ich rozmieszczenia – niewielkie biura lub sale wykładowe 
- **Topologia pierścienia** (Ring): jest to jedna z fizycznych topologii sieci komputerowych.
  - Wady: złożona diagnostyka sieci, trudna lokalizacja uszkodzenia, pracochłonna rekonfiguracja sieci
  - Zalety: możliwość zastosowania łącz optoelektronicznych, które wymagają bezpośredniego nadawania i odbierania transmitowanych sygnałów, małe zużycie przewodów
  - Gdzie stosowane:  w sieciach komputerowych, gdzie każde urządzenie jest połączone z dwoma sąsiednimi urządzeniami, tworząc zamknięty pierścień
- **Topologia gwiazdy** (Star): jest to sposób połączenia urządzeń w sieci komputerowej charakteryzujący się tym, że kable sieciowe od wszystkich urządzeń końcowych zbiegają się w jednym wspólnym punkcie
  - Wady: ograniczona liczba komputerów
  - Zalety: wysoka przepustowość, wydajność, łatwa lokalizacja uszkodzeń ze względu na centralne sterowanie
  - Gdzie stosowane: W średnich i dużych sieciach lokalnych, w których pracuje wiele urządzeń 


## Sieci Logiczne
Sieci logiczne opisują sposób przesyłania danych między urządzeniami, niezależnie od fizycznej struktury. Przykłady:
- **Punkt-punkt** (Point-to-Point): jest to  protokół komunikacyjny warstwy łącza danych
  - Wady: Słabe metody uwierzytelniania, Wymaga funkcji PPTP Passthrough w routerze
  - Zalety: Łatwa konfiguracja, Kompatybilność z Windowsem
  - Zastosowanie: używany przy bezpośrednich połączeniach pomiędzy dwoma węzłami sieci
- **Przekazywanie żetonu** (Token Passing): jest to jedna z deterministycznych metod dostępu do łącza danych
  - Wady: przerwanie medium lub awaria jednego z komputerów powoduje przerwę w działaniu całej sieci
  - Zalety: zapobiega kolizjom, zapewnia równy dostęp do medium transmisyjnego dla wszystkich urządzeń
  - Zastosowanie: wykorzystuje charakterystyczną sekwencję znaków jako symbol (token), który jest przekazywany z węzła do węzła, wskazując, kiedy rozpocząć transmisję
- **Wielodostępowa** (Multiple Access): jest to system współdzielenia medium poprzez przydział odpowiednich częstotliwości. 
  - Wady: trudności związane ze stabilnością częstotliwości nośnej, wykorzystanie kosztownych filtrów o stromych zboczach do separacji częstotliwościowej użytkowników.
  - Zalety: obsługuje różne typy sygnałów i użytkowników
  - Zastosowanie: stosowany był w pierwszych generacjach analogowych telefonów komórkowych. Znajduje zastosowanie raczej wśród systemów szerokopasmowych.
