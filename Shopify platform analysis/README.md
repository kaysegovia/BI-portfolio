Make a KPI Card that counts the unique number of apps. Make a Line Chart getting the sum of the review count on the Y-axis, and the lastmod date on the X-Axis. Make a Scatterplot with the reviews_count on the X axis and the average rating on the Y axis. 
Create a new Column in the Reviews table named helpful_reviews using a DAX expression, which multiplies the rating by 1+helpful_count to weigh the reviews by how helpful they’ve been found. The formula in mathematical form would be rating * (1+helpful_count). Make a Card with the average value of the new helpful_reviews column.
Create a new Column in the Reviews table named developer_answered using a DAX expression, which is 1 (or TRUE) if the developer_reply column is not blank and 0 (or FALSE) if the column row is blank. Make a scatterplot comparing the average rating on the Y-Axis by the value of the developer_answered column on the X-Axis.


https://docs.google.com/document/d/1129vl2pmH9et67egO57oOaINuEu-Cpu4fdEUtnLEcs4/edit?usp=sharing
