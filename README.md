# nasa-image-data

## Examining Visuals of 'climate change' from the NASA Image and Video Library

### This project uses the [NASA Image and Video Library](https://images.nasa.gov/) API to collect data about the keywords associated with the images in this library. The query used to select images was 'climate change', as the goal is to examine what kinds of photos are associated with this term and what other metadata surrounds these items, such as dates, descriptions, titles, and other keywords. This project includes a csv file of metadata associated with each image returned by the 'climate change' query. From there, this metadata will be used to create several graphs that illustrate the usage of different keywords over time, the quantitity of images over time, and what these images depict.

### I was initially interested in the language used to discuss climate and the environment, and began by focusing on headlines and keywords about these topics. Over time and through exploring the NASA Image and Video Library I ultimately thought it would be interesting to look at both the linguistic and visual associations with 'climate change'. The aim of this work is to consider how an organization visually and linguistically presents information on a pressing topic, and how that information has evolved over time. The NASA Image and Video Library is one example of an institution that has published information on climate change over many years, but this kind of observation could be applied to many different institutions and their work.

### Process:
### 1. I began by making a request to the API to get results related to 'climate change'.
### 2. I looped through the data and created lists of the information I wanted to include in this project.
### 3. I made a data frame out of these lists and saved it to a csv using the **pandas** library.
### 4. I used **OpenRefine** to help organize the data in a way that would be useful for making graphs and visualizations of the data (WIP).
### 5. I used **matplotlib**, **numpy**, and **Pillow** to create the graphs using data from the csv (TO DO).

### In the future this code could be used to simply access metadata from the NASA Image and Video Library API, as there is not documentation online anymore. Future uses could include using similar loops to examine different search querys, keywords, and images on the website. It could also be compared to the visual and written publications of other scientific institutions. Initially I had thought about working with headlines or other kinds of text from various sources, it could be interesting to see how the NASA Library data compares to other discussions about climate change in its titles and keywords. Through working on this project, I gained a lot of interest in the images themselves and the visual component of this data. This data could possible be used to consider how language and metadata is ascribed to images, and how this influences what kind of results appear in this and other libraries for different queries.

### File list:
### - finalproject1.ipynb
### - finalproject2.ipynb
### - nasa_data.csv
