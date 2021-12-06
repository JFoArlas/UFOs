# Overview
The purpose of this project was to create a webpage with a dynamic table of UFO sightings that allows users to filter for multiple criteria and view UFO sighting results that match their search parameters.

# Results
To use the page, a user may input any of the below search paramaters to filter for UFO sightings matching the desired critera:

![image1](https://github.com/JFoArlas/UFOs/blob/main/images/filter_search.png)

By default, all of the available UFO sighting data is present on the page. So entering search criteria removes any UFO sighting results that do not match the user's input. The first 3 default results on the page are as follows:

![image2](https://github.com/JFoArlas/UFOs/blob/main/images/default_top_3_results.png)

For example, if the user enters "ar" in the State filter then only sightings in Arkansas will be left. As you can see below, the "ca" results from the default data are gone and only UFO sightings in Arkansas remain:

![image3](https://github.com/JFoArlas/UFOs/blob/main/images/ar_results.png)

To return to the default results, the user must remove the search criteria and select 'enter'.

# Summary
One drawback of the design is that the user has to manually clear the search criteria they entered to reset the data. A reccomendation for future development would be to create a reset button that would clear the search criteria and reset the results to the default data to save the user time. This would be particualrly helpful if the user entered multiple search criteria and wanted to do other searches with different criteria. They could be required to delete information from up to 5 separate boxes before starting a new search.

Another reccomendation for further development would be to add a filter to allow the user to seach for keywords within the 'Comments' column. You could additionally add a dropdown of available options in the 'Shape' column because it's hard for a user to know what all the shape options are without scrolling through all the default data.
