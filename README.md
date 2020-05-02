# No-food-waste

Current report contains work with the dataset provided by "CODE" university partner "Metronom". "Metronom" is a part of the huge german retailer company "Metro". The data contains information from the one german store. Time interval of the data set - is a period between 1st to 31th of January 2020.

The main question of the report is how sales and shrinkage behave during the current period depending on the weekday, the main category of products, freshness. Results were achieved by exploratory data analysis, visualizations with Python libraries and statistical methods. By exploring the target variables, it was found that sales drops on Fridays, on contrary shrinkage takes the biggest part on Fridays. Fresh products take the main part compared to ultrafresh products. Also, we explored products with the highest shrinkage and sales. Having these results would be important for further study other time intervals and dependencies.

## Data

The data set was provided by one of the biggest german retail companies **["METRO"](https://www.metro.de/)** . It contains information about products for the one german department store. Data could not be shared openly due to non-disclosure agreement

## Reqired libraries:

- **[Numpy](https://www.numpy.org/)** ,
- **[Pandas](https://pandas.pydata.org/)** ,
- **[SciPy](https://www.scipy.org/)** ,
- **[SciPy.stats](https://docs.scipy.org/doc/scipy/reference/stats.html)** ,
- **[Seaborn](https://seaborn.pydata.org/)** ,
- **[Matplotlib](https://matplotlib.org/)** .

## Installation

You will need Python 3 installed on your computer.

Create virtual environment

```sh
python3 -m venv .venv
```

Activate virtual environment

```sh
source .venv/bin/activate
```

To install jypiter notebook, you can use pip −

```sh
pip install jupyter notebook
```

To install the latest releases of libraries, you can use pip −

```sh
pip install matplotlib seaborn pandas numpy scipy ipython
```

#### Running the project

- Run the following from the root folder:
  `jupyter notebook`
- Open the metro_project_irina_baeva-v1.ipynb file.
