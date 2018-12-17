# Homeworks for Utah's Vis for Data Science Course
In subfolders in this directory you will find some homework projects for CS 6630 / CS 5630 - Visualization for Datascience. 

More information can be found on the [course website](http://dataviscourse.net/2018/index.html)

### Homework 1
Bar, line, area, and scatterplot charts visualizing [Anscombe's Quartet dataset](https://en.wikipedia.org/wiki/Anscombe%27s_quartet).
Thorough information [here](https://github.com/JiahuiKChen/2018-dataviscourse-homework/blob/master/hw1/hw1.md)

 ### Homework 2
 Manually generated tree using D3 and Javascript. 
 Thorough information [here](https://github.com/JiahuiKChen/2018-dataviscourse-homework/blob/master/hw2/hw2.md)
 
 ### Homework 4
 World health data displayed via an interactive world map, scatterplot, and information box.
 
 Overall visualization functionality:
 
 ![Clicking Things](/hw4/figs/click.gif)
  
 Visualization's components:
 
 ![Gap Plot Data Change](/hw4/figs/data-change.gif)
 
 ![Gap Plot Year Slider](/hw4/figs/year_slider.gif)
 
 Here's a [video](/hw4/figs/click.mp4) of the visualization's functionality. 
 
 More details [here](https://github.com/JiahuiKChen/2018-dataviscourse-homework/tree/master/hw4)

### Homework 6
Interactive visualization US Presidential Election data from 1940 to 2016. Includes Electoral and Popular Vote statistics for each state for each year.

Overall visualization looks like this:
![Overview](/hw6/figs/overview.png)

Visualization components include:
![yearChart](/hw6/figs/yearChart.png)

![electoralVote](/hw6/figs/electoralVote.png)

![votePercentage](/hw6/figs/votePercentage.png)

![toolTip](/hw6/figs/toolTip.png)

Here's a [video](https://youtu.be/VpuXaajgJq4) of the visualization's functionality.

More details [here](https://github.com/JiahuiKChen/2018-dataviscourse-homework/blob/master/hw6/README.md)

## How to Run 
From any homework's root directory (example: Homework 6's root directory is `hw6`) running a web server will launch the project locally in a web browser.

Example: 
```
cd <path to this repository's root directory>/hw6
python3 -m http.server
```
Will run Homework 6 (clicking on the `.html` file will display the visualization). 
