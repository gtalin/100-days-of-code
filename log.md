# 100 Days Of Code - Log

### Day 1: January 3, 2017

**Today's Progress**: Got started with fcc "Visualize Data with a Bar Chart" assignment.

**Thoughts:** Had quite some trouble getting started with D3. Had looked at D3 a couple of months back for the first time (seemed like I had forgotten most of it). Since did not have a link for the D3 project I was working on, I solved a problem on codewars. Including the link for that instead.

**Link to work:** [codewars] (https://github.com/gtalin/CodeWars)

### Day 2: January 4, 2017

**Today's Progress**: Worked on fcc "Visualize Data with a Bar Chart" assignment.

**Thoughts:** Had some trouble trying to fit the bars in the space. Till I did not divide gdp by a factor, all I got was a square of vertical lines becuase the graph was being cut off from the top. Took a lot of time in figuring out what was wrong. Need to add axis and tool-tip when we hover.

**Link to work:** [BarChart] (https://github.com/gtalin/Data-Visualization)

### Day 3: January 5, 2017

**Today's Progress**: Worked on fcc "Visualize Data with a Bar Chart" assignment.

**Thoughts:** Adding of axis was tougher than I thought. The y-axis was getting cut off even when I added some margin. Spent a lot of time figuring it out. Adding and aligning the axis with the chart was tough. Since I hadn't made much progress in the barchart problem I did not push the barchart code. Instead I did a simple codewars kata just so I would be pushing some code to github.

**Link to work:** [codewars] (https://github.com/gtalin/CodeWars)

### Day 4: January 6, 2017

**Today's Progress**: Worked on fcc "Visualize Data with a Bar Chart" assignment.

**Thoughts:** Was able to display axis (with labels). Trick is to set a margin for svg (Done done by css but by coding it in JS) We set a left, right, top and bottom margin. We modify the w and h values (subtract margins), set svg at the width and height of unmodified w and h values. Append "g" to svg and use transform translate so that the actual (inner) graph's (0,0) starts so hat there is a left margin and bottom margin. A great link which helped with setting margin so we can add axis: [Margin graph D3] (https://bost.ocks.org/mike/bar/3/)
Better understood scale domain and range as well. On day 2 I thought the graph was cutting off becuase I needed to divide the gdp data with a factor. I thought we were pre-processing data like we do in R sometimes (Confused it a bit with normalization. Though in normalization is different. But sometimes in R we do preprocess data) But that was not needed here because here the whole scale, domain and range does that. And then we can simply use say heightScale(gdpVal) to see what that value of gdp would be in our new scale. A good link which clears up domain, range and scale is: [Domain, Range, Scale] (http://javascript.tutorialhorizon.com/2015/01/17/d3-fundamentals-understanding-domain-range-and-scales-in-d3js/)
Made svg pink to see how much free area I have for adding labels.

**Link to work:** [BarChart] (https://github.com/gtalin/Data-Visualization)

### Day 5: January 7, 2017

**Today's Progress**: Parallax Scrolling

**Thoughts:** Worked on HTML and CSS. Did parallax scrolling and added text over image. Selected some nice images under creative commons license, selected some quotes I like and added them all to make a simple page.

**Link to work:** [parallax] (https://github.com/gtalin/tipsNtricks)

### Day 6: January 8, 2017

**Today's Progress**: 2 codewars kata.

**Thoughts:** Something is better than nothing.

**Link to work:** [codewars] (https://github.com/gtalin/CodeWars)

### Day 7: January 9, 2017

**Today's Progress**: Codewars: implementing an array object without using arrays.

**Thoughts:** Further broadened my understanding of this, prototype chain. It was a good exercise.

**Link to work:** [codewars] (https://github.com/gtalin/CodeWars)

### Day 8: January 10, 2017

**Today's Progress**: Read up on node (express) in preparation for a project I have in mind. Two great resources [crud] (https://zellwk.com/blog/crud-express-mongodb/) and [Daniel Shiffman API in Node] (https://www.youtube.com/watch?v=P-Upi9TMrBk&t=156s) Did codewars kata. 

**Thoughts:** Have several questions in my mind. Specially need to find ways to transfer data from server.js to client js script without using a template engine (in the blog link above, ejs has been used.) What I want is to transfer data to client js and do dom manipulation from client js.

**Link to work:** [codewars] (https://github.com/gtalin/CodeWars)

### Day 9: January 11, 2017

**Today's Progress**: Made an analog clock.

**Thoughts:** It was a good exercise in CSS. Got to use: transform-origin, transform, transition, absolute and relative positioning. Used setInterval to animate (probably could've also used requestAnimationFrame)
Encountered an error where the seconds hand spins in the opposite direction to get back to it's starting position (In my case it was 3). When I removed the line: transition: all .5s The error was rectified. Though I am not quite sure why this removed the error. Can work more on the beautification of the clock.

**Link to work:** [Analog Clock] (https://github.com/gtalin/tipsNtricks) Codepen link: [Analog Clock] (http://codepen.io/gtalin/pen/ZLQNZK)


### Day 11: January 13, 2017

**Today's Progress**: Read up on CSS. One kata in codewars

**Thoughts:** Spent quite a lot of time reading up on CSS: creating background with radial gradient and linear gradient. How box-shadow and pseudo elements: ::after and ::before can be used to create shapes. 
In the kata I made several mistakes by neglecting few things. Main being we had to sort the data before scaling which I did. But we had to sort on 2 variables (the value and the key) which I didn't. 

**Link to work:** [codewars] (https://github.com/gtalin/CodeWars)

### Day 12: January 14, 2017

**Today's Progress**: Trees based kata codewars.

**Thoughts:** Didn't have much time today. Attempted a problem finding paths in tree on codewars.

**Link to work:** [codewars] (https://github.com/gtalin/CodeWars)

### Day 13: January 15, 2017

**Today's Progress**: Worked on CSS. Halfway through making a Koala face with CSS. 

**Thoughts:** A lot of shapes are possible in CSS with border-radius. We can add light effect by adding a shade of a lighter color in a darker color (eyes). Need yet to give depth perception to ears by adding shadow. Linear-gradient and radial-gradient can be used to produce a glossy effect (did not use it in this project yet)

**Link to work:** [CSS Animal] (https://github.com/gtalin/tipsNtricks) on [codepen] (http://codepen.io/gtalin/pen/MJjbyx)

### Day 14: January 16, 2017

**Today's Progress**: Koala face with CSS. 

**Thoughts:** Used pseudo element ::after and :: before along with box-shadow to make the hair of the Koala. Had made ear with border feature (to give it two colors: background color and border color) instead used ::after to remake the ear.
Shadow inside ear to give it a depth (By box-shadow) and lighter patch on nose to give it a little shine (using ::after pseudo element and transform to rotate it)
Used radial gradient above.

**Link to work:** [CSS Animal] (https://github.com/gtalin/tipsNtricks) on [codepen] (http://codepen.io/gtalin/full/MJjbyx/)

### Day 15: January 17, 2017

**Today's Progress**: FreeCodeCamp API project for Timestamp Microservice.

**Thoughts:** There was a gap between when I had first read up on express. Revised it and then setup the repo and basic server using express. Used two routes: a.) For when some parameter is passed to root and b.) when parameter is not passed. 

**Link to work:** [timeStamp Microservice] (https://github.com/gtalin/timeStampMicroService) 

### Day 16: January 18, 2017

**Today's Progress**: FreeCodeCamp API project for Timestamp Microservice.

**Thoughts:** Worked on converting date parameter in URL to unix and human readable date. Tried to get the values as close to the demo app in fcc. If string form date is wrong, node automatically converts it to unix timestamp: 1008374400 (in firefox browser however if we do the same: Date.parse("Dec 15") we get NaN) which then converetd to human readable form becomes: Dec 15 2001. Have yet to make the home page explaining how to use API and then checking out options of how to deploy it. 
Date to string: new Date(unix)
Unix to human readable: Date.parse(string);
Above commands with a few changes have been used.

**Link to work:** [TimeStamp Microservice] (https://github.com/gtalin/timeStampMicroService) 

### Day 17: January 19, 2017

**Today's Progress**: Made alien pixel art with JS.

**Thoughts:** Pixel art is fun. Initially thougt to make one with box shadows then decided to use divs and JS instead.

**Link to work:** [Pixel Art Alien] (http://codepen.io/gtalin/full/apJmLV/) [Pixel Art Alien] (https://github.com/gtalin/tipsNtricks) 

### Day 18: January 20, 2017

**Today's Progress**: Codewars kata to find the branch with maximum sum.

**Thoughts:** It was mainly a problem of tree traversal (solved through recursion)

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 19: January 21, 2017

**Today's Progress**: Codewars kata Arrays are objects in JS

**Thoughts:** Codewars in JS are objects.

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 20: January 22, 2017

**Today's Progress**: Made modifications to pixel art. 

**Thoughts:** Made some modifications in pixel art. Learned about getters and setters in JS. Working on d3 Heat map

**Link to work:** [Pixel Art Alien] (https://github.com/gtalin/tipsNtricks) [Pixel art] (http://codepen.io/gtalin/full/YNVJWB/)

## Day 21: January 23, 2017

**Today's Progress**: Worked on D3 heat-map. Wrote a script to calculate height of a tree. 

**Thoughts:** Spent quite a lot of time on D3. Did figure out how we can go about creating a heat map. Parsed the data so we can get an array of arrays for plotting a heat-map.
Wanted to have some working code so write a script to calculate height of a binary tree. 

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 22: January 24, 2017

**Today's Progress**: implemented dfs using recursion. 

**Thoughts:** DFS using recursion.

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 23: January 25, 2017

**Today's Progress**: D3 heat-map. 

**Thoughts:** D3 heat-map. Had parsed data so that I just got an array of arrays. Was planning on building the heat map using rows and then cells in rows. Realised I did not need to do that. I could just use rect feature that I had used in making bar-char and simply use an array of objects. (previously I had parsed the data so that I had an array of rows. Each row containing variance for all years: 1753-2015 (a row for each month thus 12 rows)
The new approach is much better. Have much to add yet: tooltip, axis, labels and most importantly color.
DFS using iteration and path using dfs. 

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 24: January 26, 2017

**Today's Progress**: Worked a bit on D3 heat-map and did bfs.

**Thoughts:** D3 heat-map color in the heat-map. bfs and path using bfs.

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 25: January 27, 2017

**Today's Progress**: Implemented Dijkstra in JS.

**Thoughts:** Did not work on the heat map today. 
Had some troubles with the dijkstra implementation because of on an assumption I made of the indices of graph and the indices of queue being the same (which was the case for the first iteration). But with each iteration, the length of queue reduced and thus direct mapping of index of Q and it's contents did not work.

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 26: January 28, 2017

**Today's Progress**: Codewars Kata

**Thoughts:** Read about regExp. Did a kata.

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 27: January 29, 2017

**Today's Progress**: Heat-map. 

**Thoughts:** Worked on heat-map D3. Basic grid layout after reading data.

**Link to work:** [HeatMap] (https://github.com/gtalin/Data-Visualization)

## Day 28: January 30, 2017

**Today's Progress**: Heat-map. 

**Thoughts:** Color to heat map using color-scale and functioning tooltip.

**Link to work:** [HeatMap] (https://github.com/gtalin/Data-Visualization)

## Day 29: January 31, 2017

**Today's Progress**: Heat-map. 

**Thoughts:** Legend and title. It's supposed to be a multi-line title. The method I've used doesn't seem the best.

**Link to work:** [HeatMap] (https://github.com/gtalin/Data-Visualization)

## Day 30: February 1, 2017

**Today's Progress**: Heat-map. 

**Thoughts:** Completed the heat map today. The multi-line title problem was resolved by adding "text" for each line using selectAll and enter() method. 

**Link to work:** [HeatMap] (https://github.com/gtalin/Data-Visualization) on codepen [Heat Map] (http://codepen.io/gtalin/full/MJmpWg/)

## Day 31: February 2, 2017

**Today's Progress**: Started on twitch tv free code camp app and did a slection sort implementation. 

**Thoughts:** Started on twitch tv free code camp app and did a quick slection sort implementation. 

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 32: February 3, 2017

**Today's Progress**: GCD implementation

**Thoughts:** Did a greatest common divisor implementation.

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 33: February 4, 2017

**Today's Progress**: Bubble sort

**Thoughts:** Had a very hectic day and was too tired. But did not want to skip.

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 34: February 5, 2017

**Today's Progress**: Codewars kata

**Thoughts:** Codewars kata

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 35: February 6, 2017

**Today's Progress**: Fcc twitch tv app

**Thoughts:** Worked on twitch TV app. Used flexbox

**Link to work:** [Twitch] (https://github.com/gtalin/twitchTV)

## Day 36: February 7, 2017

**Today's Progress**: Fcc twitch tv app

**Thoughts:** Had to change the way I was processing data. Used getJSON to get data. Used it inside a loop and formed the dom elements directly. Also used a nested getJSON (the 1st being for user data nd the 2nd being for user status) 
The above process was fine if we had to display the data just once. But we have some buttons by which we can switch display to all, offline or online channels. 
So for this I decided to use deferred objects. Used when and then. However by this process, my nested getJSON stopped working. Tried to get it to work then realised like we are putting all getJSON calls into a stack, we can do the same thing for the getJSON statement we used to get the status of a channel (the one which was a nested getJSON previously. -- we were directly creating dom elements in the success callback of 1st getJSON and in the same callback had the nested 2nd getJSON which was creating the status part of the row and only in the success callback of the second getJSON did we append all the elements to dom.

**Link to work:** [Twitch] (https://github.com/gtalin/twitchTV)

## Day 37: February 8, 2017

**Today's Progress**: Fcc twitch tv app

**Thoughts:** Added the option to view just the "online", "offline" or "all" streamers.
Could've used the option to hide the list elements. Instead chose to filter elements and reconstruct the list.

**Link to work:** [Twitch] (https://github.com/gtalin/twitchTV) [codepen] (http://codepen.io/gtalin/full/WRKrWN/)

## Day 38: February 9, 2017

**Today's Progress**: Quiz in HTML, CSS and vanilla JS

**Thoughts:** Highest peak in each continent quiz.

**Link to work:** [Quiz] (https://github.com/gtalin/tipsNtricks) 

## Day 39: February 10, 2017

**Today's Progress**: Quiz in HTML, CSS and vanilla JS

**Thoughts:** Highest peak in each continent quiz.

**Link to work:** [Quiz] (https://github.com/gtalin/tipsNtricks) [Quiz codepen] (http://codepen.io/gtalin/full/ggBNmY/)

## Day 40: February 11, 2017

**Today's Progress**: array2tree 

**Thoughts:** Array to tree conversion. 

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 41: February 12, 2017

**Today's Progress**: Request Header Parser Microservice free code camp

**Thoughts:** Part of free code camp API projects. Completed the project and deployed it. Followed instructions on heroku dev center to deploy node js app on heroku. Had an initial error. Checked heroku logs (as well as compared my package.json file with the package.json file in the demo app in the node app deployment tutorial on heroku dev center) and found that I had not mentioned the "start" script. Once I did that and pushed the changes to heroku, my app was working. 

**Link to work:** [Request Header API] (https://github.com/gtalin/requestHeader)  [HeaderAPI] (https://headparse007.herokuapp.com/api/whoami)

## Day 42: February 13, 2017

**Today's Progress**: URL shortner free code camp

**Thoughts:** Just got started with the project. 

**Link to work:** [url shortner] (https://github.com/gtalin/urlShortner) 

## Day 43: February 14, 2017

**Today's Progress**: URL shortner free code camp

**Thoughts:** Was struggling to pass a url as paramter. Found I can use a wild character * for it.
I thought I would use url package to parse the url but so far it's not working.

**Link to work:** [url shortner] (https://github.com/gtalin/urlShortner) 

## Day 44: February 15, 2017

**Today's Progress**: Quote generator react

**Thoughts:** Quote machine on react. The visualization is not that great.

**Link to work:** [Quote machine react] (https://github.com/gtalin/tipsNtricks)  [Quote Machine react codepen] (http://codepen.io/gtalin/full/dNrrxm/) 

## Day 45: February 16, 2017

**Today's Progress**: url shortner 

**Thoughts:** Implemented logic of url shortner as suggested in geeksforgeeks. Will come in handy for the URL shortner API free code camp.

**Link to work:** [Codewars] (https://github.com/gtalin/CodeWars)

## Day 46: February 17, 2017

**Today's Progress**: URL shortner free code camp

**Thoughts:** Parsed url using 'valid-url'. 
Created mongodb in mLab. Used free code camp [turtorial] (https://github.com/FreeCodeCamp/FreeCodeCamp/wiki/Using-MongoDB-And-Deploying-To-Heroku) to access MongoDB from express. Spent a lot of time trying to figure out how to access the path set from ubuntu into the express file using process.env. It turns out the variable we set using export gets deleted as soon as we close the shell. It doesn't even work if we open a new shell window or tab. We need to run nodemon in the same terminal window (and tab) in which we use export to set set the MONGODB_URI.So finally was able to connect to the mLab DB from local system. 
Need to create collection with actual url an reduced url. Will use the url shortner logic I implemented yesterday. 

**Link to work:** [url shortner] (https://github.com/gtalin/urlShortner) 

## Day 47: February 18, 2017

**Today's Progress**: Pomodoro timer in progress.

**Thoughts:** Spent quite a lot of time on Pomodoro timer today. Trying to write modular code so that my variables are not all over the place and if something breaks (which tends to happen when my program structure and flow are not right and I add some more functionality ) I have a better chance of fixing it. 
On a side note initially wrote incorrect constructor for time (my data and functionality had got all mixed up) and was wrongly recreating the object repeatedly instead of just decrementing the one I had (because my constructor was wrong)

**Link to work:** [Pomodoro WIP] (https://github.com/gtalin/tipsNtricks)

## Day 48: February 19, 2017

**Today's Progress**: Pomodoro timer.

**Thoughts:** Worked on Pomodoro timer. 

**Link to work:** [Pomodoro WIP] (https://github.com/gtalin/tipsNtricks)

## Day 49: February 20, 2017

**Today's Progress**: Url shortner

**Thoughts:** Learned more about mongodb commands and using mongodb with node.
For example db.collection.count() gives the number of documents in a collection However to use the same in express, we have to tweak a bit:
collection.find({}).toArray(function(err,docs) {console.log(docs.length});
If we try to console collection.find().count() or collection.find({}).toArray() we get some weird results. 
Also went through the comparison sheet between SQL and mongoDB.
SQL: Database ; MongoBD: Database
SQL: table    ; MongoBD: collection
SQL: row      ; MongoBD: document
SQL: column   ; MongoBD: field

**Link to work:** [url shortner] (https://github.com/gtalin/urlShortner) 

## Day 50: February 21, 2017

**Today's Progress**: Weather icons

**Thoughts:** Made cloud, thunder bolt and rain using css

**Link to work:** [Weather Icons] (https://github.com/gtalin/tipsNtricks) 

## Day 51: February 22, 2017

**Today's Progress**: Weather icons

**Thoughts:** Worked a bit more on the icons. Though in all probability I'll not be using these icons for my weather app, it was still quite nice to work on it.
Also worked on the pomodoro timer. 

**Link to work:** [Weather Icons] (https://github.com/gtalin/tipsNtricks) 

## Day 52: February 23, 2017

**Today's Progress**: Pomodoro timer

**Thoughts:** WOrked on the Pomodoro Timer

**Link to work:** [Pomodoro] (https://github.com/gtalin/tipsNtricks) 

## Day 53: February 24, 2017

**Today's Progress**: Weather App

**Thoughts:** I wanted to this with vanilla JS. I had used jQuery before to "get" data but this time I used XMLHttpRequest.
I used IP address to get the location (Name of place and geographic co-ordinates which I would use for get weather data through a weather API.) I could've used HTML5 geolocation option but for that we need user permission. I wanted something without that so IP address was the only option.
I used ip-info.io to get the location data. Now due to some misunderstanding with how to use the API with vanilla JS and jQuery, I spent quite a lot of time getting the JSON data (in XMLHttpRequest() we need to add ?callback at the end of the url to get the JSON data. It was mentioned in the documentation page however I was looking at the jQuery syntax (on the same page) and that did not have callback in the url.) However in the end I realised my wrong usage of API and was able to use vanilla JS to get the data.

**Link to work:** [Weather App] (https://github.com/gtalin/tipsNtricks) 

## Day 54: February 25, 2017

**Today's Progress**: Weather App

**Thoughts:** Used promises for the first time in my application. It was great to use it. The code looked much neater and organized + I got to learn how to use them.

**Link to work:** [Weather App] (https://github.com/gtalin/tipsNtricks) 

**Link to work:** [Weather App] (https://github.com/gtalin/tipsNtricks) 

## Day 55: February 26, 2017

**Today's Progress**: Weather App

**Thoughts:** Had some problems with weather API url. Was getting wrong data. Rectified it. 

**Link to work:** [Weather App] (https://github.com/gtalin/tipsNtricks) 

## Day 56: February 27, 2017

**Today's Progress**: Passport for authentication.

**Thoughts:** In the process of reading and working through a tutorial on js authentication using passport.

**Link to work:** No link

## Day 57: February 28, 2017

**Today's Progress**: Weather App

**Thoughts:** Weather icons I am using (by Erik Flowers) have a direct mapping for various weather APIs including openweather.org. Thus using those icons and directly adding the weather id we get from the API to the icon to get the appropriate icon.
I did notice a slight problem with the icon right now though. The weather returned was hazy. Icon is also hazy but it returned a day time hazy icon as opposed to a night time hazy icon. So we'll probably have to check the time as well. Or we can simply use the basic weather icons there are (as indicated in main in api)
Also read up on passport authentication.
Still left: Need to sort out icons and capitalization of weather description. Make it look slightly better.

**Link to work:**  [Weather App] (https://github.com/gtalin/tipsNtricks) 

## Day 58: March 1, 2017

**Today's Progress**: Star field in JS in progress.

**Thoughts:** Making a starfield in JS. So far particles on a dark background (in canvas)

**Link to work:**  No link.

## Day 59: March 14, 2017

**Today's Progress**: Started work on force directed graph Free code camp

**Thoughts:** I am following some force directed graph d3 tutorials I found online to do my free code camp project. Following the tutorial I was able to get circles as nodes.
Need to use flags instead. Already have a feeling that is going to be tougher than I think. (have sprites with css making that work in SVG)
Will also work on changing parameters for simulation so that it looks more open and nodes a bit farther apart.

**Link to work:**  No link.

## Day 60: March 15, 2017

**Today's Progress**: Force directed graph Free code camp

**Thoughts:** Worked on changing parameters for simulation so that it looks more open and nodes a bit farther apart. Still not very happy with how the nodes look. Also searched a bit as to how I can use sprites to add flag images in graph.
The graph is made with svg and the sprite sheet has a css file. If it was just html we could've added <img> tag and then classes as per the css sheet. But in d3, there is svg and that has <image> tag which doesn't take classes like the <img> tag does.

**Link to work:**  No link.

## Day 61: March 16, 2017

**Today's Progress**: Force directed graph Free code camp

**Thoughts:** Was displaying country name for nodes by doing: node.append("title").text(...) This was working in chrome however today I checked on firefox. It wasn't working so used tooltip to display country name. 
d3.forceX().strength and d3.forceY().strength causes graph to spread out more. Lesser the value, more spread out it is. 

**Link to work:**  No link.

## Day 62: March 17, 2017

**Today's Progress**: Force directed graph Free code camp

**Thoughts:** Need to add flags as HTMl in the graph becuase we have a sprite sheet with corresponding css. 
The first approach I used, I used <image> and got the whole png file as node rather than part of the sprite sheet extracted. I had applied css class to the <image> but it works for <img> the html tag and not for <image> the svg tag.
A comment in one of the forums said that in d3 not everything needs to be svg, we can make things html as well. First I tried attaching <img> tag to a <circle> but that did not work. 
Then I decided to make my nodes as <img> rather than <image> and do away with <circle> all together. But when I made the nodes as html, the graph became static. I was able to get a unique flag for each node but I could no longer move the nodes. It looked like the final graph I was getting with circles as nodes but the nodes could not move and neither could I see the place attached to each node as I hovered over them.
Thus I need to think of a better approach to make the graph work. 

**Link to work:**  No link.

## Day 63: March 18, 2017

**Today's Progress**: Force directed graph Free code camp

**Thoughts:** Need to add flag to an svg node: <g> That way we can add individual flags as well as maintain the interactive nature of the graph.

**Link to work:**  No link.

## Day 64: March 19, 2017

**Today's Progress**: File metadata API Free code camp 

**Thoughts:** Started file metadata project, fcc, using multer package. 

**Link to work:**  No link.

## Day 65: March 20, 2017

**Today's Progress**: Some exercises on free code camp. 

**Thoughts:** Did some exercises on free code camp. 

**Link to work:**  No link.
