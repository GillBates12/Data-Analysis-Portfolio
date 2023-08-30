# Data-Analysis-Portfolio
In here I will have multiple projects to show my data analysis proficiency and what I have learned in each project I've done. 

1. Spotify Data Project. To start I received all my listening history dating back to 2015 with Spotify. They send them in very clunky JSON files with a lot of irrelevant information. I used Python to clean the data and pick out just the song title, album, artist and listening time. From there I uploaded the cleaned CSV file to Tableau and made a data visualization dashboard.

2. Bike Sales Analysis - in this project I took some bike sales data and analyzed purchases of bikes based on distance from work, income level, age, gender, region and so forth using pivot tables. I then made a dashboard to conduct the findings with splicers for end users to be able to find insights using more variables.

3. Fantasy Football Season Stats -
   Purport: In fantasy, the WR and RB are the most crucial components of a winning team. Of the 16 total players on a team, most people draft 7 players of those positions combined. Two starting (WR & RB) and a FLEX and then two backups. Next to the QB, they score the highest points for a team and their consistency is most necessary for fantasy league success. What I did to calculate value going into the 2023 draft was create a shorthand scale of which players will be great picks, good picks and sleepers going into the next season. 

Rank: this is the metric for where in the pecking order a player sits. If they're an RB1 the usage will be much higher and obviously be a better pick than a backup

Age: this varies for WR and RB. WR obviously have a longer time in the league so the ranking will differ. 

Average: straightforward, how many points do they get per game? 

I made a variable to account for all of these above attributes a player can have. For rank I did 1-5 to apply as an added bonus for a player. An RB1 is the highest possible with a score of 5 since their usage(thus scoring potential) will be highest and an RB3 is the lowest with a score of 1. 

For age, typically the younger the better. For RBs, after age 28 with the excpetion of great players their score remains the lowest because they don't last as long in the league. For WRs it's after age 30 when the rank starts dwindling

For average, it's based on the peers of their position. So you can be an RB2 or 3 but if you're putting up top 5 numbers then that accounts for something and negates the lower pecking order position.

The total score accounts for all the variables listed as well as performance to give a holistic view of good options for the next season, accounting for player decline due to age, getting benched and how well they did the previous season.  

