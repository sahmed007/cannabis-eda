# Exploratory Data Analysis of Marijuana Strains

This is an attempt to provide insights, similarities, and differences in regards
to marijuana strains with data provided from Leafly via Kaggle.

The primary goals of this project are to answer the following questions:

1. Can we augment this data set with a more categorized view of the strains? Currently, the dataset is only categorizable via plant (indica vs sativa vs hybrid).
2. Can we discover the profile differences between plant type? Are effects and flavors more heavily leaning towards one plant type than the other?
3. Can we find commonalities between strains that have a higher rating than those strains that have a a lower rating?
4. Can we find a correlation or key words in a strain's description that can result in a higher average user rating?

Assuming that the above questions are answered, it may be possible to create a recommendation engine.

4. Can we provide unique recommendations based on a user's flavor and profile preferences?

## Installation

Create a Conda environment and install the necessary dependencies.

```bash
conda create --name cannabis-eda python=3.10
```

Then activate:

```bash
conda activate cannabis-eda
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GPLv3](https://choosealicense.com/licenses/gpl-3.0/)