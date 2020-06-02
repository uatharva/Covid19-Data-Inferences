# Covid19-Data-Inferences
A detailed parametric and non-parametriic inferences used on COVID19 dataset along with AirNow dataset for Massachusetts.

Findings for Task1 and Task2
1) I have covid data of several states from that I narrowed down to few counties of MA states. These counties were selected based on number of cases and deaths which were all close to easy coast and have high population densities.

The data was in the form of counties as row and date as columns, giving numbers on the present day (not new). So I transponsed the dataframe and dropped unnecessary columns which we don't use. I then converted data to new data form, so each day will have number of new cases. Because in initial days I didn't have good numbers, so I used data starting from 1st March.

2) Graph findings:
I see that there is a high fluctuations in number of cases and deaths over the time till May for all the counties. Few counties such as Barnstable where population density is low comparatively, I see lesser numbers. Same thing I verified it from cumulative distribution. About outliers, I saw high number of outliers from last days so I adjusted the critical value and got few outliers which I detected and removed on county basis.
