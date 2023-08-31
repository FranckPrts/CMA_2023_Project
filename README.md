# Sea Level Rise and Extreme Weather Events Analysis

### Pod
Rajasaurus Baris, [CMA 2023](https://academy.climatematch.io/)

## Overview

This repository contains the code, data, and analysis for our CMA 2023 project. Here we aimed to investigate the relationship between sea level rise (SLR) and extreme weather events, particularly their impact on coastal communities. The project focuses on comparing sea level measurements from tidal gauges (TG) with data obtained from satellite-based models (ECCO) during severe storm events.

## Table of Contents

- [Scientific Background](#scientific-background)
- [Research Question](#research-question)
- [Hypotheses](#hypotheses)
- [Data Collection](#data-collection)
- [Data Analysis](#data-analysis)
- [Results](#results)
- [Future Work](#future-work)
- [Contributors](#contributors)

## Scientific Background

Sea level rise is a critical environmental issue that exacerbates the impact of storms on coastal communities. The high amplitude of sea level changes during storm events poses challenges for accurate measurement and representation by climate models. Tidal gauge (TG) data provides higher-resolution in-situ measurements of sea level fluctuations, which can be compared with satellite-based models like ECCO.

## Research Question

How does the resolution and reliability of sea surface height (SSH) data from ECCO compare to tidal gauge (TG) data during severe storm impact events?

## Hypotheses

- H0: There is no significant difference in resolution/reliability between SSH data and TG data during severe storm events.
- H1: There is a significant difference in resolution/reliability between SSH data and TG data during severe storm events, favoring TG data.

## Data Collection

The project focuses on analyzing specific severe storm events, including:

- Hurricane Sandy (October 2012)
- Hurricane Maria (September 2017)
- Typhoon Ketsana (September 2009)

For each event, TG data and ECCO SSH data were collected for various coastal locations. The data included sea level measurements and associated metadata.

## Data Analysis

The collected data underwent analysis to calculate Pearson's correlation between TG and ECCO SSH time series. We also considered Bland-Altman plots to evaluate the consistency and agreement between datasets.

## Results

The analysis yielded valuable insights:

- Strong correlation between TG and ECCO SSH data in some locations.
- Some TG data provided higher resolution and reliability during extreme weather events.
- ECCO data's lower resolution near the coast influenced the results.

| Event   | Location               | Pearons Statistic | Pvalue            | Min TG           | Max TG           | Min SAT          | Max SAT          | Percent_usable |
|---------|------------------------|-------------------|-------------------|------------------|------------------|------------------|------------------|----------------|
| Sandy   | Atlantic City, NJ     | -0.8307771964541347 | 0.001537424752063651 | -0.34474992752075195 | 0.7571251392364502 | -0.011457881579796492 | 0.011457881579796436 | 100.0 |
| Sandy   | The Battery, NY       | -0.7424619647484809 | 0.008869248556628137 | -0.4015833333333332 | 0.8669166666666668 | -0.014469226201375252 | 0.014469226201375363 | 100.0 |
| Sandy   | Montauk, NY           | -0.7531328301741064 | 0.0074559342297149805 | -0.3132878787878788 | 0.7259204545454547 | -0.01068242515126866 | 0.010682425151268604 | 100.0 |
| Maria   | Isabel Segunda, PR    | -0.4611116383274443 | 0.06246702286955319 | -0.09793877601623535 | 0.2222280502319336 | -0.001560370127359989 | 0.0015603701273600445 | 100.0 |
| Maria   | Esperanza, PR         | TOO SHORT         | TOO SHORT         |NO DATA|NO DATA| -0.001560370127359989 | 0.0015603701273600445 | 0.0 |
| Maria   | Arecibo, PR           | TOO SHORT         | TOO SHORT         |NO DATA|NO DATA| -0.0016681849956512451 | 0.0016681849956512451 | 0.0 |
| Maria   | Mayaguez, PR          | TOO SHORT         | TOO SHORT         |NO DATA|NO DATA| -0.0013145009676616137 | 0.0013145009676615027 | 0.0 |
| Maria   | Fajardo, PR           | 0.8002793342695729 | 0.10387470925223188 | -0.07427835464477539 | 0.2175273895263672 | -0.000390092531840025 | 0.0003900925318399695 | 100.0 |
| Ketsana | Malakal, Palau        | -0.47123345888475304 | 0.3454710918143166 | -0.25140976905822754 | 0.11129868030548096 | -0.0017577782273292542 | 0.0017577782273292542 | 100.0 |
| Ketsana | Legaspi, Philippines  | TOO SHORT         | TOO SHORT         |NO DATA|NO DATA| -0.0019367411732673645 | 0.0019367411732673645 | 0.0 |
| Ketsana | Manila, Philippines   | TOO SHORT         | TOO SHORT         | -0.11147904396057129 | 0.26039600372314453 |NO DATA|NO DATA| 0.0 |
| Ketsana | Subic Bay, Philippines | 0.6426570312975 | 0.16872571988471247 | -0.107208251953125 | 0.2514582872390747 | -0.0008405869205793115 | 0.0008405869205792005 | 100.0 |
| Ketsana | Qui Nhon, Vietnam     | 0.9491202756007416 | 0.0038172621818771666 | -0.20693743228912354 | 0.38843750953674316 | -0.0023103132843971252 | 0.0023103132843971252 | 100.0 |


## Future Work

The project opens avenues for further investigation:

- Explore additional storm events and locations.
- Incorporate more sophisticated statistical methods.
- Investigate the impact of SLR on storm intensity and frequency.

## Contributors

This project was a collaborative effort involving the following contributors:

**Pod members:**
- [Franck Porteous](https://github.com/FranckPrts)
- Hannah Krohn
- James Milward
- Faith Hunja
- Ayman khaled Attah-Allah
- Ruben Espeleta
- Aizat Salam
- Denisse Córdova Carrizales


**Pod TA:** Grant Parajuli<br>
**Project TA:** Gaby Mayorga Adame

____
thanks for reading!<br>
if you have any question you can [email Franck](mailto:franck.porteous@protonmail.com)