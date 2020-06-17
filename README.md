paperscape-headstart
# Paperscape - headstart


Based on "Paperscape" at https://paperscape.org/

About Paperscape
[A list of external news/blog posts about Paperscape can be found here.]

Paperscape is a tool to visualise the arXiv, an open, online repository for scientific research papers. The Paperscape map currently includes all (non-withdrawn) papers from the arXiv and is updated daily.

Each paper in the map is represented by a circle, with the area of the circle proportional to the number of citations that paper has. In laying out the map, an N-body algorithm is run to determine positions based on references between the papers. There are two “forces” involved in the N-body calculation: each paper is repelled from all other papers using an anti-gravity inverse-distance force, and each paper is attracted to all of its references using a spring modelled by Hooke’s law. We further demand that there is no overlap of the papers.

The map is rendered simply as a solid circle for each paper. The colour of the circle denotes the arXiv category of the paper, and the brightness indicates age. Brightness is sometime difficult to discern, and we are working on adding a heat-map overlay to indicate clearly the areas of the map which have the most recent activity.

As you zoom in on the map labels will start to appear on individual papers. These labels are (mostly) automatically extracted by analysing word frequency in the title and abstract of the paper, and are generally indicative of the subject matter of that paper. Zooming in closer also shows the author(s) of the paper. If a paper is deemed to be a review paper, or a set of lectures, this is noted.

PERHAPS THIS CAN BE USED TO VISUALIZE ALL SORTS OF CONNECTED ITEMS (SUCH AS IT INFRASTRUCTURE)... TO DO: Research!
