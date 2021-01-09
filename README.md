# Homework 6: Pythonic Monopoly

The [Rental Analysis](rental_analysis.ipynb) notebook visualizes:

1. Average housing units per year
2. Average gross rent per year
3. Average sales price per square foot per year
4. Top 10 most expensive neighborhoods by average sale price per square foot
5. Average sale price per square foot by neighborhood
6. Parallel coordinates and categories plots of the top 10 neighborhoods

The [Dashboard](dashboard.ipynb) notebook displays a dashboard of all the visualizations present in the Rental Analysis notebook. To view the dashboard in the browser, run the following steps:

1. In the command line, clone this repository: `git clone git@github.com:meowyen/hw6-pythonic-monopoly.git`.
2. Navigate to the directory of the cloned repository: `cd hw6-pythonic-monopoly`;
3. Activate your Anaconda environment. For example: `conda activate pyvizenv`.
4. To display the dashboard in the browser, run the following command: `panel serve dashboard.ipynb --log-level debug --show`.
5. The command from step 4 will automatically open the dashboard in the browser. If not, you can get the URL from the output of the command. It will look something like this: `Bokeh app running at: http://localhost:5006/dashboard`.