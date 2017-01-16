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
