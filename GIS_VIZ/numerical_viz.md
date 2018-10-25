# Overview :
* Ways of communicating numbers
* Why visualize data
* What are the characteristics of a good visualisation?
* What are the characteristics of a good Visual Narrative ?
* The purposeful conversion of numbers to visual narratives.

## Four ways to communicate numbers
* Tabular form
* Summery statistics Mean, variance etc.
* Inferential statistics Identifying significant differences
* Visualization (Visual narrative)

## Why Data Visualisation
* The brain is a fantastic visual pattern processing machine. 
* We are able to effortless detect minute variations from a patten
* Visualisation is a ”effective way of laying open the data to display the unanticipated

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/num_viz1.jpg)

## Laying data open to display the unanticipated.
> (Anscombe 1973)


<table style="border-collapse: collapse; width: 347px; height: 638px;" border="1px">
<tbody>
<tr>
<td style="width: 90px; text-align: center;" colspan="2">
<p><strong>Set A</strong></p>
</td>
<td style="width: 70px; text-align: center;" colspan="2">
<p><strong>Set B</strong></p>
</td>
<td style="width: 68px; text-align: center;" colspan="2">
<p><strong>Set C</strong></p>
</td>
<td style="width: 98px; text-align: center;" colspan="2">
<p><strong>Set D</strong></p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>X</p>
</td>
<td style="width: 41px;">
<p>Y</p>
</td>
<td style="width: 30px;">
<p>X</p>
</td>
<td style="width: 40px;">
<p>Y</p>
</td>
<td style="width: 33px;">
<p>X</p>
</td>
<td style="width: 35px;">
<p>Y</p>
</td>
<td style="width: 41px;">
<p>X</p>
</td>
<td style="width: 57px;">
<p>Y</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>10</p>
</td>
<td style="width: 41px;">
<p>8,04</p>
</td>
<td style="width: 30px;">
<p>10</p>
</td>
<td style="width: 40px;">
<p>9,14</p>
</td>
<td style="width: 33px;">
<p>10</p>
</td>
<td style="width: 35px;">
<p>7,46</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>6,58</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>8</p>
</td>
<td style="width: 41px;">
<p>6,95</p>
</td>
<td style="width: 30px;">
<p>8</p>
</td>
<td style="width: 40px;">
<p>8,14</p>
</td>
<td style="width: 33px;">
<p>8</p>
</td>
<td style="width: 35px;">
<p>6,77</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>5,76</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>13</p>
</td>
<td style="width: 41px;">
<p>7,58</p>
</td>
<td style="width: 30px;">
<p>13</p>
</td>
<td style="width: 40px;">
<p>8,74</p>
</td>
<td style="width: 33px;">
<p>13</p>
</td>
<td style="width: 35px;">
<p>12,74</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>7,71</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>9</p>
</td>
<td style="width: 41px;">
<p>8,81</p>
</td>
<td style="width: 30px;">
<p>9</p>
</td>
<td style="width: 40px;">
<p>8,77</p>
</td>
<td style="width: 33px;">
<p>9</p>
</td>
<td style="width: 35px;">
<p>7,11</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>8,84</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>11</p>
</td>
<td style="width: 41px;">
<p>8,33</p>
</td>
<td style="width: 30px;">
<p>11</p>
</td>
<td style="width: 40px;">
<p>9,26</p>
</td>
<td style="width: 33px;">
<p>11</p>
</td>
<td style="width: 35px;">
<p>7,81</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>8,47</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>14</p>
</td>
<td style="width: 41px;">
<p>9,96</p>
</td>
<td style="width: 30px;">
<p>14</p>
</td>
<td style="width: 40px;">
<p>8,1</p>
</td>
<td style="width: 33px;">
<p>14</p>
</td>
<td style="width: 35px;">
<p>8,84</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>7,04</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>6</p>
</td>
<td style="width: 41px;">
<p>7,24</p>
</td>
<td style="width: 30px;">
<p>6</p>
</td>
<td style="width: 40px;">
<p>6,13</p>
</td>
<td style="width: 33px;">
<p>6</p>
</td>
<td style="width: 35px;">
<p>6,08</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>5,25</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>4</p>
</td>
<td style="width: 41px;">
<p>4,26</p>
</td>
<td style="width: 30px;">
<p>4</p>
</td>
<td style="width: 40px;">
<p>3,1</p>
</td>
<td style="width: 33px;">
<p>4</p>
</td>
<td style="width: 35px;">
<p>5,39</p>
</td>
<td style="width: 41px;">
<p>19</p>
</td>
<td style="width: 57px;">
<p>12,5</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>12</p>
</td>
<td style="width: 41px;">
<p>10,84</p>
</td>
<td style="width: 30px;">
<p>12</p>
</td>
<td style="width: 40px;">
<p>9,11</p>
</td>
<td style="width: 33px;">
<p>12</p>
</td>
<td style="width: 35px;">
<p>8,15</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>5,56</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>7</p>
</td>
<td style="width: 41px;">
<p>4,82</p>
</td>
<td style="width: 30px;">
<p>7</p>
</td>
<td style="width: 40px;">
<p>7,26</p>
</td>
<td style="width: 33px;">
<p>7</p>
</td>
<td style="width: 35px;">
<p>6,42</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>7,91</p>
</td>
</tr>
<tr>
<td style="width: 49px;">
<p>5</p>
</td>
<td style="width: 41px;">
<p>5,68</p>
</td>
<td style="width: 30px;">
<p>5</p>
</td>
<td style="width: 40px;">
<p>4,74</p>
</td>
<td style="width: 33px;">
<p>5</p>
</td>
<td style="width: 35px;">
<p>5,73</p>
</td>
<td style="width: 41px;">
<p>8</p>
</td>
<td style="width: 57px;">
<p>6,89</p>
</td>
</tr>
</tbody>
</table>
</blockquote>
<table>
<thead>
<tr>
<th>Stat</th>
<th>X</th>
<th>Y</th>
</tr>
</thead>
<tbody>
<tr>
<td>Mean</td>
<td>9.0</td>
<td>7.5</td>
</tr>
<tr>
<td>StdVar</td>
<td>3.317</td>
<td>2.03</td>
</tr>
</tbody>
</table>
Linear Regression Y2 = 3 + 0.5 X


(R2 = 0.67)


![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/graph_set%20A-D.png)


## What are the characteristics of a good visualisation?
1. Expressive The truth, the hole truth and nothing but the truth.
2. Efficient Focus the attention on the important aspects.
3. A good visualisation is the right tool for the job.

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/graph.jpg)


## What are the characteristics of a good visual narrative?
* Engages the reader.
* Is esthetical pleasing.
* Should be memorable.
* Enables the reader to explore different aspects of the date by combining multiple visualisations.
* Not compromising the rules of a good visualisation

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/diamands.jpg)

# What to consider when designing a data visualisation
There are several classical texts that addresses the question of what is a good visualization 
* J. Bertin  1967
  Retina (visual ) variables and their Characteristics
* Edward Tufte 1983
  Optimise the Data-Ink ratio
*Cleveland & McGill 1984 
  Empirical estimates of the effectiveness of different graphical encoding  methods:
* Jock Mackinlay 1986 
  Two measures for choosing the right visualisation :
  Expressiveness
  Effectiveness
  
## Defining color
*  RGB: Monitors
*  CMYK : Printers
*  LAB : Human vision simulation (Adobe)
*  HSV (HSL/HSB) : Mapping applications ![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/hsv.jpg)
*  Predefined colour schemes:

## Colour schemas
*  Discreet schemas:
  Each colour should be distinct and typical for its name
  ![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/Discreet_schemas.jpg)
* Continuous schemas
  Problem which colour represents the high value and ido we see it as linear. The four main types:
  * Multi hue or spectrum schemas:![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/SpecturalSchemas.jpg)
  * Bifocal colour schemas:![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/BifocalSchemas.jpg)
  * Bifocal over white : ![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/Bifocal_WhteSchemas.jpg)
  * Mono hue schemas : ![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/MonoHuelSchemas.jpg)
  
For example on colour schemas on maps see <http://colorbrewer2.org/>

## Graphical retina (visual) variables
> Semiologi of Graphics J. Bertin  1967

![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/visualVariable.jpg)
*  X,Y location (2PD)
*  Shape (Sh)
*  Size (Si)
*  Value (V)
*  Texture (T)
*  Colour hue (C)
*  Orientation (Or)


## Characteristics of retina variables
> Semiologi of Graphics J. Bertin  1967

Characteristics governing the use of retina variables
*  Selective Distinguish a class objects from the others
*  Associative  Identify all objects of the same class
*  Order  Identify all steps of the order, min to max
*  Quantitative numerically identify the distance between objects
*  Length is a property of all characteristics specifying the number of possible classes
![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/visualVariableCompar.jpg)

## Optimise the Data-Ink ratio
(Data ink/total ink used in graph)
![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/dataInk.jpg)

## The effectiveness of different graphical encoding  methods
![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/graphicalEncodingCompare.jpg)

> Cleveland & McGill 1984 
![](https://geoinformatik.github.io/webbooks/GIS_VIZ/viz_res/graphicalEncodingCompCleveland.jpg)

