# leaflet-ld
A repository to gather ideas, issues and links to resources for development of a leaflet capability able to support semantically enabled IPT.

## plug-ins

### Linked Data for GeoJSON
support use of JSON-LD in leaflet, leveraging the OGC Building Blocks capability to create JSON-LD contexts for GeoJSON structures.
link to development repo: TBD

see https://github.com/ogcincubator/ogc-fl-demo  - how should we integrate plug-ins?


### SPARQL result set
Knowledge Graphs can support SPARQL (yuk) but simple REST stored queries

exploit templated access in OGC API records to get a result in [standard SPARQL results JSON](examples/sparql-result.json)

This can generally be used to access data to augment a UI where a KG hs more information about an object.

### OGC API processes for workflows

call a process that returns a provenance trace

### JSON-FG

support customisation based on "featureType" property. 
exploit LD plugin to apply contexts from FeatureType catalogs (using OGC API Records?)


















