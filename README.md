# DataThrone
I'll admit it. I was one of those people who was perfectly happy to have never seen an episode of Game of Thrones back in 2017, six years into the show when it was at its peak in popularity. A contrarian even, talking it down at times. I didn't understand the hype, until I was finally convinced by a coworker to "just give it a shot". Well I did, and as they say the rest is history! After watching every episode up until that point, I would go on to rewatch GOT all the way through a second time with my now wife who equally enjoyed it.

When it came time to pick a topic for a fun data project, I knew I wanted to dive into something I was passionate about. And what could be more thrilling than digging through all of the death in the Seven Kingdoms? So here we are! My project "Datathrone" is all about finding out where the most dangerous places to be were, and who were the deadliest characters in those places. We'll even get into what group of people where most in danger based on the amount of deaths in each area. I'll be using data cleansing and visualization to present some information I've always been interested in. So whether you're a hardcore fan or just getting into the series, join me on this journey as we uncover the true deadliest places and players in the Game of Thrones!

# Technical Skill
- Python
- Pandas
- Matplotlib
- Data Cleansing
- Jupyter Notebook

# Additional Dataset Information

With this database I researched the top 3 deadliest areas of this world, the top 5 killers in each of those areas, and also the top 5 deaths by allegiance in each of the 3 areas. To clarify, I wanted to know what allegiance it was most dangerous for in each of those areas. If you’ve never seen this show and plan to, turn your volume all the way down right now. Many spoilers ahead!

You may be wondering as I did, who in their right mind took the time to count every single one of the alleged 6,887 deaths over the course of 8 seasons of this show… This insane and wonderful individual is Shelly Tan, a graphics reporter specializing in data visualization, illustrations and pop culture. I wanted to be sure to thank and properly credit her for her efforts.

With a dataset like this, there are so many variables, that a methodology must be established to be able to research and get the results that we seek. Some of the decisions that were made to create this dataset include:
 - A death is only counted if the character is killed on-screen. UNLESS, the character dies off-screen but the death is confirmed or assumed due to imminent death while on screen. The exception would be prominent off-screen deaths, and prominence is determined mostly by importance to the plot.

 - Another decision that was made for this dataset was that if a character orders the death of another, the character who does the direct killing receives credit; not the one who orders the kill. But for cases where the direct killer is unidentifiable, like when Cersei Lannister uses the caches of wildfire to blow up the Great Sept of Baelor, the order giver receives the credit.

It is also noted that for big battles such as the Battle of the Bastards, it is often unclear which side a soldier being killed belongs to. Educated guesses were made based on the details like the shape of a helmet a soldier is wearing, along with other things like sigils that can be seen on armor.


---------------------------------------------------------------------------------------
Dataset Source:
Tan, Shelly (2018) data-game-of-thrones-deaths [Data set].
	Washington Post/Github.
	https://raw.githubusercontent.com/washingtonpost/data-game-of-thrones-deaths/master/game-of-thrones-deaths-data.csv
---------------------------------------------------------------------------------------


![Slide1](https://user-images.githubusercontent.com/109693942/212296785-a7b8d396-7c76-4533-90f0-61d9b635655f.jpg)

<h1 align="center">#3 - MOST DANGEROUS AREAS</h1>
<h2 align="center">BEYOND THE WALL</h2>

In my breakdown I made the decision to create two top 5's to separate beings such dragons, and groups such as armies who get kills in masses from individual humans. There was also just curiosity from me to see who the most dangerous individuals were by breaking it up.

- Rhaegel was the second deadliest dragon in the shows run, and 170 of his 273 total kills took place Beyond the Wall

- Jon Snow who is debatably the main protagonist of the show, runs up an impressive kill count through a variety of locations all over Westeros. 48 of his 112 total kills were Beyond the Wall

![Slide2](https://user-images.githubusercontent.com/109693942/213017400-a1c9b992-119b-44fb-9064-c5ca108e89f1.jpg)
Fun facts: 
- The very first death in Game of Thrones was Beyond the Wall, in the very first episode. Waymar Royce, a Ranger with The Night’s Watch, was killed by a White Walker.
- Most death Beyond the Wall was not at the hands of anyone. For example, of the 917 Wights that died Beyond the Wall 421 of them drowned.

![Slide3](https://user-images.githubusercontent.com/109693942/213018562-a5d8c4fe-a9c1-479d-83c3-d9d22c1a85db.jpg)

<h1 align="center">#2 - MOST DANGEROUS AREAS</h1>
<h2 align="center">KING'S LANDING</h2>

- Drogon is the largest and deadliest dragon in the shows run. 917 of his 1,426 total kills took place in King’s Landing
- Cersei Lannister was a ruthless but very effective leader who oversaw The Seven Kingdoms. She assumed the throne after tragically losing each of her children, and was the last monarch to sit on the Iron Throne before it was destroyed.

![Slide4](https://user-images.githubusercontent.com/109693942/213018642-0e55129e-5c58-4cd2-b79d-dc192b8cf4a9.jpg)
Fun Facts:
- King’s Landing is the home of the most amount of deaths of characters who were categorized as most important to the series (16): 
	- Robert Baratheon, Ned Stark, Joffrey Baratheon, Oberyn Martell, Shae, Tywin Lannister, High Sparrow, Loras Tyrell, Margaery Tyrell, Tommen Baratheon, Missandei, Euron Greyjoy, Sandor “The Hound” Clegane, Jaime Lannister, Cersei Lannister, and Daenerys Targaryen 
- King’s Landing is the location of the very last death in the series

![Slide5](https://user-images.githubusercontent.com/109693942/213019363-5245ad8a-f1ce-4f9c-9f80-cc8a25befca2.jpg)
<h1 align="center">#1 - MOST DANGEROUS AREAS</h1>
<h2 align="center">WINTERFELL</h2>

- If we remove all death connected to the Night King’s slaying, Arya drops to #4 with only 24 kills
- The Wights led by the Night King and White Walkers descended on Winterfell in search of Bran Stark to kill him. They were met by several forces to stand against them starting one of the largest battles of the show, hence the most kills in Winterfell


![Slide6](https://user-images.githubusercontent.com/109693942/213019446-e3dec3f7-cceb-40a7-b74e-4d014581f896.jpg)
- Winterfell is the home of the second most amount of deaths of characters who were categorized as most important to the series (10): 
	- Stannis Baratheon, Roose Bolton, Rickon Stark, Ramsay Bolton, Petyr Baelish, Theon Greyjoy, Night King, Viserion (Wight), Jorah Mormont, Melisandre “Red Woman” of Asshai 
		- Arya Stark is responsible for 3 of those 10 kills

![Slide7](https://user-images.githubusercontent.com/109693942/213023629-6458d57e-8325-480e-91e4-cb24105e1731.jpg)
