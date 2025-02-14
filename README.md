# Sales_MAG

Acest proiect are ca scop analiza datelor de vânzări pentru a obține informații despre tendințele de vânzări, cele mai populare produse, clienți și sezonalitate. Proiectul este realizat utilizând SQL, Excel și Tableau pentru a importa, curăța, analiza și vizualiza datele.

# __Structura Proiectului__
  
    SQL: Import și curățare date.
    Excel: Analiza datelor folosind tabele pivot și grafice.
    Tableau: Crearea de dashboard-uri interactive pentru vizualizarea datelor.

# __Datele Utilizate__

  Setul de date utilizat în acest proiect conține următoarele câmpuri:
```
order_id: ID-ul unic al fiecărei comenzi.
customer_id: ID-ul clientului care a efectuat comanda.
order_date: Data la care a fost plasată comanda.
product_name: Numele produsului.
category: Categoria produsului.
quantity: Cantitatea vândută.
price_per_unit: Prețul per unitate al produsului.
total_price: Prețul total pentru comanda respectivă.
```
# __Etapele Proiectului__
## 1. Importul și Curățarea Datelor (SQL)\
```
Datele sunt importate dintr-un fișier CSV într-o bază de date SQL.
Curățarea datelor a inclus:
Eliminarea comenzilor cu valori nule.
Înlăturarea comenzilor duplicate.
Crearea unei coloane profit_margin pentru a calcula marja de profit.
Întrebări SQL de analiză:
Total vânzări pe lună.
Cele mai vândute produse și categorii.
Clienți care au efectuat cele mai multe achiziții.
```
## 2. Analiza în Excel
```
Datele curățate din SQL au fost importate în Excel pentru analiză detaliată.
Tabele pivot create:
Vânzări pe lună și an.
Analiza sezonalității.
Performanța produselor și categoriilor.
```
### __Vizualizări:__
```
Bar chart pentru cele mai populare produse.
Line chart pentru tendințele vânzărilor în timp.
```
## 3. Vizualizare și Dashboard-uri în Tableau
Datele au fost importate în Tableau pentru crearea următoarelor dashboard-uri interactive:
```
Dashboard 1: Evoluția vânzărilor în timp
Vizualizare a vânzărilor lunare și anuale folosind un grafic de tip Line Chart.
Dashboard 2: Cele mai populare produse și categorii
Grafic de tip Bar Chart pentru identificarea produselor și categoriilor cu cele mai mari vânzări.
Dashboard 3: Distribuția vânzărilor pe regiuni (opțional)
Hartă interactivă pentru vizualizarea vânzărilor pe regiuni (dacă sunt disponibile datele).
```
# __Tehnologii Utilizate__
```
SQL pentru import, curățare și analiză de date.
Microsoft Excel pentru analiza datelor și crearea tabelelor pivot.
Tableau pentru crearea de dashboard-uri interactive.
```
# __Cum să Rulezi Proiectul__
```
Clonează acest repository.
Importă fișierul sales_data.csv într-o bază de date SQL.
Rulează scripturile SQL pentru curățarea și analiza datelor.
Importă datele curățate în Excel pentru a crea tabele pivot.
Folosește Tableau pentru a importa datele și a crea dashboard-uri interactive.
```
