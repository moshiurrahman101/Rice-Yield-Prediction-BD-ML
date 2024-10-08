# Rice Yield Prediction in Bangladesh Using ML Model

## Project Overview

This project aims to predict rice yield in Bangladesh using machine learning models. The dataset includes features such as average rainfall and pesticide usage, which are used to predict the crop yield. The project leverages multi-variable linear regression to provide accurate predictions for rice yield based on these features.

## Table of Contents

- [Project Overview](#project-overview)
- [Data Description](#data-description)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Data Description

The dataset used in this project includes the following columns:
- `year`: The year of the data record.
- `Value_x`: The amount of pesticide used (in units).
- `average_rain_fall_mm_per_year`: The average rainfall (in millimeters) per year.
- `Value_y`: The crop yield (in units).

## Installation

To run this project, you need to have Python and the following libraries installed:
- pandas
- scikit-learn
- matplotlib

You can install the required libraries using `pip`:

```bash
pip install pandas scikit-learn matplotlib
