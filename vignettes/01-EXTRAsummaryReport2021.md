---
title: "Additional information and analysis"
#bibliography: references.bib
---

```{r}
knitr::include_graphics(here::here("images/iKoalaICON.png"))
```

# Report summaries in detail {#pastsums}

In the [2021 report](@sums) we have estimated the abundance of koalas across all five sites as well as site specific abundance for each of the study areas. The terminology and analyses performed within this report are consistent with earlier analysis [@Gruber2013; @Gruber2014; @Gruber2015] unless otherwise stated:

1. **[Monitoring design of sampling area and periods](\@ref(ref:mont))**: The first section of the report looks at the sampling design at each of the 5 sites during each of the 3 periods.

2. **Raw Occurrence data:** The raw observations of Koala presence determined by the presence of koala faecal pellets at a sampling sites overall and for each period.

3. **Occupancy model:** The previous (prior to 2020) Koala report fitted an occupancy model to the data by dividing the observed occupancy into the three groups and estimated koala abundance after accounting for detection issues. The 2021 report has updated this model to account for the processes effecting detection in a more ecologically meaningful way based off a Bayesian State-Space model that accounts for both the observation and process error associated with estimating Koala abundance.

4. **Previous analyses (ran for full dataset only)**: Two key aspects of previous reports have been included as additional information into the following aspects of this research data. These analyses have been done at the level of the whole dataset (by combining all sites (n = 5). Each individual analysis for further investigation can be generated from the `iKoala` application.
	- **Activity**: Activity was estimated as the proportion of trees with one or more koala faecal pellets at a sampling site for each of the three periods.
	- **Tree preferences**: Koalas are know to select certain tree species (referred to as 'strike rate') - defined as the probability for every period that a faecal pellet is found under a tree of a particular tree species.

Additional notes on the project structure can be found in the `./README.Rmd` file. *For more information on terminology, sampling methods and analysis, please, refer to the reports referred to above. These pdfs can also be found within the project folder `/_resources/pdfs/pastReports/`*.

```{r eval = FALSE}
list.files(here::here("./_resources/pdfs/"))
```

## Definition of terms

The terminology and analyses performed within this report are consistent with reports by [@Biolink2011; @Gruber2014a]. The terms include:

-   **Grid:** the area which is defined as a single replicated sampling area (n = 5).

-   **Site:** which are the locations at each point on the grid where the absence or presence of feacal pellets was collected.

-   **Period:** over the duration of our study (2007-2020) there are several periods of differing sample design and data collection. This grouping allows us to account for these differences throughout the study.

-   **Occurrence:** is determined by the presence or absence of koala faecal pellets at a sampling site for every period, at a selected number of locations.

-   **Active:** a *site??grid??* where at least one koala faecal pellet was found during a period.

-   **Activity level:**, which is the proportion of trees with one or more koala faecal pellets at sampling sites for every period.

-   **Strike rate:** which is the preference for certain tree species defined as the probability for every period that a faecal pellet is found under a tree of a specified tree species.