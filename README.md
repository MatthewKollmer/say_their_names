# The Say Their Names Project

The Say Their Names Project is one sub-project in the larger [Virality of Racial Terror Project (VRT)](https://www.racialviolencearchive.com/vrt-project.html), a grant-funded initiative that applies computational methods to identify and study the circulation of racial violence reports in the United States between 1865 and 1921. In that regard, the Say Their Names Project specifically relies on existing datasets of lynchings from the period. It builds off a century's worth of work by journalists, activists, and researchers–from Ida B. Wells-Barnett, Monroe Work, the NAACP, and many others–who collectively documented instances of lynchings and racial violence over many decades. Thanks to this rich tradition of activism through research, we have data that provides victim names, places, and dates, and in turn, a much better understanding of the unfortunate legacy of racial violence in the United States.

Two resources, more recently compiled, have become integral to the Say Their Names Project. They are the [Seguin-Rigby Dataset](https://journals.sagepub.com/doi/full/10.1177/2378023119841780) and the [Tolnay-Beck Inventory](https://www.press.uillinois.edu/books/?id=p064135). Together they include documentation of thousands of victims of racial violence. Both resources were compiled by sociologists and researchers who investigated numerous other sources and archives. Using their data, the Say Their Names Project has built a pipeline for text-mining digitized newspapers in order to identify reports and reprintings of lynchings. The results are new datasets that allow us to study racial violence reporting at numerous scales–from the individual instances of racial violence, to regional, local, and national responses to the broader phenomenon of lynching.

This repository is a presentation of code from the Say Their Names Project. It is intended to make our pipeline more easily replicable and reviewed. Please note that this work is ongoing, and so this repository will see many updates in the near future. But if you'd like to follow along, you can retrace every computational step in the following Python notebooks:

1) unify our data sources (see [01_unify_data_sources.ipynb](https://github.com/MatthewKollmer/say_their_names/blob/main/01_unify_data_sources.ipynb))
2) pull search results from Chron Am (see [02_pull_search_results.ipynb](https://github.com/MatthewKollmer/say_their_names/blob/main/02_pull_search_results.ipynb))
3) scrape search results (see [03_scrape_search_results.ipynb](https://github.com/MatthewKollmer/say_their_names/blob/main/03_scrape_search_results.ipynb))
4) enrich our datasets (see [04_enrich_dataset.ipynb](https://github.com/MatthewKollmer/say_their_names/blob/main/04_enrich_dataset.ipynb))
5) select a random sample (see [05_random_sample.ipynb](https://github.com/MatthewKollmer/say_their_names/blob/main/05_random_sample.ipynb))
6) label the training data (see [06_label_training_data.ipynb](https://github.com/MatthewKollmer/say_their_names/blob/main/06_label_training_data.ipynb))
7) TBD

To understand the genesis of this project, you may also want to review my draft version here: [https://github.com/MatthewKollmer/messing-around/tree/main/vrt_work/say_their_names](https://github.com/MatthewKollmer/messing-around/tree/main/vrt_work/say_their_names). This draft version shows how the project involved numerous iterations, failed attempts, explorations, and non-linear processes. It contains journal entries alongside code and other resources. The draft version is admittedly more convoluted, but it's also a fully transparent resource that highlights the many _processes_ involved in this kind of work.

If you need access to the data, please [contact me](https://matthewkollmer.com/contact/). Once I send you an invite, the Say Their Names data can be found here: [https://uofi.app.box.com/folder/283227580250](https://uofi.app.box.com/folder/283227580250). 
