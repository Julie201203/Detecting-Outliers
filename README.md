# Detecting-Outliers
By extracting the relevant data from mongoDB database, the data is collected and utilized in the creation of a plot. The plot serves as a visual representation of the data, aiding in the identification and analysis of any outliers present within the dataset.

# Resonable filter for release data against runtime
The highest point is around 650 and the lowest one is around 350. It is increasing at the beginning and then drop, then increase again, very flexible. I think the outlier for release and runtime should be over 400, so we could consider it!

<img width="571" alt="Screenshot 2023-06-22 at 14 18 37" src="https://github.com/Julie201203/Detecting-Outliers/assets/102690387/80cde7ab-f651-4327-ba80-1622232d61ab">

# Resonable filter for budget against release date
Looks like it is not accurate to have this graph like this, how com some movie cost $0 and some are crazy (highest is >1.2). It keeps increasing toward the end of the graph, and the dot is relatively very high and far apart from the average line. There should be some mistake there, so thats why it is also seen as an outlier.

<img width="571" alt="Screenshot 2023-06-22 at 14 19 20" src="https://github.com/Julie201203/Detecting-Outliers/assets/102690387/22ae1761-fbc9-4508-8677-327a0b4d07cc">
