# From Data To Success
*How to Transform Raw Data Into Tangible Results*

> ***This repository was built as part of a workshop for the WIDS (Women in Data Science) Córdoba 2023 edition. During the workshop we will use [this Colaboratory notebook](https://drive.google.com/file/d/1P0LG10-NtamcRewz37AWMGUNiaXU_neX/view?usp=sharing)***

## Repository Project Organization

------------------

1. Download and install Miniconda3

2. Create env from yml file

    ```shell
    conda env create -f environment.yml
    ```

3. Activate env

    ```shell
    conda activate food_demand_forecasting
    ```

4. To run notebooks, download data [from this Kaggle dataset](<https://www.kaggle.com/datasets/kannanaikkal/food-demand-forecasting?select=train.csv>) and save all csv available files to `/1_Data/0_Raw/*`

---------------

## Dataset Description

The following details can be found in the dataset description at Kaggle. I took the liberty of making slight modifications to the wording.

### Context
The data corresponds to a meal delivery company which operates in multiple cities. They have various fulfillment centers in these cities for dispatching meal orders to their customers. The client wants you to help these centers with demand forecasting for upcoming weeks so that these centers will plan the stock of raw materials accordingly.

### Content
First of all, the replenishment of majority of raw materials is done on weekly basis and since the raw material is perishable, the procurement planning is of utmost importance. Secondly, staffing of the centers is also one area wherein accurate demand forecasts are really helpful.

### Objective
Given the available information, the task is to predict the demand for the next 10 weeks (Weeks: 146-155) for the center-meal combinations in the test set.

## Available Variables
Here is a list of the available variables in the different datasets:

- Week (just a reference number, not a date)
- Center ID
    
    - City code
    - Region code
    - Center type
    - Operational area

- Meal ID
    
    - Category
    - Cuisine

- Checkout price
- Base price
- Emailer for promotion
- Homepage featured
- Number of orders