# Final Project


## Introduction

This is a final project for the [Interacting with Data](https://github.com/Brown-BIOL2430-S04-Fall2015/syllabus) seminar in fall 2015. This project examines marine community structure on experimental plates left out on rocky reefs in the Galapagos Islands over two months. These plates were bolted to the rock under cages intended to exert variable herbivore access. The goal is to provide an intuitive, interactive view of how marine life responds to variable herbivore pressures. 

To view this project, click on the following [link](https://rawgit.com/lambrw/finalproject/master/plate_sandbox.html).

## The data

The data behind this visualization are from unpublished data on benthic communities in the Galapagos Islands. All figures you see displayed are based on empirical results of visual censuses, videos, and photos maintained by the [Witman Lab](www.witmanlab.com) at Brown University

The data themselves take the form of either integer counts of mobile invertebrates, or as percentage values for primary space-occupying organisms living on the seafloor. In the original data file, columns are descriptive variables and species, rows are samples. 


## Background



The static images normally presented of community data present a limited view of how patterns change in response to variable top-down pressures. This dynamic interaction with data will facilitate honing in on thresholds, which species respond more or less to herbivory, and how they relate to the variable herbivore guilds driven by wave exposure. In particular, it facilitates a view of the entire spread of the data (top panel, histogram style), with a simultaneous summary of the averages of the data for any given species and any given explanatory variable.

## This project

### Mapping of data to aesthetics


The X-axes correspond to either individual replicate experimental plates (top panel) or values averaged within  experimental treatments (bottom panel). Y-axes correspond to percent cover or numerical abundance. Color corresponds to experimental treatment. 

### Filtering


Data are not filtered.

### Extra ink


In addition to color, labels are assigned to treatments in the bottom panel to aid in visualization and to connect the histogram bars in the top panel to their average values.

### Motion

Motion represents continuity between species or treatments as they are selected. This facilitates intuitive comparison between species or treatments as each is selected.

### Perspective

The user is able to select which species he/she would like to focus on. As a result, the user can look at the response of individual species one by one, and see which ones respond in a consistent manner. The user can also choose any of three predictive variables to look at. By mixing and matching predictive variables with species, this approach provides a powerful tool for exploring a large, multivariate community dataset. The visualization can also be used for data exposition, although greater familiarity would be needed with the experimental design in order for a general user to interpret it.

## Assessment

My intention with this new visualization, which I think it achieves at least to some degree, is a new format for exploratory data analysis. Too often all we end up seeing with bar charts are single average values, perhaps with an error bar associated. However, this tells us really very little about the spread of the data, bias, etc. In addition, when trying to analyze a large, multivariate dataset (such as the benthic community structure displayed here), you would have to either a) make hundreds of charts of individuals species responses to multiple treatment combinations or b) condense the whole community into some sort of ordination that, while also a powerful visual approach, loses a great deal of information. As a result, I think the combination of whole dataset views (top panel, histogram style) *and* the respective average values provides a powerful tool for exploring this type of data. The ability to quickly move between individual species and predictive variable streamlines the data exploration process and has the potential to highlight salient patterns that might otherwise be obscured.

The main limitations of this approach, as the website currently stands, are:

1) The x-axis and y-axis of the bottom panel are not changing, even though the bars and the data they represent are, which hinders interpretation.

2) The list of species/treatments is very long and you have to scroll up and down between selections, which impedes viewing the fluid transitions (movement) between views.

In the future, I would like to be able to choose *combinations* of treatments (rather than just one treatment at a time) so that you can see the impact of crossed treatment effects on individual species. I would also like to add a panel that shows the full community (one bar for every species) that responds only to the treatments selected. This would give a whole-community view to complement the individual species views.

