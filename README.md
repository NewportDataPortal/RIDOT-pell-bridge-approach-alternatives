# RIDOT Pell Bridge Approach Alternatives 

This dataset contains georeferenced images of Pell Bridge Approach design alternatives presented at public workshops in Newport on 16 and 17 July, 2018.  The source materials are located [here](http://pellbridge-ea.com/documents.asp).

## Data processing steps

1. The map image is extracted from the pdf presentation and converted to a .png image file
2. The .png image file is loaded into QGIS 3.0 Georeferencer.  Georeferencing points are in the `alternative-x.png.points` files.
3. Using the QGIS georeferencer, the image is transformed into a georeferenced .tiff file using a Helmert transformation with cubic image interpolation.

