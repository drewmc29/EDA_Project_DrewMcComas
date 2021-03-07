As I thought about what subject I wanted to focus on for my exploratory data analysis project, I came across the example on Aaron Rodgers free plays. I love to watch football and this example peaked my interest, so I decided to do something regarding the NFL. 

The National Football League (NFL) is a professional American football league which consists of 32 teams. These teams are divided equally between the National Football Conference (NFC) and the American Football Conference (AFC). The NFL is one of the four major professional sports leagues in North America.

After deciding on the NFL, the next step for me was deciding what I wanted to learn from my work. What does every time strive for when they step foot on the field? To win. There is a very popular saying in football that defense wins championships. So, I thought an interesting avenue to continue down would be looking at wins in the NFL, specifically geared towards the 49ers (as they are my favorite team) and how defenses can create more wins. So, to start, I downloaded a detailed NFL play-by-play data set.

Guiding Questions:
What aspects of football plays are important in determining wins?
Looking defensively, could coaches leverage data to predict play type?
Many factors go into play calling both offensively and defensively. What are the most important elements in predicting plays as a defense?


There is quite a bit of data here, and when shaping it, we see that there are 249,686 rows and 255 columns. Because of this, the next step was to go through and understand what the columns that weren’t intuitive actually meant, and if it would be relevant for the project. 

The columns I deemed most important were team (to filter only the 49ers), the yardline the team is on, the down, yards for a first down, the score, the play type, and lastly run/pass location. And consequently, filtered just these columns into the dataset to clean it up. 

Following this filtering, the next thing I wanted to accomplish was adding a new column. This column is titled  “Full_Play”. What is special about adding this column is that it not only takes into account whether a play is a run or a pass, but the direction (left, middle, right) as well. This is crucial in identifying plays and hence being able to predict where the play is headed as a defense. 

After making this new column, I wanted to look at the data compiled. So, I looked into the data for the percentage breakdown of 49ers full plays (by the column I had just created). The results are below. 


 


After this, I wanted to create a graph of these percentages. 



The graph of the percentage of 49ers full plays is an interesting one. It is fascinating to see that passes to the right side of the field far outweigh other play types. I believe this can be attributed to the primary receivers over the years (Anquan Boldin, Deebo Samuel, Michael Crabtree) typically lining up on the right side of the field. In this sense, it is worth noting that defenses should understand the opposing teams tendencies to make best use of data to predict plays. Furthermore, the run up the middle is twice as much as a run to the left or to the right. This is likely due to the fact that the majority of teams run the ball up the middle the majority of the time.
While this previous graph is interesting, I wanted to dig a little deeper. Something I thought would be interesting to analyze was the variability of yards to go for a first down and the effect it has on play 
type. 






First, I filtered the data by yards to go less than 5 yards. Unsurprisingly, the data shows an increase on all run plays. The trend of runs up the middle remains the case with the uptick in runs across the board. It is interesting to notice however that both the run left and run right didn’t increase very much in comparison to the percentage of overall plays run. This may be a reflection of coach Shanahan's tendency to run short passing plays to the right and left sides of the field. 







In comparison to less than 5 yards, I wanted to look at the difference in results to plays with greater than 10 yards to go for a first down. This graph is much different than the last in the uptick in passing. While all passing plays increased, passes to the left and passes to the right increased in a dramatic fashion. It isn’t too much of a surprise that pass play calls were up so much in comparison to less than 5 yards needed for a first down - passing represents a greater opportunity for a team to gain more yards. However, it is interesting to look at the leniency of the 49ers to pass to the right side of the field. Passing right happens more than double the times that passing up the middle does, and significantly more than passing to the left (6%).


 
 
The next aspect of the data I wanted to examine in respect to the full play type was the down. Meaning, 1st, 2nd, 3rd, or 4th down… and how it affected the choice of play. 




The breakdown for 1st down is somewhat evenly spread across the board. This makes sense, as good teams should vary the plays they run on first down. With respect to the other data we have looked at, the trend continues with  pass left pass right and run middle being the most common/favorite plays of the 49ers offense. 
 



2nd down is where it gets a little more interesting. The aforementioned trend continues to hold true: run middle, pass right, and pass left still lead play types by a large margin. However, there is a slight drop off in pass middle, run left and run right - and this is all channeled into pass right. It is a crazy statistic that the 49ers, almost one third of the time, run a pass right play. This seems like a huge opportunity for defense to capitalize on when playing the 49ers. 
 
 




Moving from 2nd to 3rd down, there is a very clear difference across all play types. I was shocked to see how few run plays were called on third downs. Only 20% of all plays combined are run plays - this is an extremely low number compared to other teams and another point of differentiation that other teams could capitalize on. Consequently, all pass plays increased in percentage - most notably pass right which is called ⅓ of the time. 
 
 
 




The depiction of the breakdown for 4th down should be taken with a grain of salt as 4th down plays are a bit of an anomaly. What I mean by this is that teams typically punt on 4th down unless they are in a favorable part of the field and are relatively close to a 1st down or the endzone. With that being said, is it alarming to see how little the 49ers choose to run the ball to go for 4th down conversions.  Moreover, the disparity in plays called between pass right/left and pass middle is extreme. Again, this seems like a great opportunity for defenses to capitalize on the lack of diversity in play calling. 


Overall, examining the different types of plays the 49ers run was certainly worthwhile in the conclusions that can be drawn from the data. The 49ers favorite play types involve passing to the left and right of the field, as well as running the ball up the middle. Through examining yards to go for a first down, with less than five yards to go, run plays unsurprisingly made up the majority of play calls (with running up the middle being called about 30% of the time). On the other hand, with more than 10 yards to go, pass plays made up most play calls with pass left and pass right comprising almost 50% of the time. 2nd and 3rd down both saw pass right happening an amazing ⅓ of the time. 3rd down however saw a dramatic decrease in run plays than 2nd down. There are many different points of analysis one could draw from pulling and manipulating data on all NFL plays - and certainly could prove beneficial for defenses to analyze specific teams play types based on the down and yardage variability. In conclusion, defenses should absolutely understand the opposing teams tendencies to make best use of data in order to predict plays.






