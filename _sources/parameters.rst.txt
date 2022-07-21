Customizing Parameters
==================================================================

=======================
Basic Parameters
=======================
The first tab has basic parameters and the second tab has advanced parameters. You can change between basic and advanced parameters by clicking the tab in the image below. 

.. image:: /images/HIV_GUI.png
  :width: 800
  :alt: basic_parameter
  :target: parameters.html


=======================
Advanced Parameters
=======================
.. image:: /images/Advanced1.PNG
    :width: 800
    :alt: advanced_parameter
    :target: parameters.html
	
.. list-table::
  :widths: 10 40
  :header-rows: 1

  * - Parameter
    - Description
  * - ``Title``
    - Title text that would appear in the top of the result visualization file.
  * - ``Shapefile Path``
    - File path of shapefile that would be a base map layer to map visualization.
  * - ``CSV File``
    - File path of the CSV file that you want to visualize on the maps.
  * - ``Number of Maps``
    - Number of maps to visualize in the HTML file.
  * - ``Map: Select Variable and Year``
    - Layers you want to visualize in the maps.
  * - ``Initial Map Center (lat, lon)``
    - Longitude and latitude coordinates of the map center.
  * - ``Initial Map Zoom Level``
    - Set the zoom level for maps. Increasing the number will zoom-in maps.
  * - ``Map Width``
    - Set the width of the map in pixels
  * - ``Name of Variables``
    - Enter variable names to be visualized in the visualization. 

Parameters below are specific to different chart types for Multiple Line Chart(MLC), Comparison Line Chart (CLC), and Parallel Coordinate Plot(PCP) respectively.

.. image:: /images/Advanced2.PNG
    :width: 800
    :alt: advanced_parameter
    :target: parameters.html
|
Multiple Line Chart(MLC)

.. list-table::
  :widths: 10 40
  :header-rows: 1

  * - Parameter
    - Description
  * - ``Number of MLC(s)``
    - The number of MLC charts. 
  * - ``Selected Variables``
    - Names of variables to be visualized in MLC. e.g. HIV Rate,Opioid Prescriptions
  * - ``Highlight Method``
    - This parameter only applies to MLC. Determine which time period to highlight, and in which color in 'start time, end time, colorcode' format (e.g., 2019, 2026, #fdff32).

Comparison Line Chart (CLC)

.. list-table::
  :widths: 10 40
  :header-rows: 1
  
  * - Parameter
    - Description
  * - ``Number of CLC(s)``
    - The number of values on the X-axis of CLC.
  * - ``Selected Variables``
    -  Names of variables to be visualized in CLC. 
	   e.g. 2012_PrEP Use, 2013_PrEP Use, 2014_PrEP Use, 2015_PrEP Use, 2016_PrEP Use, 2017_PrEP Use, 2018_PrEP Use

Parallel Coordinate Plot(PCP)
 
.. list-table::
  :widths: 10 40
  :header-rows: 1
  
  * - Parameter
    - Description
  * - ``Number of PCP(s)``
    - The number of variables in the PCP chart.
  * - ``Selected Variables``
    - Names of variables to be visualized in PCP
	   e.g.  2012_HIV Rate, 2012_Opioid Prescriptions, 2012_% people as Food Stamp/SNAP Recipients


More Options

.. list-table::
  :widths: 10 40
  :header-rows: 1
  
  * - Parameter
    - Description
  * - ``Top 10 Chart``
    - A Top 10 Chart linked with the right-side map.
  * - ``Exclude Outliers``
    - Exclude extreme outliers to avoid skewed results.


