# Loop code chunks in RMarkdown - a flexdashboard example

This is a RMarkdown and flexdashboard example of how to implement code chunk looping. 

Specifically, this example loops through the `Species` variable in the famous **iris** dataset and the `gender` variable in the {tidyverse} **starwars** dataset, and for each of these: 
- Create a new tab named after the value in that variable, e.g. _setosa_ in `iris$Species`
- In each tab, show a HTML table that contains the data table filtered by the value. In this example, this is implemented using `DT::datatable()`.

You'll need the following packages to run this example:
- {tidyverse}
- {DT}
- {flexdashboard}

This also assumes that you have access to {rmarkdown} and {pander} via RStudio.

Clone or download this repo to get started. 
