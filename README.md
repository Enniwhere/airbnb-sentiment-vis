# airbnb-sentiment-vis
The repository for the paper PAPER_NAME that illustrates the end-to-end process of data cleaning, machine learning, and data visualization used to visualize Airbnb review sentiments.

## Data

Data is uploaded into the three folders amsterdam_data, berlin_data, and ml_data. Due to the large amount of space required, the data has been compressed into .7z files. In order to run the visualizations, the data files must be unpacked and changed into a .geojson format. After unpacking amsterdam_monthly.7z for example, the resulting csv-files can be transformed to geojson-files by running batch_csv_to_geojson.bat from the folder containing the csv-files.

## Code

The code was made with Python 3.7, and the required module versions can be found in requirements.txt. An Anaconda environment can be made from this file, which should cover all dependencies.
