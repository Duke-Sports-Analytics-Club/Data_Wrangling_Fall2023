# Data_Wrangling_Fall2023

### For those that have never used R Studio or Github before
Downloading R, git, and RStudio

R: Choose link under 0-cloud, then choose appropriate install based on computer. https://cran.r-project.org/mirrors.html

Github: Create an account if you do not have one. https://github.com/

Git: Download git using instructions here https://www.theodinproject.com/paths/foundations/courses/foundations/lessons/setting-up-git

RStudio: Download RStudio Desktop https://www.rstudio.com/products/rstudio/download/

If you want to work in the Docker containers
To bring these files into an RStudio session follow the steps below.

Click on the green Code button in this repository, and copy the git URL (it should end in .git).

Go to your RStudio Docker container at https://vm-manage.oit.duke.edu/containers/rstudio.

In RStudio, go to File → New Project → Version Control → Git.

Paste the git URL you copied in (1) into the dialog box labeled Repository URL. Adjust the folder to where you want this repository located.

Click Create Project, and the files from your GitHub repo will be displayed in the Files pane in RStudio.

Click class.Rmd to open the R Markdown file.


### Loading Data
Loading in data is going to be essential to any project. Last time we used data from packages we loaded in. This time, we will want to use outside data. Data is provided in the folder in the repository.

The data we will be working with comes from basketball-reference.com, an open source NBA data website. We will specifically be using 2021-2022 NBA player data. https://www.basketball-reference.com/leagues/NBA_2022_per_game.html

A description of each column header representing the stat can also be found at the link above by hovering over the desired text.

### Working with dplyr
dplyr is a key data wrangling package that we will learn to use and apply.

Highly recommend reading from the official website to get a clearer picture of how each function works. https://dplyr.tidyverse.org/articles/dplyr.html

### Resources
Want to further your understanding of some of the functions used in the analysis? Check out the resources folder of the repository.

Want to learn on your own? See this document for a recommended learning pathway. https://docs.google.com/document/d/1fWET_GreI5qO2E-DDDojsmlfNeoQgZaCji-4D5M3PmA/edit#

The below books are also great resources. R Cookbook is for beginners, while R for Data Science does require some basic knowledge of R.

R Cookbook - https://rc2e.com
R for Data Science - https://r4ds.had.co.nz/
