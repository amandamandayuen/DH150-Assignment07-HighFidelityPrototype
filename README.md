# DH150-Assignment07-HighFidelityPrototype
### by Amanda Ruan

# Summary of the project
- This project aims to provide COVID-19 information updated by the government, including cases tracking map, updated guidance and news, and Q&A session to both provide frequently asked questions and assist individual needs. Modifying existing government and organization-based mobile applications on COVID-19, this project aims to fill in the gaps that previous apps did not achieve and provide an assessible environment for the public to easily access COVID-19 information. 
- The purpose of this prototyping is to create a high-fidelity model of the app and to see how users could possibly interact with the model to achieve their needs and the potential problems users encounter while interacting with the model. Based on previously developed personas and tasks, this high-fidelity model has three main goals to achieve: 1) an interactive map page that allows users to look at the spread of COVID-19 by map and the cases, 2) a resources page that allows users to look for government guidance and updates related to a variety topics, 3) a Q&A page that allows users to get more information about COVID-19 and get help with their individual needs. 
- During the prototyping process, I first used Figma to create the three main wireframes based on paper drafts, then I elaborated and added more wireframes around the three main wireframes to simulate the activities users need to complete. 

# Tasks Supported by the Iteractive Prototype:
-	Access neighborhood-level COVID-19 cases information on the map
-	Customize/Filter viewing cases options on the map
-	Access COVID-19 testing booths information using both map and resource tools
-	Access government guidance on restaurant services
-	View, search for, and submit mental health related questions using the Q&A tool
-	Search by keywords
-	Search by microphone input

# Example Screen Design and Wireflows:
### 1. Example Screen Design:
The first line are examples of the three main screens 1)__Map__, 2)__Resources__, 3)__Q&A__. The bottom line are the examples of each main screen's sub screen.
![screen design](https://github.com/amandamandayuen/DH150-Assignment07-HighFidelityPrototype/blob/master/Example%20frames.png)
### 2. Wireflow for all interactions:
The frames that are highter than the rest of thier frame groups are the main screen of each feature
![wireflow all](https://github.com/amandamandayuen/DH150-Assignment07-HighFidelityPrototype/blob/master/Wireflow%20All.png)
### 3. Wireflow for Task 1: Look for Active Confirmed Cases (Map Tool)
![w1](https://github.com/amandamandayuen/DH150-Assignment07-HighFidelityPrototype/blob/master/Wireflow%201.png)
### 4. Wireflow for Task 2: Look for Testing Booths Information and Food Delivery Guidance (Resources Tool)
![w2](https://github.com/amandamandayuen/DH150-Assignment07-HighFidelityPrototype/blob/master/Wireflow%202.png)
### 5. Wireflow for Task 3: Look for Mental Health Call Line and Submit a Question (Q&A Tool)
![w3](https://github.com/amandamandayuen/DH150-Assignment07-HighFidelityPrototype/blob/master/Wireflow%203.png)

# Wireflows and Prototypes

### Link to Wireflows (Wireframe 2.0): 
https://www.figma.com/file/tT7DfvhYQKOVcNCD0sJYDX/DH150-AMANDA-RUAN?node-id=0%3A1

### Link to the Interactive Prototype (Wireframe 2.0): 
https://www.figma.com/proto/tT7DfvhYQKOVcNCD0sJYDX/DH150-AMANDA-RUAN?node-id=1%3A2&scaling=scale-down

# Graphic Interface Design and Accessibility Testing:
- I chose the main color scheme based on the COVID-19 apps and websites I have explored, including CDC app, Apple app and CDC website. The main color scheme of the app was based on CDC website and app, using the colors grey, blue, purple, and green, which are also frequently used color combinations by the other health apps and websites. The color choices of the filter buttons in the navigation bar on map tool were adopted from the map tool on COVID-19Tracker app, as I tried to use the colors that are both visually contrasting and consistent. To meet the WCAG 2.00 AA level requirements, I used Chrome’s developer Audit tool to check the color contrast of the prototype, and the Audit report suggests that the color combinations meet sufficient contrast ratio. 
![audit](https://github.com/amandamandayuen/DH150-Assignment07-HighFidelityPrototype/blob/master/Audit%20Result%20for%20Color.png)

# Inclass and Outside of Class Impression Test
Besides the in-class impression test with my first version of the prototype with my classmates, I also conducted an impression test outside of the class with a second revised version of the prototype with one of my friends, who also did not know about my project before. In summary, the main feedback from the in-class impression test was on the Resources page as my peers were a little bit confused whether the guidance information is listed by location, and they also wonder what could be done with the filter button. In addition, one classmate also mentioned that the ‘View More’ link was not consistent with other buttons and was not obvious. Another suggestion was on the phrasing of the buttons on my Q&A page as my classmates were confused about what they could do with those buttons. Based on the revised version, the main problem I had was with the Map tool, as the circles that covering the map areas first confused my friend. Another major problem I have was on the line spacing of the text, as the text was dense. Some of the quotes from my peers were listed below:
#### With the first version:
-	“We can access COVID19 information through this app”
-	“(with the Map tool)… we can check how dense the spread is…(with the Q&A tool)… we can communicate with someone else… and there’s also a resources page…”
-	“Are the announcements (on the Resources page) listed by location?”
-	“I really like your color choices and the layout looks symmetrical”
-	“I’m confused about the live chat and submit button (on the Q&A page), what’s the differences between the two? And also by naming it ‘submit’, it gives an impression that you already finished typing the questions”
#### With the second version:
-	“Why the circles are purple when I first enter the Map page?”
-	“(Map page) Why there are two circles here? If that indicates the area around you, shouldn’t there be only one circle?”
-	“(Map page) Three circles are confusing”
-	“(Resources page) maybe the colors of the two top sections are too close to the second sections”
-	“(Q&A page) you can lower the ‘View More’ button, now it’s too close to the main text body”
-	“(Resources page on testing booths) Maybe you want a division line here to separate the two parts”
-	“(Resources page on food services) The text is a little bit dense here, maybe you can increase the line spacing, so it’s more readable”
-	“Why couldn’t I go back from here? I wanna tap on the bottom buttons”
-	“The colors are good. I like your submission page!”

# Cognitive Walkthrough and Summary for Revision
### Video link to one cognitive walkthrough process: 
https://youtu.be/fL9H21XsEjg
### Summary:
I tested the second revised version of the full prototype with two of my friends and screen-recorded one of the walkthroughs as evidence. The cognitive walkthrough gives me valuable feedback on how I should modify certain features to make the interface more accessible to users when they are actually interacting with the system. 
- 1) For instance, I noticed that both of them tried to press the buttons on the bottom TAP BAR to go back to the main pages, while I only enabled interactions of the bottom TAP BAR on the three main pages MAP, RESOURCES, and Q&A. Therefore, I need to add more interactions to the other pages to make the whole process goes more smoothly. 
- 2) Moreover, they also said that the feedback given by the filter button on the NAVIGATION BAR on MAP page was not immediate. One of my friends expected immediate change of the view on the map when she clicked on one of the filters, but she did not see any change and got confused. The other friend suggested that if I don’t give immediate feedback, I could add an “apply” button under the filter bar to allow users to know they should click on “apply” before seeing any change on the map.
- 3) The circles and filters on the MAP page still led to confusion. It might be clearer if I only show one circle at a time or revise the instruction to allow the page makes more sense. For instance, I could say that the default circles are “Cumulative Confirmed” cases and represented neighborhood-level data. I could also include more scale of data available under the filter button, such as cities, states, and nations. 
- 4) Under Q&A page, I attached one of the “frequently asked question” section on top as the search result of “Mental Health”, the section did not mention mental health in the title and created confusion to my friend as she expected to see the words “Mental Health” as the first searching results. I need to revise the orders of the sections listed on the result page to stick the most relevant section names at top.

# Revision:
Based on feedbacks from both impression tests and cognitive walkthrough, I made a third revision on the prototype to solve the problems I listed above. 

### Link to revision wireflows (Wireframe 3.0): 
https://www.figma.com/file/tT7DfvhYQKOVcNCD0sJYDX/DH150-AMANDA-RUAN?node-id=152%3A0

### Link to revision interactive prototype (Wireframe 3.0):
https://www.figma.com/proto/tT7DfvhYQKOVcNCD0sJYDX/DH150-AMANDA-RUAN?node-id=152%3A1910&scaling=scale-down

# Reflection:




