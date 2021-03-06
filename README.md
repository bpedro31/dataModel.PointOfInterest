[![Status badge](https://img.shields.io/badge/status-draft-red.svg)](RELEASE_NOTES)
[![Build badge](https://img.shields.io/travis/smart-data-models/dataModel.PointOfInterest.svg "Travis build status")](https://travis-ci.org/smart-data-models/dataModel.PointOfInterest/)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
# Point of interest data models.

These data models allow to model points of interest and related entity types:

-   [`PointOfInterest`](https://swagger.lab.fiware.org/?url=https://raw.githubusercontent.com/smart-data-models/dataModel.PointOfInterest/master/PointOfInterest/swagger.yaml) : A harmonised geographic
    description of a point of interest. According to
    [Wikipedia](https://en.wikipedia.org/wiki/Point_of_interest) a point of
    interest, or POI, is a specific point location that someone may find useful
    or interesting.

-   [`Beach`](https://swagger.lab.fiware.org/?url=https://raw.githubusercontent.com/smart-data-models/dataModel.PointOfInterest/master/Beach/swagger.yaml) : A harmonised description of a beach.
    [OpenStreetMap](http://wiki.openstreetmap.org/wiki/Tag:natural%3Dbeach)
    defines it as a loose geological landform along the coast or along another
    body of water consisting of sand, gravel, shingle, pebbles, cobblestones or
    sometimes shell fragments, etc.

-   [`Museum`](https://swagger.lab.fiware.org/?url=https://raw.githubusercontent.com/smart-data-models/dataModel.PointOfInterest/master/Museum/swagger.yaml) : A harmonised description of a museum.
    [OpenStreetMap](http://wiki.openstreetmap.org/wiki/Tag:tourism%3Dmuseum)
    defines it as an institution which has exhibitions on scientific,
    historical, cultural topics. Typically open to the public as a tourist
    attraction. May be more heavily involved in acquiring, conserving or
    researching such topics.

-   [TouristInformationCenter](https://schema.org/TouristInformationCenter). A
    tourist information center which serves as an information source for
    tourists, travellers and visitors. It can be represented by an entity of
    type `PointOfInterest` which category is equal to `439`. Another option is
    to use the schema.org `TouristInformationCenter` entity type and include
    those properties which domain is `PointOfInterest` and/or properties which
    domain is `http://schema.org/TouristInformationCenter`.
