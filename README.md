# **UFOs Sightings**


### Overview of Project:
Dana have created the webpage to display UFO sightings data stored in a JavaScript array. The table data is fully dynamic and has ablility to display the data based on filter user inputted dates only. The purpose of the analysis is to further improve the functionality of existing Javascript driven dynamic webpage by adding capability to filter data by additional data points such as City, State, Country and Shape.   

### Results: 
When the website visitors first enters the site, all UFOs sighting informations is displayed. On the left hand bottom area of the site has options to further filter UFOs sighting data as shown below:  

![myimage-alt-tag](/Resources/FilterSearch.png)

The website user may enter choose to enter search filter criteria on either one or all of the fields. For example if the users is interested in the finding the UFO sightings in the California, they may enter **ca** on the text box next to Enter a State and press Enter button on keyboard. The website will return only infomation pertaining to CA. It important to enter the data in filters in lowercase only.

![myimage-alt-tag](/Resources/SearchbyState-CA.png)

### Summary:
The analysis caters to users' interest by only displaying the UFOs sighting information they have entered very quickly. The dynamic page answers users questions and curiositly quickly. However there are few major flaws to this new design as listed below
* The data each of the filter text needs to be entered on lowercase text only. If the users enters the data in uppercase (for example, CA instead of ca) will not returns any data back. 
* The data results cannot be sorted by any of the fields.

This can be resolved in future version in few of ways:
* Add a text on the top of the form directing users to enter text in the filter only in lowercase.
* Create a function to check the value entered for text fields and if it is in uppercase, display a message to enter in lowercase. 
* Convert the information entered on data to lowercase by using Javascript toLowerCase() function before adding into the filters array.
* Develop ability to sort data by using by using Javascript sort() for user chosen fields.
 