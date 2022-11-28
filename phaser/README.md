The Matrix project has developed software to support stratigraphic analysis and temporal analysis - Phasing, Grouping and Periodization - by archaeologists using Harris Matrix methodologies. The [prototype software tool](https://stratigraphic.github.io/phaser-app/) is called "Phaser". A [help file](https://stratigraphic.github.io/phaser-app/help.html) explaining more of the functionality of the Phaser software and how to use it is available.

The prototype _is not intended currently to be fully functioning_ Matrix recording and Stratigraphic Phasing analysis and archiving software. It would need more development and administrative work and resources to make it available e.g. as Open and FAIR software through an online tool with suitable registration for an archaeological community of users.

The prototype _is designed to enable demonstration_ and an overview of what we have developed so far in the Matrix project and particularly to elicit feedback from the archaeologial community on what such an online tool might need to do to encourage archaeologists involved in post-excavation analysis to use it and support it’s improvement and sustainability through its development life-cycle.

Please note that in the current prototype stage _it is not recommended to try loading a CSV file with more than around 500-3000 individual context records_. Depending upon feedback on this initial development, the software could be further developed to enable larger numbers of records to be entered, but this would require more time and further resources to enable testing and resolving scaleability issues.

See [an example test data set](CTD2021-Test-Data/CTD2021-phaser-20210504114322-with-Dating-test-data.json).

Here is a short video clip explaining how to import a CSV file into the Phaser software:

<video width="320" height="240" controls>
<source type="video/mp4" src="https://github.com/stratigraphic/matrix/blob/gh-pages/images/Importing_CSV_file_example5.mp4?raw=true">
</video>

Or make your own CSV file data set using the following 4 key fields with the matching field name headings.

CSV column heading names need to be exactly as spelled below:

* siteCode
* sourceID
* stratRelationship
* targetID
