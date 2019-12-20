# There is no plan Bee without them 🐝

#### Disclaimer

Please consider consulting the file called [`bees.html`](bees.html) in order to see our entire work without having to run the notebook `bees.ipynb`.

[Our data story can be found here](https://indigo-vanguard.github.io/).

## Abstract

Pollinators around the world play a central role in our agriculture with an estimated economic benefit of €235bn per year. Up to 75% of our crops are dependent on pollination and honey bees account for most of it. Yet, in Europe and the USA the bee population has been declining at an alarming rate during the last decades. As hand-pollination is currently not an alternative, it is hard to imagine a world without them. [1]

With this project, we first aim at giving insights about the state of the population of bees, as well as the honey produced and traded using the [FAO datasets](http://www.fao.org/faostat/en/#data). Secondly, we focus on the USA using surveys from the [US Departement of Agriculture](https://quickstats.nass.usda.gov/) in order to identify and present the main factors of bee decline. Finally, we propose a case study about almonds in California to showcase the essential role of honey bees in our agriculture.

[[1](http://sos-bees.org/wp-content/uploads/2014/04/BeesInDecline.pdf)] *Bees in Decline*, Greenpeace, 2013


## Research questions

- How do the continents compare in terms of bee decline from 1961 to these days?
- How do changes in honey production relate to number of beehives in Europe and the USA?
- What are the consequences of bee decline on the patterns of honey import/export around the world?
- What is the relation between US cases of Colony Collapse Disorder and the main factors of CCD?
- California accounts for 80% of the world almond production, what is the impact of bees on this industry in the 21st century?

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


## Resources

- [Colony Collapse Disorder](https://en.wikipedia.org/wiki/Colony_collapse_disorder) Main factors:
    - Varroa
        - APHIS report [visualization](https://bip2.beeinformed.org/state_reports/)
            - data can be found [here](https://quickstats.nass.usda.gov/)
        - [EPFL: AI to save the bees](https://actu.epfl.ch/news/de-l-intelligence-artificielle-pour-sauver-les-abe/)
    - Pesticide
        - Neonicotinoids 
        - Imidacloprid, thiamethoxam, clothianidin, fipronil, chlorpyriphos, cypermethrin and deltamethrin. (Greenpeace, *Bees in decline*, p. 7)
    - Supposed factors: Climate change, EM fields, Stress during migratory beekeeping
- [Information website Bee Informed](https://bip2.beeinformed.org/)
    - Multiple data visualization of USA datasets
- [Honey Bee research association COLOSS](https://coloss.org/)
    - [Guidelines](https://coloss.org/statistical-guidelines-for-apis-mellifera-research/): research about bees
    - Lots of pdf reports with some data that we could scrap about EU / CH data 
- [SOS-bee (Greenpeace)](http://sos-bees.org/)
    - Situation, causes and solution to solve the bee problem
    - Report *Bees in decline* [pdf](http://sos-bees.org/wp-content/uploads/2014/04/BeesInDecline.pdf) (48 pages but you just need to read the executive summary)


## Technologies
- [Plotly](https://plot.ly/): interactive web visualization library
- [Beautiful Jekyll](https://deanattali.com/beautiful-jekyll/) : for the website
- [Folium](https://python-visualization.github.io/folium/): plot on geo data
- Leaflet.js: technology behind Folium

