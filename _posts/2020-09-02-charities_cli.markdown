---
layout: post
title:      "Charities CLI"
date:       2020-09-02 03:59:19 -0400
permalink:  charities_cli
---


<p>My Command Line Interface (CLI) project is based on Charities in certain zipcodes.  This project really showed the relationships between objects and methods and how methods are chained together in order to give the CLI program direction of actions. The project also gave us the experience of using and IDE (Locally) and creating files in the bin folder and lib folder.  In the bin folder, we are set with a setup and console file via a bundle install while starting the project.  But, in order to "run" or "execute" any project, we had to create an executable file which is the file that allows us to run a program.</p>  

<p>Afterwards, in the lib folder I created an environment file which helps ties in three other files that I created as, API, Charity, and and CLI files.  in otherwords, the environment file helps the three files be able to communicate with each other so that I can call various methods and objects created within the three files. For the API file I used an API provided by a site called Orghunter.com to retrieve data to the user of the charities in the zipcode chosen. The purpose of the API file is to help retrieve data, that I have chosen, remotely in which I call to use in order to provide information of charities in the zipcode provided by the user in the begining of the CLI experience.  The next file is the Charity file which initializes and creates objects to display via data provided by the API file.  Last but most importantly, the CLI file interacts with the user by greeting the user, then asking for a zip code. This file tells the program to take user input and then based off the data given by the API, return various organizations that exist in said zipcode. After the program returns the organizations, I have it so it prompts the user to choose the organization that they wanted to learn more about by choosing the number via the index provided next to the designated organization.  When a organization was chosen, the prgram provides the URL given by Orghunter.com and the program ends.</p>

<p>My experience on this project was heavily impacted by the lack of reseources provided for charity APIs. It was not easy finding an API that retrieved charities via zipcodes like I wanted. I did come in to this project expecting to find a working API for charities easily because I had this perception that there would be many APIs for charities so that there would be many ways to access said charities in order to contribute to causes that someone may want to research. Maybe in the future the oppurtunity to create more APIs concerning charities would arise, it would just mean more exposure to any charity in said APIs.  Overall, the project has helped me see the relationships and potential that CLI has in programming and I was very excited to see it in the works as I finished.</p>



