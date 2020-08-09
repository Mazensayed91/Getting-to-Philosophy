# Getting-to-Philosophy
## With two different approaches
#### The second solution has O(n^3) but it takes about 8 ms to run the query (we wait 0.5 second to avoid heavy load on Wikipedia
Clicking on the first link in the main body of a Wikipedia article and repeating the process for subsequent articles would usually lead to the article Philosophy.
 
The program should receive a Wikipedia link as an input, go to another normal link and repeat this process until either Philosophy page is reached, or we are in an article without any outgoing Wikilinks, or stuck in a loop.
 
A "normal link" is a link from the main page article, not in a box, is blue (red is for non-existing articles), not in parentheses, not italic and not a footnote.
