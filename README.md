# Superheroes player stats

We have just launched our brand new superheroes game and have been collecting the user stats from the last few days. This repo contains some of the initial raw data. We need to run some basic processing on the data in preperation for analysis. You are welcome to use any tecnology, most people approach this with Jupyter notebooks and pandas.

### Data processing

Using the small CSV datafile. Write a simple python program that processes the data and writes the outout to another CSV file. Be sure to exclude people with nonsensical data. Processing includes:

- Anonymise any personal data for each person
- Add unique ID's for each person
- Calculate the age of each person
- Some peoples age may be incorrect or impossible, we should filter these out
- Test the program against the larger CSV file

The output should look something like:

| UID  | First name | Last name | Address | Age | 
|------|------------|-----------|---------|-----|
| 1234 | xxxx       | xxxx      | xxx xxx | 31  |
|      |            |           |         |     |

Following on from this discuss how you would implement this in a data bricks cluster or Azure Data Factory and what you would do to productionize the processor.

[Small datafile](https://raw.githubusercontent.com/BuildCircle/python-data-test/main/src/example_data_small.csv)

[Large datafile](https://raw.githubusercontent.com/BuildCircle/python-data-test/main/src/example_data_large.csv)

Finally calculate the median average & 95th percentile age of our playerbase from the large processed dataset
