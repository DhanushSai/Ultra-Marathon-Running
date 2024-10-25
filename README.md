# Ultramarathon Race Records Analysis

## Project Overview

This project involves a comprehensive analysis of a large dataset containing ultramarathon race records from 1798 to 2022. An ultramarathon, also known as ultra distance or ultra running, is defined as any footrace longer than the traditional marathon length of 42.195 kilometers (26 miles). The dataset comprises a formidable collection of over **7.46 million race records** from **1.64 million unique athletes**, showcasing various distances and events.

## Data Description

The dataset includes the following columns:

- **Year of event (int64)**: The year the race took place.
- **Event dates (object)**: Dates associated with each event.
- **Event name (object)**: Names of the ultramarathon events, which can also provide country location information.
- **Event distance/length (object)**: Types of races (e.g., 50km, 100km, 50mi, 100mi) and lengths (e.g., 6h, 12h, 24h).
- **Event number of finishers (int64)**: Number of participants who completed the race.
- **Athlete performance (object)**: Performance metrics for each athlete.
- **Athlete club (object)**: Clubs associated with the athletes.
- **Athlete country (object)**: Country of each athlete.
- **Athlete year of birth (float64)**: Year of birth for each athlete.
- **Athlete gender (object)**: Gender of the athletes.
- **Athlete age category (object)**: Age classification of the athletes.
- **Athlete average speed (object)**: Average speed of athletes in km/h.
- **Athlete ID (int64)**: Unique numerical ID representing each runner.

## Dataset Source

The data used in this project is sourced from Kaggle. You can find the dataset at the following link: [Kaggle Ultramarathon Dataset](https://www.kaggle.com/datasets/aiaiaidavid/the-big-dataset-of-ultra-marathon-running).

## Methodology

### Data Cleaning
- Anonymized athlete names to comply with data protection laws, preserving privacy while maintaining a unique Athlete ID for valuable information.
- Handled missing values and inconsistencies in data types to ensure data integrity.

### Data Analysis and Manipulation
- Filtered the dataset to focus on **50km and 50mi races** among athletes from the **USA**.
- Extracted additional insights by deriving new columns, such as country location from event names and seasonal information from event dates.

### Exploratory Data Analysis (EDA)
- Conducted EDA using Python and Pandas to uncover trends and patterns within the dataset, focusing on metrics like average speed and performance based on gender and age.
- Created visualizations to present findings, showcasing the distribution of race lengths and athlete performance across various demographics.

## Conclusion

This project provides valuable insights into the ultramarathon running community, analyzing trends over two centuries of race records. The findings contribute to a better understanding of athlete performance and participation in ultramarathons, with a focus on specific distances and demographic factors.

## Technologies Used

- Python
- Pandas
- Matplotlib/Seaborn (for data visualization)
