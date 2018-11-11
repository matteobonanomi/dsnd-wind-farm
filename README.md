# Wind Farm Open Data Analysis

This repo provides a sample code that analyses raw data from a real wind farm and estimates some useful performance parameters. A simple Machine Learning model is built to predict wind turbine power output.
[ENGIE](https://opendata-renewables.engie.com/pages/home/) open dataset is used as a practice sample.

## Getting Started

### Prerequisites
* **Anaconda 3.6** or an equivalent Python 3.6 environment
* **Python 3.6** libraries: numpy, pandas, scipy, matplotlib, seaborn 


### Clone this repo
```
git clone https://github.com/matteobonanomi/windfarmopendata
```

### Download the dataset
The code is meant to work with windfarm open data provided by ENGIE and available at the following [URL](https://opendata-renewables.engie.com/pages/home/), but you can easily adapt it to any similar dataset from a real wind farm.

* [HERE](https://opendata-renewables.engie.com/explore/dataset/la-haute-borne-data-2013-2016/table/) you can find historical (2013 - 2016) raw data from 4 wind turbines. In the sample notebook, I used the options on the left panel to filter and download only data from one turbine (R80711). If you want to limit your analysis, you can dowload only specific years of historical data.
* More recent data ( 2017 - present) can be downloaded [HERE](https://opendata-renewables.engie.com/explore/dataset/la-haute-borne-data-2017-2020/table/)
* Read the [DESCRIPTION](https://opendata-renewables.engie.com/explore/dataset/data_description/table/) to understant the meaning of each feature.
* To know more about wind farm specifics, [HERE](https://opendata-renewables.engie.com/explore/dataset/static-information/table/) you find more details.

To download data, click on EXPORT panel on the upper side of the page, and select CSV as preferred data format. The code expects CSV file in input, but it can be easily adapted to read any kind of database format (SQL, json, Excel...).

Once you have downloaded the dataset, create a **data** folder inside the cloned repo folder and paste the CSV file inside it.

### Launch Jupyter Notebook

Launch Jupyter from your Anaconda terminal (or equivalent command line tool):

```
jupyter-notebook
```
Open the notebook **wind_turbine.ipynb** contained in the repo. Run it cell by cell to understand what is going on. Markdown and comments will help you understand each line of code and the most relevant conclusions you can make from every section of the notebook.

## Built With

* [Python](https://www.python.org/) - Python programming language
* [Jupyter](http://www.dropwizard.io/1.0.2/docs/) - iPython Notebook
* [Brackets](https://maven.apache.org/) - My favourite text editor

## Versioning

We use [Git](https://git-scm.com/) for versioning. Look for new available versions, check the [list of commits](https://github.com/matteobonanomi/windfarmopendata/commits/master). 

## Authors

* **Matteo Bonanomi** - [My GitHub](https://github.com/matteobonanomi)

## License

* This project is licensed under the GPL v3 License - see the [LICENSE.md](LICENSE.md) file for details
* If you are going to use [ENGIE](https://opendata-renewables.engie.com/pages/home/) dataset to practise, please notice that it has its own [LICENCE](https://www.etalab.gouv.fr/wp-content/uploads/2017/04/ETALAB-Licence-Ouverte-v2.0.pdf).

## Acknowledgments

* Acknowledgement is given to [ENGIE](https://opendata-renewables.engie.com/pages/home/) for providing such an interesting and well-documented sample dataset


