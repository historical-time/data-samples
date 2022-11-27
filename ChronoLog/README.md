# ChronoLog data samples

## The ChronoLog data model

[ChronoLog](https://chrono.ulb.be/) is a modelling tool for historical and archaeological chronologies. Its data model is based on three typs of objects: *periods*, *sequences* and *synchronisms*: 
* A period can represent any continuous period of time (historical era, reign, archaeological period, stratum, ceramic style, ...). ChronoLog periods have 3 fields: start, end, duration (all expressed in years). None of these fields is mandatory, hence a period can be fully known (precise value for start, end or duration), totally unknown (no value for any of the 3 fields) or something in-between (partial knowledge for the start, end, or duration). Such partial knowlege is expressed using bounds: the start, end or duraiton of a period, can have a lower bound (i.e., a minimum value), an upper bound (i.e., a maximum value) or a range (both a minimum and a maximum value). Values can also be exact (i.e., 1984), which corresponds to a range with equal lower and upper bound. 
* Periods are then stacked to make *sequences*. A sequence is a set of periods such that the start of the next period equals the end of the previous period (with no gap). 
* Finally, *synchronisms* are relations between two periods. ChronoLog supports dozen of types of synchronisms, such as contemporaneity, inclusion, overlap, etc... 

For more details on the ChronoLog data model, see: 

* [ChronoLog user manual](https://chrono.ulb.be/download/)
* [JAS article](https://doi.org/10.1016/j.jas.2020.105225)

## ChronoLog File formats

* .clog format : ChronoLog models are saved in a "ChronoLog" format (.clog) which is a JSON format. Such files are not intended to be read by humans, although they are quite easy to understand. They are automatically created by ChronoLog when one saves a model (these models are created interactively, by "point and click") and the user can load them in ChronoLog using the "File-->Open" menu.

* CSV format: ChronoLog can export and import models in CSV format. This is done in two steps: first export/import the sequences, then the synchronisms (via the " File" menu).

Examples of such files for our dummy example called "ChronoLand" (see user manual and JAS paper) are provided in this repository. For more complex exampes, from real-life case studies, see [here](https://chrono.ulb.be/download/).