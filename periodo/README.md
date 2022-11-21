# PeriodO data samples

See the [documentation of how temporal extents are represented in PeriodO](https://perio.do/technical-overview/#temporal-extent).

Examples:

* [Mell. Enkeltgravskultur](mud-mell-enkeltgravskultur.ttl) as [defined in MUD - Museernes Udgravningsdata Danmark Dateringskodetabel](http://n2t.net/ark:/99152/p0r8d9ccs43)
    
    A single year for the start interval and a single year for the stop interval.
    
    Both year values directly correspond to how the years are represented in the original source, because the original source also uses proleptic Gregorian years with year 0 (the value `0000` is interpreted as 1 BCE).
    
* [Banshan Period](british-museum-banshan.ttl) as [defined by the British Museum](http://n2t.net/ark:/99152/p08m57h395t)

    A single year for the start interval and a single year for the stop interval.
    
    Here the proleptic Gregorian year values are an interpretation of how the values are represented by the original source, which uses BC.
    
* [Late Archaic Period](johnson-goode-late-archaic.ttl) as [defined by Johnson and Goode](http://n2t.net/ark:/99152/p0t3585c8d7)

    A single year for the start interval and a range of years for the stop interval.
    
* [Tournaisian Age](icc-tournaisian.ttl) as [defined in the Geologic Time Scale (2020)](http://n2t.net/ark:/99152/p09qtgwqhqk)

    A range of years for the start interval and a range of years for the stop interval.

* [Reiwa era](harmon-yanase-reiwa.ttl) as [defined by Harmon and Yanase](http://n2t.net/ark:/99152/p0fbfthrjgj)

    A single year for the start interval and no numeric value for the stop interval (just the label "present").
