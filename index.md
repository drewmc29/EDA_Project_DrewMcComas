## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/drewmc29/EDA_Project_DrewMcComas/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

As I thought about what subject I wanted to focus on for my exploratory data analysis project, I came across the example on Aaron Rodgers free plays. I love to watch football and this example peaked my interest, so I decided to do something regarding the NFL. 

The National Football League (NFL) is a professional American football league which consists of 32 teams. These teams are divided equally between the National Football Conference (NFC) and the American Football Conference (AFC). The NFL is one of the four major professional sports leagues in North America.

After deciding on the NFL, the next step for me was deciding what I wanted to learn from my work. What does every time strive for when they step foot on the field? To win. There is a very popular saying in football that defense wins championships. So, I thought an interesting avenue to continue down would be looking at wins in the NFL, specifically geared towards the 49ers (as they are my favorite team) and how defenses can create more wins. So, to start, I downloaded a detailed NFL play-by-play data set.

Guiding Questions:
What aspects of football plays are important in determining wins?
Looking defensively, could coaches leverage data to predict play type?
Many factors go into play calling both offensively and defensively. What are the most important elements in predicting plays as a defense?


There is quite a bit of data here, and when shaping it, we see that there are 249,686 rows and 255 columns. Because of this, the next step was to go through and understand what the columns that weren’t intuitive actually meant, and if it would be relevant for the project. 

The columns I deemed most important were team (to filter only the 49ers), time remaining, the yardline the team is on, the down, yards for a first down, the score, the play type, and lastly run/pass location. And consequently, filtered just these columns into the dataset to clean it up. 

Following this filtering, the next thing I wanted to accomplish was adding a new column. This column is titled  “Full_Play”. What is special about adding this column is that it not only takes into account whether a play is a run or a pass, but the direction (left, middle, right) as well. This is crucial in identifying plays and hence being able to predict where the play is headed as a defense. 

