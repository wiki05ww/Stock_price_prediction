**Stock Price Prediction with AI
Opis projektu**

Projekt przedstawia praktyczne zastosowanie sztucznej inteligencji oraz uczenia maszynowego w analizie trendów rynkowych i prognozowaniu cen akcji.

Celem projektu jest sprawdzenie, czy modele AI mogą skutecznie wspierać:

- analizę danych finansowych,
- identyfikację trendów,
- podejmowanie decyzji inwestycyjnych.

Analiza została przeprowadzona na rzeczywistych danych giełdowych (akcje Netflixa) oraz dodatkowych danych kontekstowych.

**Problem badawczy**

Czy metody sztucznej inteligencji są w stanie:

przewidywać przyszłe ceny akcji na podstawie danych historycznych?
wspierać inwestorów w interpretacji trendów rynkowych?

**Technologie i narzędzia**

W projekcie wykorzystano:

Python 
Pandas – analiza danych
NumPy – obliczenia numeryczne
Matplotlib – wizualizacja danych
Prophet – model prognozowania szeregów czasowych
Scikit-learn – metryki oceny modeli

**Dane**

Projekt bazuje na dwóch zbiorach danych:

- historyczne dane giełdowe Netflixa (ceny akcji, wolumen)
- dane dotyczące treści publikowanych na Netflixie
  
**Etapy projektu:**
1. Przygotowanie danych
- konwersja dat
- sortowanie danych
- usuwanie braków
- selekcja istotnych kolumn
2. Analiza eksploracyjna
- wizualizacja trendów cen akcji
- analiza zmian w czasie
3. Modelowanie
- zastosowanie modelu Prophet do prognozowania szeregów czasowych
- trenowanie modelu na danych historycznych
4. Ewaluacja
- ocena jakości prognoz przy użyciu:
- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
  
**Wykorzystanie AI generatywnej**

Projekt uwzględnia także wykorzystanie generatywnej AI do:

- interpretacji wyników modeli,
- tworzenia opisów analiz,
- tłumaczenia wyników na język zrozumiały dla osób nietechnicznych.
  
**Wyniki**

Model pozwala na:
przewidywanie przyszłych cen akcji,
identyfikację trendów wzrostowych i spadkowych,
wspieranie decyzji inwestycyjnych (w ograniczonym zakresie).

**Ograniczenia**
modele nie gwarantują trafnych prognoz,
rynek finansowy jest silnie zmienny i trudny do przewidzenia,
wyniki mają charakter edukacyjny, nie inwestycyjny.

**Jak uruchomić**
Sklonuj repozytorium:
https://github.com/wiki05ww/Stock_price_prediction.git

Zainstaluj wymagane biblioteki:
pip install pandas numpy matplotlib prophet scikit-learn

Uruchom notebook:
jupyter notebook

**Autor**

Projekt wykonany w ramach kursu Sztuczna Inteligencja.

**Licencja**

Projekt ma charakter edukacyjny.
