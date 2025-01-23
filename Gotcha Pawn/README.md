<h2><strong>Overview:</strong></h2>
1. Introduction and Purpose<br>
2. Tech Stack<br>
3. Future Considerations<br>
<br><hr><br>
<img src="/Gotcha Pawn/GOTCHA PAWN.png"></img>
<br>
<h2><strong>Introduction:</strong></h2>
<h3><br></h3>
This is a ServiceNow application to create a Service Catalog gacha machine to have employees exchange tokens for virtual collectibles. I wanted to create something like this because of a relatively recent obsession with certain blind boxes and thought "how could I apply this to an application and what good can come from it? Some of the ideas and purposes include:<br>
- What could the currency be or represent in order to be able to redeem a virtual toy?<br>
- What would people use this for and why would they want to?<br>
- How can this be fun and collaborative?<br>
- How can this be easy as an end user?<br><br>
Typically in this day and age, people do not spend that long at a company as they did maybe 10-20 years ago. There have been studies showing how management, quality of life, and pay are some of the biggest factors for why people leave the companies they work for. Although I cannot sit here and shovel out millions of dollars to every working individual, I can at least aim to make a personal project tackle a more fun work environment. This is an application that can easily make a conversation point over teams in their stand ups. A collectible toy aspect creates a bit of fun in the work day while the daily token system can encourage people to keep within a company (at least a little) and gives a daily mind challenge on whether or not to spend or save. I generally aim for this to be extremely easy for an end user to use. Here is a flow chart as an end user:<br><br>

<iframe width="768" height="432" src="https://miro.com/app/live-embed/uXjVLpNe17c=/?moveToViewport=-720,-225,2255,1080&embedId=155059377638" frameborder="0" scrolling="no" allow="fullscreen; clipboard-read; clipboard-write" allowfullscreen></iframe>

<br><br><br>
The video will be coming soon!
<!-- Watch the video of how this works and the inner machinations below:<br>
<iframe width="420" height="315" src="https://www.youtube.com/watch?v=Zu1wVZ6OX3Y"></iframe><br> -->
<br><br><hr>
<h2><strong>ServiceNow tech stack and tools:</strong></h2>
<ul>
<li>All the obvious stuff like tables, forms, configurations, users/roles/groups, etc.</li>
<li>Service Catalog & Record Producers</li>
<li>Flow Designer & Custom Action Scripts</li>
<li>Scripting in Script Includes, Businesses Rules, Flow Designer, etc.</li>
<li>Scheduled Jobs</li>
<li>Dynamic information based on the logged-in user.</li>
<li>Portal Design & Widget Configuration</li>
</li>UI Policies</li>
<li>Reports and Dashboards</li>
</li>ACLs</li>
</ul>
<br><br><hr><br>

<h2><strong>Future Considerations:</strong></h2>
<ul>
<li>Adding the animal gacha pictures.</li>
<li>Adding more gacha machines and toy series in general.</li>
<li>Duplicate gachas owned will instead increase a quantity integer instead of generating a new record.</li>
<li>Users being able to trade in gachas (deletion of records) in exchange for tokens based on how rare the item is.</li>
<li>Disabling the drilldown view in reports.</li>
<li>Ability to stats between teams in your company.</li>
</ul>
<br>
Most of everything will be explained in the video. Thank you for taking a look at my application!