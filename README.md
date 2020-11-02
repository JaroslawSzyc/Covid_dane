02.11.20r.

# Na Dolnym Śląsku (aktualne):

![](images/geo_1.png)



![](images/DS_total_cases.png)


![](images/DS_LJBZ_cases.png)

W wypadku Legnicy i Jeleniej Góry widzimy sumę diagnoz dodatnich z miasta i powiatu.

(Bolesławiec i Zgorzelec mają tylko powiat) 


# W Polsce (dane na wczoraj):

![](images/PL_total_cases.png)


![](images/PL_new_cases.png)

Aby lepiej zrozumieć tempo wzrostu dziennych zakażeń, zobaczmy jak to wygląda w skali logarytmicznej:

![](images/PL_new_cases_log.png)

Dostrzegamy tu od mniej więcej drugiego tygodnia września wyraźny trend liniowy. Oznacza to, że mamy do czynienia ze wzrostem wykładniczym.

Możemy dopasować funkcję do tych danych, aby lepiej zrozumieć to zjawisko. Dla przeskalowanych danych wyznaczymy prostą regresji metodą najmniejszych kwadratów. 

![](images/PL_regression.png)

Współczynnik R-kwadrat wynosi ok. 0.9776, zatem jest to dość dobrze dopasowany model.
