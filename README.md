# INSPIRE_Coverage
Sorting the issues in INSPIRE Coverage encoding


## Original INSPIRE Elevation Grid Coverage Model
The following UML Model is from the INSPIRE Data Specification for Elevation - shows the ElevationGridCoverage featureType, that has been derived from RectifiedGridCoverage. Unfortunately, due to the way this FT was extended, it cannot be provided via a WCS

![Original INSPIRE Elevation Grid Coverage Model](https://github.com/DataCoveEU/INSPIRE_Coverage/blob/master/pix/Elevation%20Extension%20Example.png)

## Modified INSPIRE Elevation Grid Coverage Metadata Element Model
In the following UML Model, we've extracted the parts that were originally extended to the RectifiedGridCoverage FT for ElevationGridCoverage and created a stand-alone FT ElevationGridCoverageMetadata, that can be provided in the coverage metadata element. All attributes from the original ElevationGridCoverage FT have been maintained.

![Modified INSPIRE Elevation Grid Coverage Metadata Element Model](https://github.com/DataCoveEU/INSPIRE_Coverage/blob/master/pix/Elevation%20Metadata%20Example.png)

The schema for ElevationGridCoverageMetadata is available at: https://schema.datacove.eu/ElevationGridCoverageMetadata.xsd
