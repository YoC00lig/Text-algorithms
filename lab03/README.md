<h1> Treść zadania </h1>
<a href="https://github.com/YoC00lig/Text-algorithms/blob/main/lab03/lab03.ipynb">Rozwiązanie zadania </a>
<p></p>
<p>Zadanie dotyczy wykorzystania odległości edycyjnej:</p>

<ol>
<li>Zaimplementuj algorytm obliczania odległości edycyjnej w taki sposób, aby możliwe było określenie przynajmniej jednej sekwencji edycji (dodanie, usunięcie, zmiana znaku), która pozwala w minimalnej liczbie kroków, przekształcić jeden łańcuch w drugi.</li>
<li>Na podstawie poprzedniego punktu zaimplementuj prostą wizualizację działania algorytmu, poprzez wskazanie kolejnych wersji pierwszego łańcucha, w których dokonywana jest określona zmiana. "Wizualizacja" może działać w trybie tekstowym. Np. zmiana łańcuch "los" w "kloc" może być zrealizowana następująco:
<ol>
<li>*k*los (dodanie litery k)</li>
<li>klo*c* (zamiana s->c)</li>
</ol>
</li>

<li>Przedstaw wynik działania algorytmu z p. 2 dla następujących par łańcuchów:
<ol>
<li>los - kloc</li>
<li>Łódź - Lodz</li>
<li>kwintesencja - quintessence</li>
<li>ATGAATCTTACCGCCTCG - ATGAGGCTCTGGCCCCTG</li>
</ol>
</li>

<li>Zaimplementuj algorytm obliczania najdłuższego wspólnego podciągu dla pary ciągów elementów.</li>
<li>Korzystając z gotowego tokenizera (np spaCy - <a href="https://spacy.io/api/tokenizer">https://spacy.io/api/tokenizer)</a> dokonaj podziału załączonego tekstu na tokeny.</li>
<li>Stwórz 2 wersje załączonego tekstu, w których usunięto 3% losowych tokenów.</li>
<li>Oblicz długość najdłuższego podciągu wspólnych tokenów dla tych tekstów. Traktujemy teraz token (wyraz) jako podstawową, niepodzielną jednostkę ciągu.</li>
<li>Korzystając z algorytmu z punktu 4 skonstruuj narzędzie, o działaniu podobnym do narzędzia diff, tzn. wskazującego w dwóch plikach linie, które się różnią. Na wyjściu narzędzia powinny znaleźć się elementy, które nie należą do najdłuższego wspólnego podciągu. Należy wskazać skąd dana linia pochodzi (< > - pierwszy/drugi plik) oraz numer linii w danym pliku. Traktujemy teraz całą linię jako podstawową, niepodzielną jednostkę ciągu.</li>
<li>Przedstaw wynik działania narzędzia na tekstach z punktu 6. Zwróć uwagę na dodanie znaków przejścia do nowej linii, które są usuwane w trakcie tokenizacji.</li>
</ol>