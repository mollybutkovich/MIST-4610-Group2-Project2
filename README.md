# MIST-4610-Group2-Project2

## Team Name and Members
Sp24_61608_Group 2

1. Dylan Artis @DJA706
2. Dana Baus @Dananasplitt
3. Molly Butkovich @mollybutkovich
4. Connor Coniglio @ConnorConiglio
5. Thomas Le @thomasle123
6. Alex Quinlan @AlexQuinlan12

## Describing your dataset and what data it contains: 
The dataset contains information on meteorite landings all over the world from the years 860 to 2012. The data set is sponsored by NASA and can be found here: https://catalog.data.gov/organization/about/nasa-gov.  The dataset contains 45,717 rows and 10 columns. Each column provides invaluable information regarding each meteorite’s name, ID,  nametype, reclass, fall, year, reclat, relong, and geolocation. Six of the ten columns of data were the string datatype. Those columns included fall, geographic location, name, nametype, reclass, and year. However, the year datatype was later adjusted as explained in the manipulations sections. One of the ten columns, Id,  was the Number (whole) datatype. The remaining three of the ten columns were the Number (decimal) datatype. Those columns include mass, reclat, and relong. However, the geographical roles of the reclat and relong columns were manipulated as described in the manipulations section. 

The first column, name, describes the name of the meteorite. The second column, the ID, represents a unique identifier for each meteorite. The third column, nametype, decides whether the Name is a valid name for a meteorite. The fourth column, reclass, describes the group a meteorite is in based on its properties. The fifth column, mass (g), describes the mass of each meteorite measured in grams. The sixth column, fall, describes if the meteorite hit the ground or burnt up in the atmosphere and did not reach the ground. The seventh column, year, gives information regarding the year when the meteorite entered the Earth's atmosphere or hit Earth. The eighth column, reclat, gives the latitude of the meteorite landing, and the ninth column, reclong, gives the longitude of the meteorite landing. The tenth column combines the latitude and the longitude into one Geographic coordinate. 

Note: Row 30,684 has data containing the year as “2101.” However, we believe that the data input is incorrect. According to Google, it should say “2010.” 

## Two questions the team generated and why they are interesting and important:

**Question 1:** What are the names and locations of the meteorites with a mass greater than 20,000,000? 

  **Results:** Mundrabilla (Australia), Campo del Cielo (Argentina), Gibeon (Namibia), Hoba (Namibia), Bacubirito (Mexico), Chupaderos (Mexico), Canyon Diablo (USA, Arizona), Sikhote-Alin (Russia), Armanty (China), Cape York (Greenland)

  **Explanation:** This information is useful because we are able to use past landings to predict where the next big meteorites may land or what may be considered a danger zone for meteorites. Since we know the exact latitude and longitude of each meteorite, we can make an assumption that the bigger and more dangerous meteorites hit certain areas. This is important because it helps countries identify possible natural disasters that may be common to them. They can steer their focus toward developing security protocols and safety preparedness for when a meteorite strikes. These can include shelters with certain infrastructure, evacuation plans, and a constant flow of information about protecting yourself during a meteorite strike.

  **Analysis:** For problem 1, we tried to figure out where the big meteorites tend to land on Earth. To be classified as a big meteorite, it had to weigh more than 20 million grams in mass. By tracking the meteorites' longitude and latitude, we found that the bigger meteorites are sporadically spread across the globe, hitting every continent except for Europe and Antarctica. We can conclude two things from this visualization. First, big meteorites will rarely hit the earth as only 22 out of the 45716 meteorite strikes involved big meteorites. Second, it will be hard to predict where the next big meteorite strike will hit, but the majority of the big meteorites tend to hit North America and Africa as North America has had 3 meteorites and Africa has had 2 meteorites hit.

**Question 2:** How has the mass of all L6 meteorites changed over time from 2000 and how is it projected to change over the next 20 years from 2012?

  **Result:** Mass of the L6 meteorites appears to spike in 2002, but is forecasted to have small spikes until 2032. 

  **Explanation:** This information is useful because we can take into account the total mass of past years and predict the total mass for years to come. Studying the patterns of meteorite falls over time aids in evaluating the potential hazards of impacts on Earth. By analyzing historical trends and predicting future falls, scientists understand how often and where small celestial bodies enter Earth's atmosphere. This knowledge is crucial for devising effective strategies to minimize the risks linked to larger impact events or even to predict when we can expect precious resources to descend. These L6 meteorites are studied thoroughly in order to understand the evolution of early Earth.

  **Analysis:** For problem 2, the classification of meteorites we are looking at are classified as “L6”. By observing the total masses of L6 meteorites from 2000 through 2012, we can use the forecast ability in Tableau to predict the total mass of L6 meteorites in the next 20 years. 2000-2002 had large spikes in total mass measured by grams. In 2000, the total was 555,435 grams. 2001 decreased to 205572 grams. Although 2001 decreased from the previous year, it is still high compared to the future year and predictions. The next year is the highest total in the range 2000-2032 with an astounding 818328 grams. 2002 was the absolute maximum in total. Since then it has been hovering around 100000 grams with spikes. Our forecast starts after 2012 when it is predicted to decrease even more with spikes as total mass decreases even more.

## Manipulations applied to the data set as part of the analysis:
The data set did not require any manipulations of the functions of the columns. However, some of the datatypes within the dataset needed to be adjusted. The “Year” datatype was converted from “Number” to “Date” datatype in order for our visualizations to be shown over time. Additionally, the “Reclat'' Geographical Role needed to be switched to “Latitude,” and the “Relong” Geographical Role needed to be switched to “Longitude.” 

**Tableau Workbook:**
https://github.com/mollybutkovich/MIST-4610-Group2-Project2/blob/8446d91457759c09633219025a0d3d96654c5f93/Group%20project%202.twbx


	


