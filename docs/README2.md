# milestone2
# milestone Project

## UX Experience
The aim in this project is to take raw data, presumably formatted as JSON, and: present it in a format thatʼs user-friendly (charts, tables, etc.), allow the user to interact with it (e.g. sort a table, narrow down to a subset of the data, etc.), and potentially derive some insight from the data.

This project will be called "Earth's Future"
Our World's Future - Lets maintain our beautiful World
Statistics and wildlife anyalictics as a guide to how we can readdress the balance and reverse climate change
resources and links to data and other websites.
Readdress the balance of population and Country / Continent and Habitat and Species and how they correlate with each other. Reverse Climate Change in theory via data correlation and achieving a balanced perspective to try to understand the real world and what can be done to achieve this in practice.

### The Cards
create a climate change dataset. Add data and graphs explaining the data focus on wildlife and world population and how it is affecting the planet. How we can analyse and understand the data to make positive decisions going forward. Sustainable cities Population Control Saving wildlife from extinction by providing and reversing their dwindling habitats Respect for wildlife and food sources Finding solutions What are the solutions Implementing the solutions for planet health

#### Earth Focus - population by country/continent and area measurement
I am creating a dynamic dashboard showcasing the data between Country / Continent and Area.
-the dashboard did not happen for me in the end. but intend to add at some stage together with an interactive map.
#### Population Levels and comparisons between countries and Continents. I want the end user to be able to choose different graphs to show the way data interacts and compares.
I am using a combination of my tutorials and libraries to create my graphs. I had selected code from #Stack Overflow to assist with colouring my barcharts.

##### Earth focus-2 scatter plot
Continent A string like 'Europe' and the Continent is the same as Country. "In the lessons when we parse the results it is either because the data has a string and we want a number or when the data is one timestamp and we want another. A scatterplot is a chart best suited to plotting two numbers against each other so try Area versus Population". As quoted by a tutor on my course. So I am demonstrating a correlation with population verses area, using a scatterplot.

#####Earth Focus - population by country/continent and area measurement
I am creating a dynamic dashboard showcasing the data between Country / Continent and Area.
(I ran out of time so did not includethis in the end).
Population Levels and comparisons between countries and Continents. I want the end user to be able to choose different graphs to show the way data interacts and compares.

I am using a combination of my tutorials and libraries to create my graphs. I had selected code from #Stack Overflow to assist with colouring my barcharts.

### Technologies Used
-Jquery to demonstrate DOM manipulation -Bootstrap Cosmos to help with styling -D3 helps bring data to life using HTML, SVG, and CSS. It allows User to create anything from an HTML table to a Pie chart, from -graphs and bar charts to geospatial maps -Make graph technologies; Crossfilter / DC / JSon
github to deploy my website; AWS Cloud9 followed by gitpod as soon as I heard thichs was available I swithced over to the gitpod platform as I found it more straight forward to use. "wget" command to retrieve data from other websites and json.

#### Types of Fields
Differences Measurements and Dimensions
There are two types of fields, dimensions and measures, based on the role they play in the data:
Measures are quantitative fields, meaning theyʼll always be of type number.
Dimensions are fields that act as labels/names/buckets/categories. They could be of any type, including number. The following can be used to tell whether a field is a measure or a dimension before becaming second nature:
i) Is it a number? If not itʼs definitely a dimension. ii) If it is: Does it represent a quantity/ can you perform some mathematical operation on it? iii) If so, itʼs a measure, if not, itʼs a dimension. For instance, a phone number contains numbers, but isnʼt really a quantity (adding/multiplying/dividing, etc. two phone numbers does not make mathematical sense).

#### Presenting the Data
D3 provides tools to generate charts out of JSON data. These charts could be tied to each other i.e. filtering on one chart affects the other charts at once (Iʼm sure youʼve seen this in the examples). The most common charts are: Tables - Self-explanatory, you can have as many measures and dimensions as you want in these. Simple bar/column charts - one dimension, one measure. Each bar/column represents an instance of the dimension field (e.g. a specific country), and its height/length is the magnitude of the measure (the countryʼs area). Scatter plots - one dimension, two measures. Each dot is an instance of the dimension field (e.g. specific country) and its horizontal and vertical position on the chart represent the magnitude of the first and second measure respectively. Donut/Pie chart - one dimension, one measure. Line graph - two measures (self-explanatory), or one dimension and one measure, where the dimension is represents values that are continuous in nature, for example time.

###  Credits
Cover page inspired by my course work in Code Institute Bckground image is a preview page from Adobe stock images (from which I have and account) My Mentor Brian Mancheria for helping me to try to understand the logistics of Java script and providing me with info to outline a project for myself -The Tutor support -The Slack Community =Thw World Data Bank for data on Population and Environement issues-Popululation Matters Data -Populataion Matters Images where indicated -DC.JS GETTING STARTED AND HOW-TO GUIDE -© 2019 GitHub, Inc. -Diff Checker: https://www.diffchecker.com/
My tutors and my Mentor Brian who has been very patient in helping me to understand java script and graphs.

### Tests
##### github-the four box cover page was not evenly distributed in two rows of two boxes as it was in gitpod; 
##### edge-social links were slightly different colours; 
##### firefox and chrome.  
##### I did not use jasmine as I did not fully understand it and also probably did not need too either on this project.  

### Bugs
#### Home Page - major bug issue 
#### unresolved
Below is the link to a home page I created but cannot deploy as somehow the links have caused issues with both my bar chart and my pie chart not rendering on the webpage.

https://8000-d2264e7f-c97d-48d2-b0ad-7b63896e9c67.ws-eu01.gitpod.io/piechart.html

 My layout is still not right but I am still working on this.  It is unresolved.  For some reason the last page on the website has become the home page.

https://8000-d2264e7f-c97d-48d2-b0ad-7b63896e9c67.ws-eu01.gitpod.io/index.html#part1graphs_btn

Another example of my home page above I am unable to deploy due to menu links - Both home pages are interactive using Jquery.

#### My social links moved to the right hand side when I deployed it in github. I am not sure quite why.

I have had considerable problems with this project and my understanding of java script and how it works.

I really hope to be able to iron these out in time hence the project being unfinished. I have not managed to resolve these issues yet. I appear to have a lack of understanding on how to manipulate information in the making of the graphs and the calculations involved. Hence I having trouble making my graphs appear and despite the console addressing issues - I was unable to resolve them. (Although, I did manage to go through the course modules ok). Since I am currently unable to master the making of my graphs and have run out of time - I have decided that I shall be submitting this project minus at least two of them. I hope that I shall be able to resolve these issues in future, as I move on in the course.

I could not make multiple colours appear in my barchart.html.
.colorAccessor(function (d) { if (d.value > 12) { return "Country"; } if (d.value > 9) { return "Continent"; } if (d.value > 6) { return "test3"; } if (d.value > 3) { return "test4"; } })

#### scatterplot.html
Could not make the graph appear with the data for measurements of area and population and dimension - country. I tried different information from different datasets (see docs folder for ideas and wireframes and datasets), but only got into strife so went back to a basic dataset example.

#### barchart2.html and dashboard
As above with scatterplot.
Cannot figure out at this stage how and where the following select menu should go in my barchart page and how it links up with the html menu and all the charts:
       
    <div class="menu" style="width:200px;">            
    <select class="dc-select-menu">
            <option value="">Select all</option>
            <option class="dc-select-option" value="Country">Country</option>
            <option class="dc-select-option" value="Population">Population</option>
            <option class="dc-select-option" value="Population">Continent</option>
            <option class="dc-select-option" value="Area">Area</option>
        </select>

         dc.selectMenu("#container_id")     
            .dimension(dim);
            .group(group);

I need to gain a better understanding of the process of creating interactive dashboards as I like them and am determined to master this situation at some point. I feel that I am close but I am just not quite grasping it and am waiting for the "lightswitch to come on". So I have since populated the site with some pretty pictures of graphs to illustrate until I am finally figure them out.

Finally I understand it is not good practice to add the script to the same page as the html.  However, since I have broken things so many times during the building of this project, I just decided to leave things where they are for now.


© 2019 GitHub, Inc.