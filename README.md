# Trends in UFO Sightings in the United States (1969-2019)

The original dataset we used came from Kaggle (https://www.kaggle.com/datasets/rishidamarla/ufo-sightings-approx-100000/) and can be found in the "resources" folder as nuforc_reports.csv. There are two other files also contained in the "resources" folder:
1. geoUSA.json - used to work on our heatmaps in Tableau.
2. census_data_19702020.csv - a csv file with data on each state's indivdual population and the population of the entire USA gather from the 1970, 1980, 1990, 2000, 2010, and 2020 census reports.

#### Important Files & Folders:
* All visuals made during this project can be found in the "visuals" folder.
* All data cleaning processes can be found in the data_cleaning.ipynb file. This file also created the clean dataframe and stored is as clean_data.csv in the "output" folder. This dataframe is used for our data exploration.
* The final presentation slides can be found in the presentation_slides.pdf file.
* The analysis report write-up can be found in the analysis_report_writeup.pdf file.

#### Jupyter Notebooks used to answer our project questions:
* sightings.ipynb contains all of the code and visuals made to answer our first question for this project: How often do sightings occur at certain times of day or in the year?
* Sighting_vs_State_bar.ipynb contains all of the code and visuals made to answer our second question: Where do most sightings occur? Is it correlated to population size?
* shapes_and_states.ipynb contains all of the code and visuals made to answer our third question: Are certain shapes sighted more in certain locations?
* sightings_over_time-Chart.ipynb contains all of the code and visuals made to answer our fourth and final question: Have sightings increased or decreased over time?

#### In the "output" folder, you will also find the following:
1. shape_stats.csv - created in the shapes_and_states.ipynb file for use in the heatmaps made in Tableau. It shows each state's abbreviation along with is most sighted, second most sighted, and third most sighted UFO shape.
2. sightings_by_hundthous.csv - created in the Sighting_vs_State_bar.ipynb file for use in the heatmaps made in Tableau. It shows each state's abbreviation along with the total number of sightings in the state, the average population of the state over the 50 year time period, and the number of sightings per hundred thousand residents for each state.
3. sightings_by_state.csv - also created in the Sighting_vs_State_bar.ipynb file for use in the heatmaps made in Tableau. This csv file contains only the state's abbreviation and the total number of sightings in the state.

#### Finally, there is a file named sightings_vs_state_heatmaplink.txt file containing the link to the public page for the Tableau worksheets. There are five screenshots, one for each worksheet from Tableau, in the "visuals" folder as well:
1. sightings_per_state_map.png - Worksheet 1
2. sightings_per_hundthous_state_map.png - Worksheet 2
3. most_common_shape_map.png - Worksheet 3
4. second_common_shape_map.png - Worksheet 4
5. third_common_shape_map.png - Worksheet 5
