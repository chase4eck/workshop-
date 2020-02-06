# [Return to Home](https://chase4eck.github.io/workshop-/)

# Class Notes

## What is human development?
- It is development OF the people, FOR the people, and BY the people.
  - First said by Lincoln at Gettysburg.
- The focus of human development must change from income to bettering living conditions.
- Highlights the concept of choice.
- Crown jewel of human development: the HDI.
  - It is essentially a measure of human development
  -  Cannot completely measure human development though; this is not really possible
- 2 types of measures of human development: breadth measure and focus measure.
  - Focus measure is more of the descriptive factor.

## HDR 2015 Discussion
- Discussing volunteer work, family work, and jobs/employment together.
  - Also includes artistic work: contributes to social cohesion.


## Debunking Myths About the Third World
- "Who are 'we' and 'them'?"
  - 'Them' being the 3rd world countries.
- As fertility rate (or family size) increases, lifespan decreases.
  - The study done w/ the smartest students from Sweden; occurred because of preconceived notions.
- On the topic of world distribution of income, Rosling showed how the "hump" (when looking at the Asian population) travelled from entirely in poverty to mostly middle class.
  - The data also predicts that in the future, the vast majority of the population will end up in the middle.
- Child survivability is directly proportional to income.
  - Rosling then splits Africa up into its countries; they reveal how there are some countries in Africa that seek aid, while others are a vacation destination.
- A country can develop much faster if it is healthy first than if it is wealthy first.
- Rosling also splits up countries into their classes; this shows a large distribution of both low and high income/ child survivability.
- "The improvement of the world must be highly contextualized." - 14:44
  - Need more detail on a regional level.
- Gapminder: used to connect big data/ databases to visual representations for public access.


## High Resolution Global Gridded Data for Use in Population Studies
- Using non-spatial population data to transfer census data into grid-cell data
  - GRUMP uses this data along w/ satellite info to build its dataset
- There are four ‘base’ standardised 100 m tiled datasets and 30 arc-second global mosaic derivations
  - 30 arc-second global mosaic derivations = 1km datasets
- Some useful info:
  - Base dataset creation involves processing raster topography data with vector country boundary data using a Geographical Information System (GIS) and other geospatial software. Raster images consist of a grid of pixels of particular size (spatial resolution), each pixel having a discrete (x,y) location and value. Raster images are commonly used in GIS applications, where they can represent digital elevation or terrain models of the Earth’s surface (i.e., topography). Vector datasets represent data slightly differently, utilising points (or nodes), and (in turn) lines and polygons, to represent (x,y) positions in space. Vector data can be assigned attribute information where required, and are well suited to representing boundary data.
- Four 100 m resolution datasets form the basis of the archive:
  1. Topography
  2. Standardised
  3. Gridded
  4. Clipped to country coastal boundaries
  - These create a resolution of 1 km and tiles of 100 m
#### There's a lot of math and computing involved in transferring this data into grid cells that I do not understand
- Each grid can be separated into a stack of layers to better understand how the data is making up that tile
- Some examples of layers:
  - Precipitation, land-slope, nightlights, population count, population density, water, land cover
- These layers come from a multitude of data-sites
  - For example, OSM (open street map) provides the majority of info about streets, waterways, railroads, and airports
