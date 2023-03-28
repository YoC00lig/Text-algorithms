<h1> Treść zadania </h1>
<a href="https://github.com/YoC00lig/Text-algorithms/blob/main/lab02/lab02.ipynb">Rozwiązanie zadania </a>
<p></p>
<p>Zadanie polega na implementacji dwóch algorytmów kompresji:</p>

<ol>
  <li>statycznego algorytmu Huffmana (2 p)</li>
  <li>dynamicznego algorytmu Huffmana (3 p)</li>
 </ol>
Dla każdego z algorytmów należy wykonać następujące zadania:

<ol>
  <li>Opracować format pliku przechowującego dane. Zwróć uwagę na dwie kwestie:
    <ol>
      <li>Liczba bitów wynikowego pliku nie musi być podzielna przez 8, ale z dysku zawsze odczytujemy pełne bajty, dlatego ważne jest, aby jakoś rozwiązać ten problem. W przeciwnym razie po dekompresji można uzyskać nadmiarowe dane.</li>
      <li>Plik wynikowy musi być binarny, tzn. rozwiązanie nie może zakładać, że w pliku tym zapisywane są 0 i 1 jako znaki ASCII.</li>
    </ol>
  </li>
  <li>Zaimplementować algorytm kompresji i dekompresji danych dla tego formatu pliku.</li>
  <li> Zmierzyć współczynnik kompresji (wyrażone w procentach: 1 - plik_skompresowany / plik_nieskompresowany) dla plików o rozmiarach: 1kB, 10kB, 100kB, 1MB, o różnej zawartości:
    <ol>
      <li>wybrany przez Ciebie plik tekstowy z projektu Gutenberg,</li>
      <li>wybrany przez Ciebie plik z kodem źródłowym jądra Linuksa,</li>
      <li>plik ze znakami losowanymi z rozkładu jednostajnego - należy uwzględnić wszystkie 256 wartości, a nie tylko znaki drukowalne.</li>
    </ol>  
  </li>
  <li>W sumie w punkcie 3 należy przeprowadzić analizę dla łącznie 12 plików (4 rozmiary x 3 typy plików).</li>
  <li>Zmierzyć czas kompresji i dekompresji dla plików z punktu 3.</li>
</ol>
