<h1>User Manual (docs/user.md)</h1>


<h2>Overview of Website</h2> 
The Farmer's Market in Prince George's County website is designated as an online space for the residents of PG county Maryland to locate the nearby farmers’ markets. The stakeholders of the website include vendors and sponsors of the farmers market. These people are indirectly impacted by the information we display on the website as our website may increase traffic at specific markets by promoting it and giving customers an overview of the market before they visit it. Ultimately, it is our team’s goal is to bring awareness to the fresh foods located in the county. 
Interface and User Tasks 
When a user enters our system, they are presented with a home page, about tab, services tab, and help tab. Each tab was designed to help the user navigate the site and find the appropriate information. Users should use our website to educate themselves on which farmers market is near to them. This allows users to support the local businesses in PG county, but it also allows users to view what fresh foods are available nearby. When interacting on our user interface, users can use the map to see the addresses of the different farmer’s markets, visit the websites of the different farmers’ markets, and learn about the importance of fresh foods in PG county. 
An overview of each webpage and its function: 
Home Page 
An introduction to the Prince Georges County Farmers' Market Website with a statement of the different actions a user can perform on our platform 
About Tab
The About page gives an overview of the purpose of the website and background information about the Doctor’s hospital. 
Services Tab
The Services Tab offers information about the Farmers’ markets. It lists the name of the market, the markets’ website, and has an interactive map for users to see the location of the market within the county. 
 Help Tab 
The Help Tab is a page to aid developers that may want too added to our project. The page tells developers about our technology stack and our team members. 
 






<h1>README.md (top part of your README.md)</h1>


<h2>Description of the Project</h2>  
Our application is called Farmers Markets in Prince George’s County, Maryland. The website organizes, presents, and delivers information about local farmers’ markets in PG County for residents that are interested in going to a farmers market to get fresh foods. Some farmers’ markets do not effectively communicate with the public and have limited updates on their webpage.  Our group decided to solve this information problem by providing information about all farmers’ markets in the county on one website. 
The team gathered resources from PG County’s Open Data API on farmers’ markets and pulled the information from the API to display farmers markets’ locations with a live Google Map. The application comes equipped with a home page, an about page, a service page, and a help page. Users will be welcomed with a home page when they first enter our website. On the home page, users will get a brief description of the goal of the website. The about page tells users more about our application and the services we provide. The service page, where the main actions take place, composes of the list of farmers’ markets, their websites, and their Google Map location. While our application is intuitive, easy-to-use,  and has passed usability tests, we offer users instructions on how to use our application on the help page. The application is optimized for all the popular desktop browsers, including Chrome, Edge, Firefox, IE, Safari, and mobile browsers, such as Android browsers and iOS Safari. Below, are the links to access our site and key manuals. 

Link to the Farmers Market In Prince George's County website: 
Compassionate-kepler-215836.netlify.com

Link to the Farmers Market In Prince George's County User Manual :
Add URL Here 

Link to the Farmers Market In Prince George's County Developers Manual :
Add Url here 
Developer Manual (bottom half of your README.md)


<h2>Information for Future Developers</h2>  
Since our application is a simple website there will be no dependencies the user has to install. All the frameworks and javascript libraries are linked within the HTML documents. The team utilized Bootstrap’s CDN, which is a free content delivery network. Bootstrap CDN makes it so that our users do not have to download Bootstrap’s source files. The website also uses Greensock’s Javascript library. This allows us to create the overlay effect and make the text flow in upon loading the site. We implemented this by linking to Greensocks CDN within the HTML document.
Front-End Information 
Overall, the website functions fine. At surface level, there does not appear to be any bugs or resizability issues. Although, as technology evolves and new mobile devices come out with different screen sizes. It potentially could affect the resizability of the site and cause things to break. Future developers working on the site should look to maintain it by keeping it updated to modern website scalability. 
Back-End Information 
	Back to the point of our application being a simple website, there is no need to download any dependencies. Everything that you need to access and utilize the website should already be downloaded on the platform that is being used to access the website. The website was deployed to Netlify, which is a cloud computing company that offers hosting and serverless backend services for static websites. After completing the frontend and backend code, the GitHub repository was linked to the Netlify platform, Netlify was able to offer hosting for the code that was developed. A server was needed for the website due to the data that was being Fetched using the PG County Open Data API. When fetching data, there is data that is being sent and recieved. For the case of the website that was developed, the data that was being shown on the site was gathered by sending requests to another API, this was the fetch. The fetch was successful and gathered all the data that was requested and stored it on the server that Netlify deployed. 
	Since our application was a simple website, there was no need for writing any test cases. All the improper styling, formatting, and broken links were found by completing a UX Evaluation. The UX Evaluation resulted in findings of different color schemes, but also helped us find out that the navigation bar wasn’t functioning properly. The navigation bar contained buttons that allowed users to explore different pages on the website, but there were buttons that were leading to the incorrect page.
The data that is being fetched from the PG County Open Data API was retrieved by using GET endpoint and was formatted and POSTed to our application. The GET endpoint referred to the .json file which contained all the data on the Open Data website, the data was picked up from the .json file and was then mapped out. A variable was associated with the data that we needed to pull from the JSON file. After the data was picked up from the Open Data JSON file, the data was then formatted to match the formatting of our application. The only known bugs that we are facing right now is the layout of the “Services” page. The table is properly showing the name of the market and the websites that are associated with the map but, there are some links to these markets which are broken, due to the the market not supplying a valid URL. The Map that was embedded in the application has some issues with sizing and layout. The map does not fit the right half of the page perfectly.


<h2>Final Report (docs/final.md)</h2> 
The Dynamic Web Applications class at the University of Maryland in Fall 2019, was tasked with solving an information problem in Prince Geoge’s County Maryland. Our team decided to create a one-stop hub website where residents in the county could find all their local farmers’ markets by using the SODA API supplied on Prince George’s County Open Data. The creators of the website and tacklers of the information problem are Clarence Fernandes, Hilary Zhang, Yeeun Kang, Rohan Saxena, Janell Coleman, and Neel Shah. The curated website can be found at the following URL: Compassionate-kepler-215836.netlify.com Each team member had a unique role in the final reveal of the website as the roles ranged from technical to non-technical roles. This report gives an overview of the final product, explains the team’s process in creating the site, and offers recommendations on how the final product could be built upon and approved in the future. 
 
The team desired to solve the information problem surrounding farmers’ markets in Prince Georg’s County, Maryland for significant reasons. There are numerous farmers located throughout the county, but there is not a resource available that offers information about each market on one website and gives the demographic breakdown of the county which supports why it's important to bring awareness to the farmers’ markets. Prince George’s County demographic is composed of mostly minorities. Because of this, the team wants to promote healthy and fresh foods located in the county. While the website does not solve the other problems revolving around food insecurity and unhealthy eating habits such as low-income, lack of transportation, and a lack of knowledge, it is our goal that the website will make people aware of the fresh food options located in the county and potentially slightly increase the number of fresh foods people and visitors of the county consume and promote the small vendors at the farmers market. 
 
The target audience of this website is residents and visitors of  PG county that want to explore the different farmers’ markets. Prince George’s County Farmers Market website offers more than a traditional Google search as the content is made specifically for people in PG county and serves as a single source of information.  We aim to promote healthy food options located in the county to the residents and visitors of the county. Additionally, our stakeholders are vendors at the farmers market as they will receive a direct promotion to potential customers from our site. In addition to promoting healthy foods, our site promotes some of the small businesses in the county. This website is unique as it is specifically for a small suburb in Maryland. 
 
<h2>Technical System</h2>  
Technical system decision rationale
How/if your final system helps to address the problem
Challenges faced and impact on final design: problems with filtering information by the season 
 
 
 
<h2>Future Recommendations</h2>  
	The Prince Georges County Farmers Market website is a solid foundation for bringing awareness to the healthy foods located in Prince George's County while promoting small businesses. The strong foundation built from this website allows for numerous projects to be built off of what we started. Going forward, it is recommended that developers add a filtering feature to the website. Filtering will allow users to find out what products the farmer’s markets’ offer, if they accept government food assistance payment, and what seasons the markets are open. This will give users an abundance of information to help users make decisions about which farmers market is appropriate for them. Closing sentence 
 
 
 
<h2>Information problem you're trying to solve</h2> 
Identified stakeholders/target browsers
Data you chose to work with
Chosen strategies and solutions for the problem
Technical system decision rationale
How/if your final system helps to address the problem
Challenges faced and impact on final design
Possible future work directions with this problem




.

