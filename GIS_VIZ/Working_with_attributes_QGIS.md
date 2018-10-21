## <a id="WorkingWithAttributes"/>Working with attributes

*   Creating new attributes
*   Deleting attributes
*   Calculating attribute values

The attribute manipulation is available in:

1.The fields tab of the layer properties

2.The attribute table of the layer

Which environment to use:

1.The tools are almost the same

2.The attribute table is easier to use with small feature classes (< 10000) objects

3.The fields tab is much quicker to use on large feature classes and perhaps also less cluttered

## <a id="TheAttributeTableFilterNaviggate"/>The Attribute table filter and naviggate

## <a id="TheAttributeTableCreateEditAttributes"/>Create and edit attributes in the Attribute table

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/sql_res/wwa_22.JPG)

## <a id="proppertiesCreateEditAttributes"/>Create and edit attributes in propperties field table

Qgis operates with two types of attributes:

*   Real attributes stored in the data file
*   Virtual attributes that are calculated on the fly and stored in the project document.

Both types of attributes must be declared as a data type and size:

*   Whole number (Integer) -2,147,483,648 to 2,147,483,647
*   Decimal number (real) approximately -3.4E38 to 1.2E38
*   Text (string) 100 charecters
*   Date
*   Date time (SpatiaLite)

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/sql_res/wwa_23.JPG)

## <a id="TheFieldCalculato"/>The Field calculator

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/sql_res/wwa_23.JPG)

