18.11.20r.

# Na Dolnym Śląsku:

![](images/top10.png)

![](images/geo_2.png)

![](images/DS_WJL_cases.png)

![](images/DS_LJBZ_cases.png)

W wypadku Legnicy i Jeleniej Góry widzimy sumę diagnoz dodatnich z miasta i powiatu.

(Bolesławiec i Zgorzelec mają tylko powiat) 

![](images/DS_total_cases.png)

# W Polsce:

Dane do wczoraj.

![](images/PL_total_cases.png)


![](images/PL_new_cases.png)

Aby lepiej zrozumieć tempo wzrostu dziennych zakażeń, zobaczmy jak to wygląda w skali logarytmicznej:

![](images/PL_new_cases_log.png)

Dostrzegamy tu od ok. 2. tygodnia września do 1. tygodnia listopada wyraźny trend liniowy. Oznacza to, że mamy do czynienia ze wzrostem wykładniczym.

Możemy dopasować funkcję do tych danych, aby lepiej zrozumieć to zjawisko. Dla przeskalowanych danych wyznaczymy prostą regresji metodą najmniejszych kwadratów. 

![](images/PL_regression.png)

Współczynnik R-kwadrat wynosi ok. 0.979, zatem jest to dość dobrze dopasowany model.

Obecnie, według powyższych danych wynika, że przeszliśmy do trendu liniowego, ale należy mieć na uwadze, że od początku listopada ogłoszono zmiany w wytycznych dotyczących robienia testów. 

![](images/PL_positive.png)

Tutaj widzimy ile procent wykonywanych testów ma wynik dodatni. Czerwoną linią wskazany jest poziom 5%, który w maju WHO uznało za 'zbyt wysoki', aby zacząć łagodzić zastosowane restrykcje sanitarne. Więcej informacji w artykule: 

[www.jhsph.edu/covid-19/articles/covid-19-testing-understanding-the-percent-positive.html](https://www.jhsph.edu/covid-19/articles/covid-19-testing-understanding-the-percent-positive.html)


![](images/PL_total_deaths.png)



Źródła danych:

[www.duw.pl/pl/dla-mediow/aktualnosci-covid-19](https://www.duw.pl/pl/dla-mediow/aktualnosci-covid-19)

[ourworldindata.org/coronavirus](https://ourworldindata.org/coronavirus/country/poland?country=~POL)

