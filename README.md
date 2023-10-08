# Map-Point-Reduction
Given a set of location coordinates for an individual, due to the time resolution at which the data
is collected (for example, a typical collection strategy is to collect the individual’s location every
2 minutes at the minimum – different strategies are used in this), there are multiple points
collected around the same area for each person. Work on an
algorithm to reduce the data points into a grid system such that we have a single point for a
couple of points that fall in the grid.

An example to illustrate this is: Consider a 50m x 50m grid, an individual walking around in that
grid will generate multiple coordinates over the course of the day. All the points in that grid will
then be reduced to a single point – the center of the 50m x 50m grid.

Various methods can be used to achieve this:
• An exact method: divide the globe into 50m x 50m grid systems and classify the
points into these grids. This is expensive and computationally expensive.

• An approximate method: if you chose this method, you would come up with an
approximate method that achieves the reduction purpose.

Your Chosen method will
be tested against a large set of coordinates for accuracy and efficiency.
