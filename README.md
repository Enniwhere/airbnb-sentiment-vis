# airbnb-sentiment-vis
The repository for the paper PAPER_NAME that illustrates the end-to-end process of data cleaning, machine learning, and data visualization used to visualize Airbnb review sentiments.

## Data

Data is uploaded into the three folders amsterdam_data, berlin_data, and ml_data. Due to the large amount of space required, the data has been compressed into .7z files. In order to run the visualizations, the data files must be unpacked and changed into a .geojson format. After unpacking amsterdam_monthly.7z for example, the resulting csv-files can be transformed to geojson-files by running batch_csv_to_geojson.bat from the folder containing the csv-files.

## Code

The code was made with Python 3.7, and the required module versions can be found in requirements.txt. An Anaconda environment can be made from this file, which should cover all dependencies.

## Visualization

The visualization is implemented in the files amsterdam_visualization_with_review_text.html, amsterdam_visualization_without_review_text.html, berlin_visualization_with_review_text.html, and berlin_visualization_without_review_text.html. All visualization expect there to be data present in the amsterdam_data and berlin_data folders, and the data used for the visualization can be gotten by unpacking the X_monthly.7z files and running the batch_csv_to_geojson.bat files as indicated above. As the visualizations use a lot of data, there is a certain amount of lag as they start up, and this is especially true for the visualizations with review text. If this starting lag turns out to be too much, the more lightweight versions using the trimmed data can be used instead.