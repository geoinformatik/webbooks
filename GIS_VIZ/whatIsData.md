# What is data
*  Data is commonly defined as a symbolic representation of information.
*  Data thus stores information and information can be extracted from data.
*  Advocates of the knowledge triangle believe that knowledge can be obtained from information, but remember that there is such a thing as misinformation.

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/KnowlageTriangel.jpg)


# How data represents information
*  Data as we use it typically comes in the form of <strong><span style="color: #0000ff;">values</span></strong> that define <strong><span style="color: #ff0000;">properties</span></strong> of <strong><span style="color: #ff00ff;">entities</span></strong>. i.e. the<strong><span style="color: #ff0000;"> highest completed education</span></strong> of <strong><span style="color: #ff00ff;">person_1</span></strong> is a <strong><span style="color: #0000ff;">masters program</span></strong>.
*  Another bit of data could specify that the <strong><span style="color: #ff0000;">gender</span></strong> of <strong><span style="color: #ff00ff;">person_1</span></strong> is <strong><span style="color: #0000ff;">female</span></strong>.
*  Note that the entity can be just a spatial location so the data could be of the form the <strong><span style="color: #ff0000;">elevation</span></strong> at<strong><span style="color: #ff00ff;"> loacation_1</span></strong> is <strong><span style="color: #0000ff;">35</span></strong> meters above sea-level.

# Tabular representation of data

* A way of representing data is on a tabular form 
* Each row represents a entity 
* Each column represent a properties
<table width="830" border-collapse:="collapse">
<tbody>
<tr>
<td width="189">
<p><strong>ID</strong></p>
</td>
<td width="145">
<p><strong><span style="color: #ff0000;">Gender</span></strong></p>
</td>
<td width="495">
<p><span style="color: #ff0000;"><strong>Highest completed education</strong> </span></p>
</td>
</tr>
<tr>
<td width="189">
<p><strong><span style="color: #ff00ff;">Person_1</span></strong></p>
</td>
<td width="145">
<p><strong><span style="color: #3366ff;">Female</span></strong></p>
</td>
<td width="495">
<p><strong><span style="color: #3366ff;">Masters program</span></strong></p>
</td>
</tr>
<tr>
<td width="189">
<p><strong><span style="color: #ff00ff;">Person_2</span></strong></p>
</td>
<td width="145">
<p><strong><span style="color: #3366ff;">Female</span></strong></p>
</td>
<td width="495">
<p><strong><span style="color: #3366ff;">Ph.D. program</span></strong></p>
</td>
</tr>
<tr>
<td width="189">
<p><strong><span style="color: #ff00ff;">Person_3</span></strong></p>
</td>
<td width="145">
<p><strong><span style="color: #3366ff;">Male</span></strong></p>
</td>
<td width="495">
<p><strong><span style="color: #3366ff;">Masters program</span></strong></p>
</td>
</tr>
</tbody>
</table>

# Types of data

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/data.svg)

# Unstructured data
> Cardiff After DarkBy Maciej Dakowicz

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/unstructuredData.jpg)

# What makes time different
* Entities can change property values over time, it is however seldom time it self that promotes the changes.
* Time can be seen as both a quantitative (continues) and a categorical (discreet)

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/chronoData1.jpg)

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/cronodata2a.jpg)

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/cronodata2b.jpg)


# What makes spatial data different
* Spatial data is represented as complex data.  Spatial data can depending on the situation be analysed as:
  * Categorical,
  * Quantitative
  * Unstructured
* Spatial data has special operators such as neighbourhood
* In visualisations spatial data  consumes the x-y dimension meaning that this dimension can not be used for other data.

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/spatialData1.png)

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/spatialdata2.jpg)
![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/spatialdata3.jpg)

# Key types of spatial data 
* A rather simplistic 3 layer classified: 
* Vector data: The geometry of the entity is represented as a point, line or polygon. 
![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/typesofspatiaData1.jpg)
* Raster data: Represents space by subdividing it into small squares and assigning a property value to each square  ![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/typesofspatialdata2.jpg)
* Non spatial data can easily be joined to spatial data if they have a common key (property) ![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/typesofspatialdata3.jpg)

# Aggregated properties
* Properties can either be measured properties or aggregated properties.
* Quantitative properties are typically aggregated in terms of :
  * Central tendency: average, meridian, sum 
  * Variation: StdDev
* Categorical properties are typical aggregates in terms of count and percentage.

# Organising aggregated data
* A common model of aggregated is a multidimensional data cube. 
![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/oranisingAggragateddata.jpg)

* In this concept the categorical properties function as dimensions while their unique valued define size.
* If there are more than one quantitative property in the dataset the names of these properties also appear as dimensions.
* The values of the dataset occupy the cells of the cube.


# Wide tables

* The dimensions in aggregated data can easily become rather large. 
* If you want to combine several dimensions the resulting tabular representation will have extremely many columns and are therefore called wide tables.

# Long tables
* The Principal of a long table is to have one column for each dimension of the data set and one column for value. 
 
 <table width="886">
<tbody>
<tr>
<td width="203">
<p><strong>Municipality</strong></p>
</td>
<td width="401">
<p><strong>Education</strong></p>
</td>
<td width="111">
<p><strong>Gender</strong></p>
</td>
<td width="80">
<p><strong>Year</strong></p>
</td>
<td width="91">
<p><strong>Value</strong></p>
</td>
</tr>
<tr>
<td width="203">
<p>Kerteminde</p>
</td>
<td width="401">
<p>Social science, SCE</p>
</td>
<td width="111">
<p>Men</p>
</td>
<td width="80">
<p>2017</p>
</td>
<td width="91">
<p>62</p>
</td>
</tr>
<tr>
<td width="203">
<p>Kerteminde</p>
</td>
<td width="401">
<p>Social science, SCE</p>
</td>
<td width="111">
<p>Women</p>
</td>
<td width="80">
<p>2006</p>
</td>
<td width="91">
<p>57</p>
</td>
</tr>
<tr>
<td width="203">
<p>Langeland</p>
</td>
<td width="401">
<p>Primary school 7th-9th grade</p>
</td>
<td width="111">
<p>Men</p>
</td>
<td width="80">
<p>2016</p>
</td>
<td width="91">
<p>1034</p>
</td>
</tr>
<tr>
<td width="203">
<p>Langeland</p>
</td>
<td width="401">
<p>Primary school 7th-9th grade</p>
</td>
<td width="111">
<p>Men</p>
</td>
<td width="80">
<p>2017</p>
</td>
<td width="91">
<p>1016</p>
</td>
</tr>
<tr>
<td width="203">
<p>Langeland</p>
</td>
<td width="401">
<p>Primary school 7th-9th grade</p>
</td>
<td width="111">
<p>Women</p>
</td>
<td width="80">
<p>2006</p>
</td>
<td width="91">
<p>1337</p>
</td>
</tr>
<tr>
<td width="203">
<p>Langeland</p>
</td>
<td width="401">
<p>Construction (TBT)</p>
</td>
<td width="111">
<p>Men</p>
</td>
<td width="80">
<p>2016</p>
</td>
<td width="91">
<p>462</p>
</td>
</tr>
<tr>
<td width="203">
<p>Langeland</p>
</td>
<td width="401">
<p>Construction (TBT)</p>
</td>
<td width="111">
<p>Women</p>
</td>
<td width="80">
<p>2006</p>
</td>
<td width="91">
<p>22</p>
</td>
</tr>
<tr>
<td width="203">
<p>Langeland</p>
</td>
<td width="401">
<p>Construction (TBT)</p>
</td>
<td width="111">
<p>Women</p>
</td>
<td width="80">
<p>2007</p>
</td>
<td width="91">
<p>24</p>
</td>
</tr>
</tbody>
</table>

# Slicing and dicing long tables
* Long tables are much more flexible when it comes to slicing and dicing large data amounts.
* Long tables need to be sliced and diced before use typically by using in pivot tables/graphs in a spreadsheet or in specialised visualisation tools such as tableau.
* In QGIS you can use the “group statistics” plugin to slice and dice long tables.
* For statistical data it is also often possible to slice and dice before downloading the data.




<table width="825">
<tbody>
<tr>
<td width="149">
<p><strong>Municipality</strong></p>
</td>
<td width="159">
<p><strong>Year_1 &ndash; Education_1</strong></p>
</td>
<td width="105">
<p><strong>Year_1 - &hellip;</strong></p>
</td>
<td width="156">
<p><strong>Year_1 &ndash;</strong></p>
<p><strong>Education_N</strong></p>
</td>
<td width="96">
<p><strong>&hellip;.</strong></p>
</td>
<td width="161">
<p><strong>Year_N</strong><strong>-</strong></p>
<p><strong>Education_N</strong></p>
</td>
</tr>
<tr>
<td width="149">
<p>Copenhagen</p>
</td>
<td width="159">
<p>50</p>
</td>
<td width="105">
<p>130</p>
</td>
<td width="156">
<p>1138</p>
</td>
<td width="96">
<p>&hellip;.</p>
</td>
<td width="161">
<p>556</p>
</td>
</tr>
<tr>
<td width="149">
<p>Roskilde</p>
</td>
<td width="159">
<p>2</p>
</td>
<td width="105">
<p>10</p>
</td>
<td width="156">
<p>437</p>
</td>
<td width="96">
<p>&hellip;..</p>
</td>
<td width="161">
<p>12</p>
</td>
</tr>
<tr>
<td width="149">
<p>&hellip;.</p>
</td>
<td width="159">&nbsp;</td>
<td width="105">&nbsp;</td>
<td width="156">&nbsp;</td>
<td width="96">&nbsp;</td>
<td width="161">&nbsp;</td>
</tr>
</tbody>
</table>

