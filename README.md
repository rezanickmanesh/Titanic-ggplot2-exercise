# Titanic-ggplot2-exercise

Have a look at the str() of the titanic dataset, which has been loaded into your workspace. Looks like the data is pretty tidy!
First, have a look at the distribution of sexes within the classes of the ship. Use ggplot() with the data layer set to titanic. Map factor(Pclass) onto the x axis, factor(Sex) onto fill and draw a dodgy bar plot using geom_bar(). By dodgy we mean that position has to be set to "dodge".
These bar plots won't help you estimate your chances of survival. Copy the previous bar plot, but this time add a facet_grid() layer: ". ~ Survived".
You want to include the final variable in the plot, Age. Start off by copying the previous ggplot() command. Add a mapping of Age onto the y axis. Replace geom_bar() with geom_jitter() and set its attributes size to 3, alpha to 0.5 and position set to posn.j. Make sure that factor(Sex) is mapped onto col instead of fill this time to correctly color the scatter plots.
