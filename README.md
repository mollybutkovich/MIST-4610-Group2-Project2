# MIST-4610-Group2-Project2

## Team Name and Members
Sp24_61608_Group 2

1. Dylan Artis (https://github.com/DJA706)
2. Dana Baus (https://github.com/Dananasplitt)
3. Molly Butkovich (https://github.com/mollybutkovich)
4. Connor Coniglio (https://github.com/ConnorConiglio)
5. Thomas Le (https://github.com/thomasle123)
6. Alex Quinlan (https://github.com/AlexQuinlan12)

## Description of Dataset
The dataset contains information on meteorite landings all over the world from the years 860 to 2012. The data set is sponsored by NASA and can be found here: https://catalog.data.gov/organization/about/nasa-gov.  The dataset contains 45,717 rows and 10 columns. Each column provides invaluable information regarding each meteorite’s name, ID,  nametype, reclass, fall, year, reclat, relong, and geolocation. Six of the ten columns of data were the string datatype. Those columns included fall, geographic location, name, nametype, reclass, and year. However, the year datatype was later adjusted as explained in the manipulations sections. One of the ten columns, Id,  was the Number (whole) datatype. The remaining three of the ten columns were the Number (decimal) datatype. Those columns include mass, reclat, and relong. However, the geographical roles of the reclat and relong columns were manipulated as described in the manipulations section. 

The first column, name, describes the name of the meteorite. The second column, the ID, represents a unique identifier for each meteorite. The third column, nametype, decides whether the Name is a valid name for a meteorite. The fourth column, reclass, describes the group a meteorite is in based on its properties. The fifth column, mass (g), describes the mass of each meteorite measured in grams. The sixth column, fall, describes if the meteorite hit the ground or burnt up in the atmosphere and did not reach the ground. The seventh column, year, gives information regarding the year when the meteorite entered the Earth's atmosphere or hit Earth. The eighth column, reclat, gives the latitude of the meteorite landing, and the ninth column, reclong, gives the longitude of the meteorite landing. The tenth column combines the latitude and the longitude into one Geographic coordinate. 

Note: Row 30,684 has data containing the year as “2101.” However, we believe that the data input is incorrect. According to Google, it should say “2010.” 

## Question 1

**Question 1:** What are the names and locations of the meteorites with a mass greater than 20,000,000? 

  **Results:** Mundrabilla (Australia), Campo del Cielo (Argentina), Gibeon (Namibia), Hoba (Namibia), Bacubirito (Mexico), Chupaderos (Mexico), Canyon Diablo (USA, Arizona), Sikhote-Alin (Russia), Armanty (China), Cape York (Greenland)

  **Importance:** This information is useful because we are able to use past landings to predict where the next big meteorites may land or what may be considered a danger zone for meteorites. Since we know the exact latitude and longitude of each meteorite, we can make an assumption that the bigger and more dangerous meteorites hit certain areas. This is important because it helps countries identify possible natural disasters that may be common to them. They can steer their focus toward developing security protocols and safety preparedness for when a meteorite strikes. These can include shelters with certain infrastructure, evacuation plans, and a constant flow of information about protecting yourself during a meteorite strike.
![Screenshot (161)](https://github.com/mollybutkovich/MIST-4610-Group2-Project2/assets/163011335/cfed7466-c080-4693-ab8b-735f72dd8ec0)

  **Analysis:** For problem 1, we tried to figure out where the big meteorites tend to land on Earth. To be classified as a big meteorite, it had to weigh more than 20 million grams in mass. By tracking the meteorites' longitude and latitude, we found that the bigger meteorites are sporadically spread across the globe, hitting every continent except for Europe and Antarctica. We can conclude two things from this visualization. First, big meteorites will rarely hit the earth as only 22 out of the 45716 meteorite strikes involved big meteorites. Second, it will be hard to predict where the next big meteorite strike will hit, but the majority of the big meteorites tend to hit North America and Africa as North America has had 3 meteorites and Africa has had 2 meteorites hit.

## Question 2
**Question 2:** How has the mass of all L6 meteorites changed over time from 2000 and how is it projected to change over the next 20 years from 2012?

  **Results:** Mass of the L6 meteorites appears to spike in 2002, but is forecasted to have small spikes until 2032. 

  **Importance:** This information is useful because we can take into account the total mass of past years and predict the total mass for years to come. Studying the patterns of meteorite falls over time aids in evaluating the potential hazards of impacts on Earth. By analyzing historical trends and predicting future falls, scientists understand how often and where small celestial bodies enter Earth's atmosphere. This knowledge is crucial for devising effective strategies to minimize the risks linked to larger impact events or even to predict when we can expect precious resources to descend. These L6 meteorites are studied thoroughly in order to understand the evolution of early Earth.
![Screenshot (162)](https://github.com/mollybutkovich/MIST-4610-Group2-Project2/assets/163011335/aaf77428-4380-47f7-93f4-5e7b6949e9f3)

  **Analysis:** For problem 2, the classification of meteorites we are looking at are classified as “L6”. By observing the total masses of L6 meteorites from 2000 through 2012, we can use the forecast ability in Tableau to predict the total mass of L6 meteorites in the next 20 years. 2000-2002 had large spikes in total mass measured by grams. In 2000, the total was 555,435 grams. 2001 decreased to 205572 grams. Although 2001 decreased from the previous year, it is still high compared to the future year and predictions. The next year is the highest total in the range 2000-2032 with an astounding 818328 grams. 2002 was the absolute maximum in total. Since then it has been hovering around 100000 grams with spikes. Our forecast starts after 2012 when it is predicted to decrease even more with spikes as total mass decreases even more.

## Manipulations to Dataset
The data set did not require any manipulations of the functions of the columns. However, some of the datatypes within the dataset needed to be adjusted. The “Year” datatype was converted from “Number” to “Date” datatype in order for our visualizations to be shown over time. Additionally, the “Reclat'' Geographical Role needed to be switched to “Latitude,” and the “Relong” Geographical Role needed to be switched to “Longitude.” 

## Tableau Workbook
https://github.com/mollybutkovich/MIST-4610-Group2-Project2/blob/8446d91457759c09633219025a0d3d96654c5f93/Group%20project%202.twbx

## Molly Butkovich: Honors Addition
**Question 3:** What is the average mass of each Lunar class of meteorites from the years 1990 to 2012? Also, show the location of all the meteorites in the class “Lunar (feldsp. breccia)”. 

**Importance**: Lunar meteorites are rocks found on Earth that came from the Earth’s moon. The Earth’s moon has minimal protection from outside meteoroids due to it having no atmosphere to stop the meteoroids’ impact. Oftentimes, meteoroids travel into the moon at extremely fast speeds causing a collision which could lead to a Lunar rock to chipping off and exiting the moon’s gravitational pull. From there, the lunar rocks will enter orbits of nearby planets, in this case, Earth. Over time, the rocks will fall out of the Earth’s orbit and hit the ground, but it could be tens of millions of years before this instance occurs (Korotev, n.d.). The question posed is interesting because it studies the classes of meteorites that come from our very own moon. Although it is hard to forecast what time exactly the rocks will fall onto Earth, the first visualization will highlight the average masses of each Lunar class and could play a role in the classification of each individual meteorite. Additionally, Lunar meteorites will continue to be found on Earth for years to come because the moon has no atmospheric protection. In turn, scientists could continue to study these rock formations and use this information to gain further knowledge about the moon’s components. As well as gain a deeper understanding of potentially finding a future correlation between when and where a meteorite will fall. Scientists will be able to utilize this data to continuously track meteorites for years to come and possibly start to find correlations or information regarding areas of space we know less about.  
![Screenshot (163)](https://github.com/mollybutkovich/MIST-4610-Group2-Project2/assets/163011335/c4f5aa37-9942-4e2e-ad06-b5700c9cb3e4)

**Visualization 1 analysis:** This visualization shows a breakdown of the average mass of meteorites organized by their classification from the years 1990-2012. According to the line graph, the classes Lunar (basalt) and Lunar (feldsp. breccia) tend to have larger masses of meteorites, on average. This visualization also shows scientists which years certain classes had larger masses of meteorites, on average. The information could be studied for years to come to see if the Lunar classes continue to have larger masses, on average, or if it just occurred for a few years. 
![Screenshot (164)](https://github.com/mollybutkovich/MIST-4610-Group2-Project2/assets/163011335/ce5d09e1-0360-44cf-91ec-1f7ff1b9ca75)

**Visualization 2 analysis:** This visualization demonstrates the location areas of the most common Lunar meteorites, Lunar (feldsp. breccia). These meteorites are composed of the most common minerals of the crust of the Earth and the moon (Korotev, n.d.). As demonstrated by the map visualization, the meteorites tend to land in the same areas which indicates that the pieces likely broke apart as they entered the Earth’s atmosphere or upon impact. This information is beneficial because it shows scientists that Lunar meteorites will likely be lumped together in the same locations. Additionally, it demonstrates to scientists that they should search in surrounding areas when a Lunar (feldsp. breccia) is discovered.

**Tableau Packaged Workbook:**
Honors Option Workbook- https://github.com/mollybutkovich/MIST-4610-Group2-Project2/blob/main/Group%20project%202-%20Molly%20Butkovich%20Honors%20Option.twbx

**Works Cited:** 
Korotev, R. L. (n.d.). Lunar meteorites. Lunar meteorites | Some Meteorite Information. Retrieved April 28, 2024, from https://sites.wustl.edu/meteoritesite/items/lunar-meteorites/


	


