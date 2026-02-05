# leaflet-ld
A repository to gather ideas, issues and links to resources for development of a leaflet capability able to support semantically enabled IPT.

## Leaflet plug-ins roadmap.

### Linked Data (LD) for GeoJSON
support use of JSON-LD in leaflet, leveraging the OGC Building Blocks capability to create JSON-LD contexts for GeoJSON structures.

A key issue is the use of "resolvers" for URIs for either URIs that do not return a machine readable semantic description or for environments where either we cannot access the Web or may know more information about the object that the object itself knows.

link to development repo: TBD

Two examples to consider:
1. BBlocks Examples exposed vi OGC API Features (pygeoAPI) with LD https://defs-dev.opengis.net/bblocks-pygeoapi/collections/ogc.bbr.examples.observation.vectorObservationFeature/items/vector-obs-1
2. An "explainer" showing how LD works: https://github.com/ogcincubator/ogc-fl-demo  - this doesnt use a resolver and requires well behaved URI dereferencing.


### SPARQL result set
Knowledge Graphs can support SPARQL (yuk) but simple REST stored queries

exploit templated access in OGC API records to get a result in [standard SPARQL results JSON](examples/sparql-result.json)

This can generally be used to access data to augment a UI where a KG hs more information about an object.

### OGC API processes for workflows

call a process that returns a provenance trace

### JSON-FG

support customisation based on "featureType" property. 
exploit LD plugin to apply contexts from FeatureType catalogs (using OGC API Records?)


















