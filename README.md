# Projekt-Dyplomowy

Precyzyjna i wydajna rekonstrukcja śladów cząstek naładowanych w zderzaczach protono-
wych jest niezwykle skomplikowanym problemem. System wyzwalania detektora LHCb prze-
twarza dane pochodzące z przecięcia wiązek protonowych, które zachodzą z częstotliwością
25 MHz. Typowy przypadek zawiera setki cząstek wtórnych oraz do 10 wierzchołków pier-
wotnych. Z uwagi na progam fizyczny eksperymentu system śladowy musi zapewnić wysoką
wydajność rekonstrukcji dla wszystkich typów produkowanych cząstek oraz dla szerokiego
zakresu pędów. Jednocześnie, system ten musi również zapewnić odpowiednia czystość re-
konstruowanych śladów poprzez możliwość dyskryminacji przypadkowych kombinacji hitów
(duchy).
Przy nominalnej świetlności zmodernizowany eksperyment LHCb będzie produkować oko-
ło 4 terabajtów danych na sekundę, podczas gdy tylko około 10 gigabajtów danych na sekundę
można zapisać na stałe w celu analizy fizycznej. Oznacza to, że LHCb potrzebuje sposobu,
aby zdecydować, które części surowych przypadków są najbardziej interesujące do analizy i
zapisać je, odrzucając resztę. Taki system jest powszechnie znany jako system wyzwalania
przypadku (z ang. trigger ). W 2021 roku zakończył się projekt modernizacji detektora LHCb,
który pracuje przy świetlności ok. pięć razy większej niż poprzedni detektor [1]
Częścią architektury trygera są serwery rekonstruujące ślady cząstek. Używają one se-
kwencji algorytmów zdolnych do filtrowania i klasyfikowania surowych danych z detektora.
Szybki rozwój sztucznej inteligencji w ostatnich latach pokazuje jaki potencjał może mieć
zastosowanie modeli uczenia maszynowego w implementacji systemów wyzwalania przypad-
ków. Ważnym etapem budowy tego typu modeli jest ich ewaluacja. W kontekście wyzwalacza
jest to porównanie działania ”klasycznych” algorytmów w stosunku do modeli opartych o ele-
menty sztucznej inteligencji
Niniejszy projekt dyplomowy koncentruje się na ewaluacji wytrenowanego modelu uczenia
maszynowego i oceny jakości rekonstrukcji śladów cząstek długożyciowych w detektorze
LHCb, ze szczególnym uwzględnieniem wpływu liczby wierzchołków pierwotnych na precyzję
tego procesu. Badania opisane w niniejszej pracy wykonano z użyciem próbek symulacyjnych
wyprodukowanych dla zmodernizowanego detektora LHCb przy nominalnych warunkach pra-
cy.
