# Diamonds are analyst's best friends
![Image](https://user-images.githubusercontent.com/63467553/88570093-c7aef000-d03b-11ea-8019-8f413cf62cf7.png)


## Motivation :blush:
*This is my second project within the Ironhack Analytics Bootcamp (Part time version) in Madrid.*

## Overview :gem:
The objective of this project is to analyse if the price of **diamonds** varies depending on their 4Cs and if there are any specific variables to be taken into account that affect diamond price more than others. It is important to have the knowledge background as following in order to understand the basics of this database:

- **Carat:** It refers to the diamond's weight, not size. The price of a diamond does not increase linearly with the increase of the catat. Carat weight is not related to a better diamond, the cut is. 
- **Cut:** A diamond's cut is crucial to the stone's final beauty and value. It takes into account the design and craftsmanship of the diamond, including its weight relative to its diameter. The most important factor of all the 4Cs.
    - Premium
    - Ideal
    - Very good
    - Good
    - Fair
- **Color:** The color of a diamond is scaled within the GIA color grading system. It defines the colour of the diamond. The most colorless is D and it goes to Z. 
    - D: Colorless
    - E: Colorless
    - F: Colorless
    - G: Near colorless
    - H: Near colorless
    - I: Near colorless
- **Clarity:** Is the assessment of small imperfections on the surface and within the stone. Diamond shape and size affects clarity. 
    - IF: Internally flawless (100% free of inclusions - less than 1% of all diamonds are FL clarity)
    - VVS1, VVS2: Very very slightly included (diamonds have minuscule inclusions that are difficult even for a trained eyes to see under 10x magnification)
    - VS1, VS2: Very slightly included (minor inclusions ranging from difficult (v1) to somewhat easy (v2) to see at 10x magnification)
    - SI2: Slightly included (Inclusions are noticeable at 10x magnification. SI diamonds are often best value)
    - I1: Included (clarity have obvious inclusions that are likely to be visible and impact beauty)
- **Depth:** It is important because the depth of the diamond will affect how much light is reflected back to the observer. *A diamond with an ideal depth will reflect most of the light that comes into the diamond.* The ideal depth would be between 59% and 62,3%
- **Table:** A diamond's table is the flat facet on its surface - As the largest facet on a diamond, the table plays a major role in determining how brilliant (sparkly) the diamond is. A bigger table isn't necessary better. The ideal table would be between 53% and 68%
- **Price:** The total price of the diamond
- **X:** Lenght of the diamond
- **Y:** Width of the diamond
- **Z:** Height of the diamond

---

## Data sources :scroll:
 - Database with diamond details and list
    - Provided by [Ironhack](http://www.potacho.com/files/ironhack/diamonds_train.csv) formatted as a `.csv` file.

## Requirements :arrow_forward:

You will need to install and import or have already installed and imported the following Python libraries in order to be able to analyse the data:
- Data analysis:
    - Pandas
- Data visualisation
    - Seaborn
    - Matplotlib
    - Plotly
    - Plotly express
    
## Folder structure :open_file_folder:
```
└── project   
    └── data
        ├── diamonds_train.csv
    ├── notebook
        ├── data_analysis_report.ipynb
    ├── .gitignore
    ├── tableau_public_link.txt
    ├── README.md
    ├── requirements.txt
```

## How to use :electric_plug:
Download the databse provided and commit cells for visualisation deploy locally. 

## Examples of some study graphs :tada:
An example of the input that you will be able to retrieve is the following:

### Distribution of price and carats

![Image](https://user-images.githubusercontent.com/63467553/88977832-d9ec9080-d2be-11ea-9963-a635d711343a.png)

### Heatmap with relationship between all numerical values

![Image](https://user-images.githubusercontent.com/63467553/88977835-da852700-d2be-11ea-96d4-24e1813e5ae8.png)

### Distribution of clarity versus price

![Image](https://user-images.githubusercontent.com/63467553/88977837-db1dbd80-d2be-11ea-91f0-6afdef1c551f.png)


## Conclusions :pushpin:
After carefully analysing the dataset provided, we can conclude the following assumptions:
There is a strong correlation in the price-carat result. Obviously in broad knowledge assumption carats are the most marketer term used for diamond standards, thus, probably they're being used in this sense in order to setting the price, however, after researching, cut is actually the most important factor of all 4Cs.

In all variables, the prices of the diamonds reach the maximum level. Meaning, you need to choose carefully the diamond values as you can fall into a increased price discrimination in terms of the diamond quality.

According to the research, the cut is the most important factor of all 4Cs, however, most of the ideal cuts fall within 1 - 1,5 carat value.

Recommendations for a potential buyer:
Analyse other factors apart from the carats, it might be worth to try finding a diamond with an Ideal cut, falling within 1 and 1.5 carats and D or E colors.

## Tableau Public Dashboard :chart_with_upwards_trend:
- A Tableau Public dashboard has also been created, which can be accessed through this link: https://public.tableau.com/profile/sandraa91rg#!/vizhome/Project_module_2/Historia1
