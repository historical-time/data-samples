# Linked Places (LPF) data samples

Linked Places format extends the GeoJSON standard, principally by providing a "when" element that can be used to temporally scope an entire place record, and/or to any of its asserted names, types, geometries, and relations to other places. See the LPF [documentation and spec](https://github.com/LinkedPasts/linked-places-format) for more information.

Examples:

* [Abingdon (UK)](Abingdon.jsonld)
Example from the spec illustrating most of the format's required and optional elements.

	A single FeatureCollection with a single feature, titled 'Abingdon (UK)'

	The entire Feature is temporally scoped by a "when" element, with both a timespan and multiple references to named periods.
Other attributes temporally scoped in this way are names, type (place type), geometry, and relations to other entities.

    
* [Ciudad de Mexico](Ciudad-de-Mexico.jsonld), from the [HGIS de las Indias contribution in World Historical Gazetteer](). Derived from data in the [original project]().

	A single FeatureCollection with a single feature, titled 'Ciudad de Mexico'
	
	The name 'Mexico' is temporally scoped, as are the single point geometry and five part-of relations to administrative units: the broad territory, a Jurisdiccion, an Audiencia, an Obispado, and a Provincia.
    