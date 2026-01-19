## Model Lotki-Volterry z ograniczoną pojemnością środowiska

W tym repozytorium znajduje się projekt badający dynamikę układu drapieżnik-ofiara. W przeciwieństwie do klasycznego modelu, uwzględniliśmy tutaj ograniczoną pojemność środowiska dla ofiar (wzrost logistyczny), co czyni symulację znacznie bliższą rzeczywistym warunkom biologicznym.

Projekt został zrealizowany wspólnie przez: Jana Kocierza, Karola Strzępka i Michała Lomparta.

📂 Co tutaj znajdziesz?

**(model LV_pres.pdf)** – Nasz referat/prezentacja.

Zawiera pełen opis matematyczny modelu (układ równań różniczkowych).

Analizujemy w nim stabilność punktów równowagi.

Wyjaśniamy biologiczne implikacje, np. dlaczego drapieżniki nie zjadają wszystkich ofiar i jak środowisko ogranicza populację.


**(lotka_volterra.ipynb)** – Notatnik Jupyter z symulacjami.

Napisany w Pythonie przy użyciu scipy.integrate oraz matplotlib.

Rozwiązuje numerycznie układ równań.

Generuje portrety fazowe oraz animacje, które pokazują, jak zmienia się liczebność obu populacji w czasie.

 Jak uruchomić symulację?
Kod znajduje się w notatniku Jupyter (.ipynb). Aby go uruchomić, potrzebujesz Pythona z kilkoma podstawowymi bibliotekami do obliczeń naukowych.

Autorzy: Jan Kocierz, Karol Strzępek, Michał Lompart Projekt realizowany w ramach przedmiotu Równania Różniczkowe na Politechnice Krakowskiej.
