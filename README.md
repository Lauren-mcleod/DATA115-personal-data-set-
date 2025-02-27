**Shark Attack Data**

**Motivation**
  
  My motivation for investigating shark attack data was to dive deeper into the location and activities performed when people are attacked by sharks. Sharks play a vital role in the ocean and are often misrepresented in media. I found this topic interesting and had potential for a variety of research questions. I narrowed down my focus to the activity shark attack victims were doing when attacked.
  
 **Data sources**
 
 The raw data came from the [Global Shark Attack File](http://www.sharkattackfile.net/incidentlog.htm). The GSAF is an organization providing an excel document with the details of reported shark attacks. This includes the location, activity, type of shark, and the injuries from the attack. The raw data comes from the The Global Shark Attack File's field reporters spread all over the globe gathering data. Additionally, anyone can contact them to report an attack, which the organization will investigate and verify the information before adding it to their data. 
 
 **Processing Steps**
 
Since the raw data provided was already in a well organized pivot table in excel in the file shark-attacks.first.file, all of my processing was removing data that did not directly relate to my main focus. Initially when processing the data I discovered there isn't a true definition of an attack. I decided for my project to define a shark attack as the victim having an injury. This lead me to remove the reports of kayaks being bumped by a shark swimming by or attacks that were post mortum. The next step in processing the data is I narrowed down the information provided about every attack. Since my project is mainly focused on activity, I removed the Name, Age, Species of Shark, Time and Investigator columns. 

**Visualization**

After narrowing down the information, I made a bar chart showing the activities victims were doing when attacked by a Shark. The most common 20 activities reported are represented as a bar. 


![International activies done when getting attacked by Sharks](https://raw.githubusercontent.com/Lauren-mcleod/DATA115-personal-data-set-/master/activityplot2.png)

This figure shows the activities shark attack victims across the globe were doing at the time they were attacked. By far the most attacks happen while the victim is surfing, followed by swimming. The activity with the least attacks is wind surfing. 

**Analysis**

Now knowing that globally the most shark attacks take place while someone is surfing. I decided to make a heatmap showing acitivity and whether the attack was provoked or unprovoked.

![Provoked vs. Unprovoked](https://github.com/Lauren-mcleod/DATA115-personal-data-set-/blob/master/provoked_unprovokedhm.png)

The heat map clearly shows that no matter where you are in the globe you are most likely to be attacked unprovoked while surfing. 
