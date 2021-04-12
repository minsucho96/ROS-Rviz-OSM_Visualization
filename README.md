
Overview
========

`Open_street_map`_ is a repository of ROS_ packages for working with `Open Street Map`_ information.

# Get Started

Step 1) Clone this package on your workspace

Step 2) `catkin_make`

Step 3) Launch osm_cartography. `roslaunch osm_cartography geo_planner.launch`

# How to change the OSM file
If you want to replace the osm file to your own, put yours in `[YOUR_WORKSPACE]/src/open_street_map/osm_cartography/maps`. 

Then, change the `map_url` in `geo_planner.launch`. Also, you should modify the `tf` arguments  accordingly.

# Results

[Open Street Map of KAIST]
![Open Street Map of KAIST](/test_image/osm_kaist.png)

[Rviz Visualization]
![Rviz Visualization](/test_image/rviz_result.png)

<img src="/test_image/rviz_result.png" alt="Rviz Visualization" style="width:30px;"/>
