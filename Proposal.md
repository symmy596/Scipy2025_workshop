# Scipy2025
 
**Title:**

**Session Type: Tutorial (4 Hours)**

**Track: Tutorials**

**Abstract**

The rapid expansion of the geospatial industry and accompanying increase in availability of geospatial data, presents unique opportunities and challenges in data science. As the need for skilled data scientists increases, the ability to manipulate and interpret this data becomes crucial. This workshop introduces the essentials of geospatial data manipulation and data visualisation, emphasizing hands-on techniques to transform, analyze and visualise diverse datasets effectively.

Throughout the workshop, attendees will explore the extensive ecosystem of geospatial Python libraries. Key tools include GeoPandas, Shapely and Cartopy for vector data, GDAL, Rasterio and rioxarray for raster data and participants will also learn to integrate these with popular plotting libraries such as Matplotlib, Bokeh, and Plotly to create compelling visualizations.

This tutorial will cover three primary topics: visualizing geospatial shapes, managing raster datasets, and synthesizing multiple data types into unified visual representations. Each section will incorporate data manipulation exercises to ensure attendees not only visualize but also deeply understand geospatial data.

Targeting both beginners and advanced practitioners, the workshop will employ real-world examples to guide participants through the necessary steps to produce striking and informative geospatial visualizations. By the end, attendees will be equipped with the knowledge to leverage advanced data science techniques in their geospatial projects, making them proficient in both the analysis and communication of spatial information.

**Tutorial Description**

This tutorial will give a broad overview of many of the core concepts in geospatial data visualisations. Attendees will come away with the skills needed to analyse and plot geospatial data as well as manipulate and combine geospatial datasets, generate new geospatial data from existing sources, generate insightful data maps and other geospatial data visualisations and come away from the tutorial with the confidence to seek out new datasets to apply their skills to.  When it comes to data visualisation, attendees will be encouraged to express themselves, material will be provided to get them to the point where they can generate their own visualisations without help but styling the plots will be up to them. This tutorial will provide a high-level overview of geospatial data analysis and visualisation and provide a list of open-source datasets that can be used to practice newly learned skills. Furthermore, the packages used are not all specific to geospatial data visualisation and are applicable to a wide range of scientific and data science problems. As such, it is open to everyone and hopefully beginners, intermediates and experts will all come away with a new skill or two.

Q) Notes \- These notes are meant for the organiser and won't be made public.  
A) 

**Session Image**

Rivers overlaid on a forest density map.   

![alt text](test.jpeg "Title")


**Q) Prerequisites** \- A list of prerequisite skills expected of attendees, so that participants can chose level appropriate tutorials. This content will be shown publicly.

A) The course and course materials will be hosted on Github use Jupyter notebooks, python packages will be installed through Conda hence a prerequisite knowledge of git, Jupyter and anaconda is required. This tutorial is aimed at the whole community but a familiarity with pandas and Matplotlib is essential to enable progress through the exercises. 

Q) If you used AI tools and or services to support the preparation of your submission, please state the name and reason for using each of them. If you haven't used any, please enter "No AI."

A) No AI

**Q) Installation Instructions** \-This information will be collected closer to the conference This content will be shown publicly.

A) Detailed instructions will be provided 

**Outline** \- A more detailed outline of the tutorial content, including the duration of each part and exercise sessions. Please include a description of how you plan to make the tutorial hands-on. ​

1) 30 minutes – Introduction.   
   1. This will introduce the course, the learning objectives and introduce the tutorial material.  
   2. What is geospatial data? This section of the tutorial will be lecture based. The characteristics and terminology of the different datatypes that are relevant to geospatial data science will be covered, namely, rasters, points, lines, polygons and multipolygons.  There will be a brief introduction on the different ways this data is collected and stored. There will also be a brief discussion on the different ways that geospatial data can be projected.

 **Learning outcomes:** 

* Understand the different geospatial datatypes  
* Understand the different geographic projections.  
* Understand the main geospatial file types. 


2) 5 minutes \- Break to allow course material to be downloaded.  
3) 90 minutes \- Section One \- Rasters. The first part of this task will involve IO operations on rasters as well masking, reprojection and plotting of raster data. The second part will involve advanced manipulations of raster data, namely the conversion of raster data to contours (lines), points and polygons.   
   1. Attendees will download a raster map of global forest cover to generate a global forest map   
   2. They will mask it with a polygon to produce a forest map of a country or area of their choice.   
   3. They will learn how to reproject the map to their favourite projection  
   4. They will then learn how to convert this data from a raster to points, lines and polygons. 

   **Learning outcomes:**

* Understand how to read and manipulate raster data with Rasterio and rioxarray.   
* Understand how to reproject raster data with rioxarray.   
* Understand how to convert raster data to vector data using GDAL and rasterio.   
* Understand how to plot raster data and vector with Rasterio and Matplotlib

4) 90 minutes \- Section Two \- Vector Data. The first part of this task will involve IO operations on vector data, namely river data as linestrings and river basin maps as polygons. The second part will involve advanced plotting to generate a river map with linestrings scaled according to the size of the river and coloured according to the river basin that they are part of. 

**Learning Outcomes**

* Understand how to read and manipulate polygon / linestring data.  
* Understand how to plot linestrings and polygons with GeoPandas and Matplotlib.  
* Understand how to reproject shape data using GeoPandas and Cartopy.  
    
5) 30 minutes \- Conclusions and wrap up. There will be a brief discussion around the key takeaways from the tutorial as well as possible next steps for anyone who wants to continue their geospatial journey. 

**Q) Additional Information** \- If available, the tutorial notes, slides, exercise files, and IPython notebooks, even if they are preliminary.

A) Git repo 

**Q) Prior Python Programming Level of Knowledge Expected** \- Please note this reflects the attendees' Python programming level only, not the attendees' level of understanding of the topic.

A) Beginner. A firm grasp of the fundamentals of Python are essential but no prior knowledge of geospatial is required. Geospatial concepts will be taught via the programming exercises, making this an excellent introduction to geospatial data science for beginners. 

Affiliation \- List your company, school, independent, etc.
