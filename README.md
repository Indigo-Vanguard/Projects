# There is no plan Bee without them 🐝

#### Disclaimer

Please consider consulting the file called [`bees.html`](bees.html) in order to see our entire work without having to run the notebook `bees.ipynb`. Additional plots for the milestone 3 have been appended at the end of the notebook.

[Our data story can be found here](https://indigo-vanguard.github.io/).

## Final abstract

Pollinators around the world play a central role in our agriculture with an estimated economic benefit of €235bn per year. Up to 75% of our crops are dependent on pollination and honey bees account for most of it. Yet, in Europe and the USA the bee population has been declining at an alarming rate during the last decades. [1]

With this project, we first look at the factors of bee population decline using surveys from the [US Departement of Agriculture](https://quickstats.nass.usda.gov/). Secondly, we try to identify where the bees are dying in the USA. This leads us to look at their impact on the economy, be it as pollinators or honey producers. We highlight the patterns in honey trade and production around the world and shed light on dirty honey tricks.

[[1](http://sos-bees.org/wp-content/uploads/2014/04/BeesInDecline.pdf)] *Bees in Decline*, Greenpeace, 2013


## Final research questions

- Can we find culprits for the Colony Collapse Disorder (CCD) cases in the US?
- Do some patterns appear as to where the bees die in the US?
- California accounts for 80% of the world almond production, what is the impact of bees on this industry in the 21st century?
- How to cluster countries based on their honey import/export around the world?
- Some countries appear to have hyper-productive beehives, how can we explain this phenomenon?

## Datasets

- [USDA NASS](https://quickstats.nass.usda.gov/)
    - Dataset of the US Department of Agriculture
    - Search criterions:
        - Sector: Animal & Products
        - Commodity: Honey
        - Data item: Honey, Bee colonies
        - Geographic Level: State (or National)
    - Available interesting datasets:
        - Inventory (number of colonies), county / state / national level
        - Losses, (CCD, deadout) from 2015-2019
        - Affected by (Varroa, pesticides)
    - Other interesting commodity: Almond
        - Area bearing/non-bearing
        - Price and yield
        - honey bee pollination
    - [Bee Colony Statistical Data from 1987-2017](https://data.world/finley/bee-colony-statistical-data-from-1987-2017)
        - Cleaned dataset from the USDA available on data world
        - USA Average loss per state per year (2010-2017)
          - Note: would still be interesting to use this one
        - USA Bee Colony survey data per state per year (1987-2017)
        - USA Bee Colony census per county per year (2002-2012)
- [FAO]( http://www.fao.org/faostat/en/#data )
    - Dataset of the UN Food and Agriculture Organization
    - [Live Stock FAO](http://www.fao.org/faostat/en/#data/QA)
        - Amount of beehives per country per year (1961-2017)
    - [Livestock Primary FAO](http://www.fao.org/faostat/en/#data/QL)
        - Amount of produced honey per country per year (1961-2017)
    - [Trade Matrix FAO](http://www.fao.org/faostat/en/#data/TM)
        - Import/Export honey quantities (tons) (and value ($)) for pairs of countries (1986-2017)


## Technologies
- [Beautiful Jekyll](https://deanattali.com/beautiful-jekyll/) : for the website
- [Plotly](https://plot.ly/): interactive web visualization library
- Leaflet.js: technology behind Folium

## Contributions

- Arthur Gassner: Introduction, Varroa/Pesticide plotting/analysis/discussion, US case study plotting/analysis/discussion, final text contributor, final presentation speaker
- Eric Jollès: Import/export map, analysis, plot and text of bees-ness chapter, merging of the notebooks, final text contributor, preparation of the final presentation
- Robin Mamié: Webmaster, plotting, analysis and discussion of the evolution of the number of beehives and honey productions in countries, comparison of their productivity, conclusion, final text contributor
- Timoté Vaucher: Updated proposal about honey, study case about almonds in California, part about honey adulteration, implementation of CSS / Js features, final text contributor