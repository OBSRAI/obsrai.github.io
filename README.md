## Overview

OBSRAI introduces a novel benchmark tailored specifically for urban-specific challenges using geospatial vector data. This benchmark is crafted to facilitate the development and evaluation of geospatial models, aiding efforts in urban planning, mobility prediction, and environmental monitoring.

# Key Features
- **Open Data:** All datasets included in the benchmark are openly licensed, ensuring accessibility and transparency for research and commercial use.
- **Diverse Tasks:** The benchmark covers five distinct geospatial tasks to challenge and evaluate the versatility of spatial representation models.
- **Global Scope:** Datasets span multiple cities across three continents, providing a diverse testing ground for geospatial analytics.

# Benchmark Structure

The benchmark is organized into subpages for each specific downstream task, as described below:

## [Human Mobility Prediction](human-mobility-prediction/description.md)
- **Purpose:** To predict human movement patterns within urban environments using data from various mobility datasets.

| Rank | Model    | Dataset | Accuracy | Precision | Recall | F1 Score | Source/Reference |
|------|----------|---------|----------|-----------|--------|----------|------------------|
| 1    | Baseline | Geolife | 0.64     | 0.64      | 0.64   | 0.64     | OBSRAI Paper     |

## [Short-Term Rental Price Prediction](short-term-rental-price-prediction/description.md)
- **Purpose:** To forecast rental prices based on the features extracted from Airbnb dataset listings.

| Rank | Model    | Dataset | MAE   | RMSE  | Source/Reference |
|------|----------|---------|-------|-------|------------------|
| 1    | Baseline | Airbnb  | 95.96 | 275.12| OBSRAI Paper     |

## [Housing Prices Prediction](housing-prices-prediction/description.md)
- **Purpose:** To model housing market dynamics and predict property values using real estate data.

| Rank | Model    | Dataset                    | MSE                   | MAE                  | RMSE                | Source/Reference |
|------|----------|----------------------------|-----------------------|----------------------|---------------------|------------------|
| 1    | Baseline | House Sales in King County | 4.47 * 10<sup>11<sup> | 5.48 * 10<sup>5<sup>   | 6.61 * 10<sup>5<sup>  | OBSRAI Paper     |

## [Crime Activity Prediction](crime-activity-prediction/description.md)
- **Purpose:** To anticipate crime occurrences and patterns using historical crime data.

| Rank | Model    | Dataset            | MAE                  | MSE                 | RMSE                | Source/Reference |
|------|----------|--------------------|----------------------|---------------------|---------------------|------------------|
| 1    | Baseline | Chicago Crimes     | 2.95 * 10<sup>-2<sup>| 2.88 * 10<sup>-3<sup> | 4.92 * 10<sup>-2<sup> | OBSRAI Paper     |
| 1    | Baseline | Philadelphia Crimes | 3.30 * 10<sup>-2<sup>| 4.15 * 10<sup>-3<sup> | 5.91 * 10<sup>-2<sup> | OBSRAI Paper     |
| 1    | Baseline | San Francisco Crimes| 2.77 * 10<sup>-2<sup>| 5.03 * 10<sup>-3<sup> | 6.52 * 10<sup>-2<sup> | OBSRAI Paper     |

## [Time Travel Estimation](time-travel-estimation/description.md)
- **Purpose:** To estimate travel times based on taxi trajectory data, aiding in traffic management and urban planning.

| Rank | Model    | Dataset    | MAE  | RMSE | Source/Reference |
|------|----------|------------|------|------|------------------|
| 1    | Baseline | Porto Taxi | 54.81| 99.72| OBSRAI Paper     |

# OBSRAI Benchmark Leaderboard

Welcome to [the official leaderboard](leaderboard.md) for the Open Benchmark for Spatial Representations for Artificial Intelligence (OBSRAI). *Note: All results are provided by contributors and are verified to the best of our ability. For detailed methodologies and model descriptions, please refer to the linked papers or sources.*


# Accessing the Data

All data used in OBSRAI are available under open licenses, which means you can freely use, modify, and distribute the data as long as you adhere to the terms of the respective licenses. This approach fosters an environment of collaboration and innovation in the GeoAI community.

# Contribution Guidelines

We welcome contributions from the community to extend the datasets and tasks or improve the benchmarking framework. Please see our [contribution guidelines](contribution_guide.md) for more details on submitting data or proposing changes.


# License

All datasets incorporated in the OBSRAI benchmark are covered by their respective open licenses. Details of individual dataset licenses are available in the dataset documentation.
