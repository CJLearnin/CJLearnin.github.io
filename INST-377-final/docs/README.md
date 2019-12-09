<h1>README.md </h1>


<h2>Description of the Project</h2>  
	Our application is named Farmers Markets in Prince George’s County, Maryland. The website organizes, presents, and delivers information about local farmer’s markets in PG County for residents that are interested in going to a farmers market to get fresh foods. Some farmers’ markets do not effectively communicate with the public and have limited updates on their webpage. Our group decided to solve this information problem by providing information about all farmers’ markets in the county on one website.  
The team gathered resources from PG County’s Open Data API on farmers’ markets and pulled the information from the API to display farmers markets’ locations with a live Google Map. The application comes equipped with a home page, an about page, a service page, and a help page. Users will be welcomed with a home page when they first enter our website. On the home page, users will get a brief description of the goal of the website. The about page tells users more about our application and the services we provide. The service page, where the main action takes place, is composed of the list of farmer’s markets, their websites, and their Google Map location. While our application is intuitive, easy-to-use,  and has passed usability tests, we offer users instructions on how to use our application on the help page. The application is optimized for all the popular desktop browsers, including Chrome, Edge, Firefox, IE, Safari, and mobile browsers, such as Android browsers and iOS Safari. Below, are the links to access our site and key manuals. 

Link to the Farmers Market In Prince George's County website: 
Compassionate-kepler-215836.netlify.com

Link to the Farmers Market In Prince George's County User Manual :
https://github.com/CJLearnin/CJLearnin.github.io/blob/master/INST-377-final/docs/user.md

Link to the Farmers Market In Prince George's County Developers Manual :
https://github.com/CJLearnin/CJLearnin.github.io/blob/master/INST-377-final/docs/Developer_Manual.md

Link to final report:

https://github.com/CJLearnin/CJLearnin.github.io/blob/master/INST-377-final/docs/final.md

<h1> Developers Manual </h1>

<h2> Information for Future Developers </h2>

Since our application is a simple website, there will be no dependencies the user has to install. All the frameworks and javascript libraries are linked within the HTML documents. The team utilized Bootstrap’s CDN, which is a free content delivery network. Bootstrap CDN makes it so that our users do not have to download Bootstrap’s source files. The website also uses Greensock’s Javascript library. This allows us to create the overlay effect and make the text flow in upon loading the site. We implemented this by linking to Greensocks CDN within the HTML document.
 
<h2> Front-End Information </h2>
Overall, the website functions fine. At surface level, there does not appear to be any bugs or resizability issues. Although, as technology evolves and new mobile devices come out with different screen sizes. It potentially could affect the resizability of the site and cause things to break. Future developers working on the site should look to maintain it by keeping it updated to modern website scalability.

<h2> Back-End Information </h2>
Because of our optimized design, users do not need to download any dependencies to get our website to function. Everything that a user needs to access and utilize the website is already downloaded on the platform that is being used to access the website. The website was deployed to Netlify, which is a cloud computing company that offers hosting and serverless backend services for static websites. After completing the frontend and backend code, the GitHub repository was linked to the Netlify platform, Netlify was able to offer to host for the code that was developed. A server was needed for the website due to the data that was being fetched using the PG County Open Data API. When fetching data, there is data that is being sent and received. For the case of the website that was developed, the data that was being shown on the site was gathered by sending requests to another API, this was the fetch. The fetch was successful and gathered all the data that was requested and stored it on the server that Netlify deployed. 

The data that is being fetched from the PG County Open Data API was retrieved by using the GET endpoint and was formatted and POSTed to our application. The GET endpoint referred to the .json file which contained all the data on the Open Data website; the data was picked up from the .json file and was then mapped out. A variable was associated with the data that we needed to pull from the JSON file. After the data was picked up from the Open Data JSON file, the data was then formatted to match the formatting of our application. The only known bugs that we are facing right now is the layout of the “Services” page. The table is properly showing the name of the market and the websites that are associated with the map, but there are some links to these markets which are broken, due to the market not supplying a valid URL. The map that was embedded in the application has some issues with sizing and layout. The map does not fit the right half of the page ideally. 

Since our application was a simple website, there was no need for writing any test cases. All the improper styling, formatting, and broken links were found by completing a UX Evaluation. The UX Evaluation resulted in findings of different color schemes, but also helped us find out that the navigation bar wasn’t functioning properly. The navigation bar contained buttons that allowed users to explore different pages on the website, but there were buttons that were leading to the incorrect page.
