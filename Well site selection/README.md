# The choice of locations for wells

We need to decide where to drill a new well.
#### The steps for choosing a location are usually as follows:
* Characteristics for wells are collected in the selected region: oil quality and volume of its reserves;
* Build a model to predict the volume of reserves in new wells;
* Choose the wells with the highest value estimates;
* The region with the maximum total profit of the selected wells is determined.

We have oil samples in three regions. The characteristics for each well in the region are already known. We will build a model to determine the region where oil production will bring the greatest profit. Let's analyze the possible profit and risks using the Bootstrap technique.

## Data Description:
- id - the unique identifier of the well;
- f0, f1, f2 - three signs of points (it doesn't matter what they mean, but the signs themselves are significant);
- product - the volume of reserves in the well (thousand barrels).

## Task Requirements:
- Only linear regression is suitable for training the model (the rest are not predictable enough).
- During the exploration of the region, 500 points are explored, from which, using machine learning, the best 200 are selected for development.
- The budget for the development of wells in the region is 10 billion rubles.
- At current prices, one barrel of raw materials brings 450 rubles of income. The income from each unit of the product is 450 thousand rubles, since the volume is indicated in thousands of barrels.
- After assessing the risks, you need to leave only those regions in which the probability of losses is less than 2.5%. Among them, choose the region with the highest average profit.
