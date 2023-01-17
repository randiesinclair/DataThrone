# DataThrone
I'll admit it. I was one of those people who was perfectly happy to have never seen an episode of Game of Thrones back in 2017, six years into the show when it was at its peak in popularity. A contrarian even, talking it down at times. I didn't understand the hype, until I was finally convinced by a coworker to "just give it a shot". Well I did, and as they say the rest is history! After watching every episode up until that point, I would go on to rewatch GOT all the way through a second time with my now wife who equally enjoyed it.

When it came time to pick a topic for a fun data project, I knew I wanted to dive into something I was passionate about. And what could be more thrilling than digging through all of the death in the Seven Kingdoms? So here we are! My project "Datathrone" is all about finding out where the most dangerous places to be were, and who were the deadliest characters in those places. I'll be using data cleansing and visualization to present some information I've always been interested in. So whether you're a hardcore fan or just getting into the series, join me on this journey as we uncover the true deadliest players and places in the Game of Thrones!

# Technical Skill
- Python
- Pandas
- Matplotlib
- Data Cleansing
- Jupyter Notebook

# Parameters/Additional Info



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

In my breakdown I made the decision to create two top 5s to separate beings such dragons, and groups such as armies who get kills in masses from individual humans. There was also just curiosity to see who the most dangerous individuals were by breaking it up.

Rhaegel was the second deadliest dragon in the shows run, and 170 of his 273 total kills took place Beyond the Wall

Jon Snow is one debatably the main protagonist of the show, and runs up an impressive kill count through a variety of locations all over Westeros. 48 of his 112 total kills were Beyond the Wall

