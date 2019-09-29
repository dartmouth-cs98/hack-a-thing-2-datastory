# hack-a-thing-2-datastory

### What We made

We created a data visualiztion inspired by data journalism sites like [The Pudding]() that explains the current state of diversity in the senate. The goals of the project were to make the data appear as a fluid story and to create the visualizations entirely with HTML and CSS, without any SVGs. We used [this tutorial](https://pudding.cool/process/flexbox-layout/) to implement the waffle chart without using SVGs and [this library](https://github.com/russellgoldenberg/scrollama) to create the scrollytelling feel, showing and hiding different text/elements of the chart as the user scrolls. Even the stripes within the waffle chart boxes are done entirely with CSS, using [this](https://css-tricks.com/stripes-css/) for a tutorial. 

Since the data for the story is fairly simple, we used information from the [U.S. Census](https://www.census.gov/quickfacts/fact/table/US/LFE046217) and the [official senate website](https://www.senate.gov/senators/EthnicDiversityintheSenate.htm) to quantify diversity in the U.S. as a whole and the current Senate. From these sources, we used the following statistics:
* The Senate is comprised of 25 women and 75 men
* Only 9 senators are non-white, 4 of whom are women and 5 of whom are men
* The population of the United States is almost 51% female
* Just over 60% of the U.S. Population is only white

### Who did what (if you worked with someone else)

Emma Langfitt and Himadri Narasimhamurthy worked together to create this data visualization. Emma did the initial framework and connection to the libraries, and Himadri worked with the charts and content of the story.

### What you learned

First and foremost, we learned that the senate is *not* representative of the United States population by a longshot. Second, we learned that the details of data visualization can make a simple-seeming diagram be very tricky to implement. Deciding how to best display the data for easy readability is only half the battle, because you then have to implement whatever choices you make. We also found that little changes like smooth scrolling and fading transitions can make a site go from feeling jumpy and hard to follow to feeling like a smooth experience, which in turn makes the story seem to flow better from one idea to the next. 

### What didn’t work

The Scrollama library was difficult to get up and running at first, since you first need to understand the logic behind scrolling and sticking items before you can really start to use the methods it implements. The next messiest bit was the layout of items within the scrolling blocks, since the library and examples came with a lot of styling that we then altered to fit our needs. If we'd had more time, we also would have liked to work with more types of visualizations, specifically trying to add a bar chart using exclusively HTML/CSS. 