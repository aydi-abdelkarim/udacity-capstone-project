
# Udacity project - Sparkify

## Acknowledgements
Many thanks to Udaicty for curating such data set and providing an excellent learing experience !!

## Motivation:
This repository contains my companion notebook to my Capstone project blog post [here](https://medium.com/@aaydi1977/enhance-your-customer-satisfaction-using-spark-478766115cd8). The objective is to build a churn detection system for an online music service called Sparkify.

## Project structure
```
├── data
│   ├── processed
│   │   └── agg_logs
│   │       ├── *.parquet					# Cached preprocessed dataset 
│   └── raw							# raw data set	
│       ├── meta_data.csv
│       └── mini_sparkify_event_data.json
├── figures							# Figures
│   ├── bivar_elapsed_days_churn.png
│   ├── bivar_gender_churn.png
│   ├── bivar_length_sum_churn.png
│   ├── bivar_song_count_churn.png
│   ├── bivar_state_churn.png
│   ├── missing_value_stats.png
│   ├── uni_gender.png
│   ├── uni_level.png
│   └── uni_state.png
├── notebooks							# Main notebook
│   └── Sparkify project.ipynb
├── README.md	

```

## Dependencies
In this work, I used these libraries along with Python=3.7.4:
- pandas
- matplotlib
- scikit-learn
- seaborn
- pyspark

