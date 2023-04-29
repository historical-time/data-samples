# NeoNet dataset sample
> All the data is available on the NeoNet GitHub.: https://github.com/zoometh/neonet/blob/main/inst/extdata/140_140_id00140_doc_elencoc14.tsv

[NeoNet](https://github.com/zoometh/neonet) is a research software for dynamic mapping of radiocarbon (C14) dates of the Late Mesolithic/Early Neolithic transition in the North-Central Mediterranean and South Atlantic European river basin. 

* The [R Shiny app](http://shinyserver.cfs.unipi.it:3838/C14/) offers a mobile geographic window for date selection by location, various filters on chronology and date quality, a calibration window, and other tools to create a user-friendly interface supported by a curated dataset of radiocarbon dates and archaeological contexts;

* The [published dataset](https://digitallib.unipi.it/it/raccolta/The-NeoNet-dataset-version-1.-A-new-dataset-of-radiocarbon-dates-for-the-study-of-the-Late-Mesolithic-Early-Neolithic-transition-in-the-North-Central-Western-Mediterranean-watershed./) counts ~ 2,500 radiocarbon dates with their archaeological context (site, layer, associated culture, etc.)  

## References 
Huet, T., Cubas, M., Gibaja, J. F., Oms, F. X., & Mazzucco, N. (2022). *NeoNet Dataset. Radiocarbon Dates for the Late Mesolithic/Early Neolithic Transition in the North Central-Western Mediterranean Basin*. Journal of Open Archaeology Data, 10(3).
 
# Stratigraphic and Bayesian analysis of the radiocarbon dates

In the frame of this chronological modelling workgroup, our aim is to:

1. build the Harris Matrix of NeoNet many sites with graph theory, and FAIR standards
2. run Bayesian analysis on-the-fly using both the radiocarbon dates and the stratigraphy information

A current example of this type of modelling can be found for the archaeological site of [Obagues de Ratera](https://github.com/historical-time/data-samples/blob/main/neonet/TEST.tsv)
