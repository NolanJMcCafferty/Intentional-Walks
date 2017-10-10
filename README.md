# Intentional-Walks
This is a MATLAB program to determine if an intentional walk should be issued, 
based on the statistical analysis in The Book, by Tom Tango, Mitchel Lightman, and Andrew Dolphin.

The reasoning behind these formulas can be found in Chapter 10 of The Book.
The basic idea is that we can calculate the "teammate" wOBA from the current batter and the next batters in the order,
depending on how many outs there are. Then we calculate the wOBA ratio by dividing the batter's wOBA by the "teammate" wOBA. 
We can also calculate the minimum wOBA ratio needed for an intentional walk to be a good call, using the table on page 315
of The Book. Finally we compare these two values to decide if the intentional walk is a good idea.





