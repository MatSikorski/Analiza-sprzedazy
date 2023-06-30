# Analiza sprzedaży

&emsp;Projekt zawiera analizę sprzedaży poszczególnych produktów w środowisku Jupyter Notebook w Pythonie przy pomocy narzędzia Pandas oraz Matplotlib.

# Informacje ogólne

&emsp;Przeprowadzona analiza zawiera odpowiedzi na następujące pytania:
- Jaki był najlepszy miesiąc w sprzedaży? Ile zarabiono w tym miesiącu?
- W którym mieście była największa sprzedaż?
- O której godzinie najlepiej wyświetlać reklamy? Jak to wygląda w różnych miastach?
- Jakie produkty są najczęściej sprzedawane razem?
- Jaki produkt sprzedawał się najlepiej? Z czego to może wynikać?

# Dane oraz ich analiza

&emsp;Pobrałem dane zawierające sprzedaż w poszczególnych miesiącach 2019 roku. Przed analizą przedstawiłem poszczególne pliki csv w jednym zbiorze danych:
```bash
  all_months.csv
```
 zawierającego kolumny: `Order ID`, `Product`, `Quantity Ordered`, `Price Each`, `Order Date`, `Purchase Address`
####
####

&emsp;Począwszy od oczyszczenia danych, przechodząc przez kolejne etapy ich analizy, ostatecznie uzyskałem zbiór danych:
```bash
  all_data.csv
```
który był rozszerzeniem wcześniejszego zbioru o następujące kolumny: `Month`, `Sales`, `City`, `Hour`, `Minute`
## Źródła danych

 - [Sales Product Data](https://www.kaggle.com/datasets/knightbearr/sales-product-data)
