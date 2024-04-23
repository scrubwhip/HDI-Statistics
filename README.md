# HDI Statistics
## About
This repository is a collection of visualizations, sheets, and code that summarizes various aspects of the United Nations' Human Development Index (HDI) data. It includes four distinct visualizations of trends in HDI data, along with the datasets that led to them and documentation of the code that produced them.

## Sources and Contributions
>Where does the data come from?
>>The data used in this exploration includes two `CSV` files, both of which were sourced from [Kaggle](https://www.kaggle.com/), an online catalog of downloadable databases. The first is entitled ["Human Development Index and Components"](https://www.kaggle.com/datasets/rajkumarpandey02/human-development-index-and-components) and was uploaded to [Kaggle](https://www.kaggle.com/) by Raj Kumar Pandey in 2021. The second is entitled ["Countries by Continent"](https://www.kaggle.com/datasets/hserdaraltan/countries-by-continent) and was uploaded to [Kaggle](https://www.kaggle.com/) by Serdar Altan in 2022.

>How is each dataset used?
>>As acknowledged above, the repository includes a [comprehensive HDI and HDI components dataset](https://www.kaggle.com/datasets/rajkumarpandey02/human-development-index-and-components) and a [simple dataset](https://www.kaggle.com/datasets/hserdaraltan/countries-by-continent) of countries and continents of the world. As shown in the documentation of my code, the former is manipulated to describe how a country's HDI--particularly, its HDI rank in relation to others--can describe other variables, such as gross national income and life expectancy. The latter is a much smaller and simpler dataset, and it is used to group trends in the data by geographic region, or continent. For each, I used the Python coding language and [Google's Colab coding environment](https://colab.research.google.com/) to work with the data.

>Where can I find the original data?
>>The original data doesn't exist in this repository, but to find the original sets, you can navigate to the links above and download them for free from [Kaggle](https://www.kaggle.com/). 
## Purpose
>Who is it for?
>>This repository is intended for anyone generally interested in geographical data and statistics sorted by nation and continent. It could be useful specifically for political geographers, activist groups, government statisticians, economists, and other data analysts in general.

>Why is it useful?
>>The data I've compiled is helpful for many in the fields listed above, as it can help predict patterns in human development and show which regions or countries are particularly struggling or exceeding in a certain aspect of development.

## Findings
### Mean Life Expectancy at Birth and Mean GDI
![-mean-life-expectancy-at-birth-among-hdi-groups-](/visualizations/Life-Expectancy.png)
![-mean-GDI-among-hdi-groups-](/visualizations/GNI.png)

The data shows a negative correlation between HDI rank and both GDI per capita and Life Expectancy at Birth, suggesting that countries with a lower HDI experience shorter life expectancies and less income per person. 
### HDI by Country and Mean HDI by Continent
image
The world data doesn't show as obvious of a trend when sorted into countries. However, when averaged among continents, it appears that Africa and Oceania have less development, on average, than Europe and Asia.
>Limitations
>>I encountered some issues merging the two datasets to add a continent column describing the country. Some countries had different names in one dataset than their equivalent in the other, resulting in about 20 countries not being included in the dataset. To ensure this wouldn't affect the country map above, I manually transferred the data from the HDI and Components sheet to the new exported sheet. I wasn't able to use this completed dataset when separating countries by their continent attribute, though, and the average values shown in the visualization of HDI by continent may lack certain countries. 
## Navigation
After the README, to navigate through the repository:
* Go to the `HDI_Data_Project.ipynb` file, where I instruct the user through the process of manipulating the data.
* Next, navigate to the `data` folder, where you can find both complete datasets proceeding the changes made.
* If you would like to see the visualizations in more detail, go to the `visualizations` folder, where you can find them as `PNG` files.
* To edit the code yourself, simply download the `.ipynb` file, upload it to your preferred coding environment, and don't forget to upload the original `CSV` files as well, which you can download from Kaggle. 
## Contributors/Help
Made by Sam Leggett
>For help, call:
