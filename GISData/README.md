# GISData

Source shapefiles are not committed to this repository. Download the layers from
Gunnison County's public GIS data and place them here before running `docker compose up`.

`load-shapefiles.sh` expects these shapefiles (with their `.dbf`, `.prj` and `.shx` companions):

- `Address.shp`
- `Driveway.shp`
- `Exempt.shp`
- `Jurisdictions.shp`
- `Road.shp`
- `Sections.shp`
- `Subdivision.shp`
- `Taxdistrict.shp`
- `Taxparcelassessor.shp`
- `Towns.shp`
- `VotingPrecincts.shp`

See `load-shapefiles.sh` for the full list of layers and their coordinate systems.
