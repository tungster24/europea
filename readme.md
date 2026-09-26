![Europea Series](logos/logo.png)
# tungster24's Europea Series

The Europea Series is a companion to the NextGen OTL WorldA series of maps that
were made by Hadaril. It's an attempt to remake the *europe* map that used to be
a part of the NextGen series.

To use them, simply download this repository.

## Directories

1. The `blank` directory stores blank maps for each time period. These also
contain rivers.
2. The `political` directory stores the maps that display nations.
3. The `exports` directory stores the raw exports. These require some manual
processing to work with.
4. The `data` directory has clean data ready to use. This includes the heightmap
both in raw b/w and colorised with rivers.
5. The `gis` directory contains the `.qgz` (QGIS project) and `.qpt` (QGIS
composer template) files. You can use these files to create your own exports for
Europea.
6. The `logos` directory simply contains logos used for the github repository.

## Specification

If you wish to export maps for Europea from other software, don't fret. Europea
uses:

```
Lambert Azimuthal Equal Area centered on 52°N, 10°E
```
known in QGIS as:
```
ESPG:3035
ETRS89-extended / LAEA Europe
```

## Political map dates

The following dates currently have a full Europea map:
* 1789-01-01
* 1910-01-01
* 1930-01-01
* 2026-04-05

## Special thanks
These are other people who have done work on the project, or just people I want
to thank:
* jakemakesmaps
* kyaazu
* jurrasiczilla
* historicalbrazil
* hyade
