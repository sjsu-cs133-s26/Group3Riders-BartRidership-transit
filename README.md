# The New Commute: Realigning BART Schedules to Post-Pandemic Realities
A data analysis project examining how COVID-19 permanently shifted Bay Area transit habits, using BART origin-destination ridership data from 2019 to 2022.

## Team Members
- Sukhjot Singh
- Zachery Byrd
- Olsen Arliawan
- Adam Abramyan
- Hieuson Dang

## Dataset - [BART Ridership on Kaggle](https://www.kaggle.com/datasets/mrgeislinger/bart-ridership)
 - This dataset contains the detailed hourly ridership numbers for the Bay Area Rapid Transit (BART) system. It is sourced directly from BART's origin-destination portal and was updated until 2023. It captures the specific flow of passengers between any two stations for every hour of operation, offering a view of transit habits over more than a decade.

## How to Run
1. Download the dataset zip file from [Kaggle](https://www.kaggle.com/datasets/mrgeislinger/bart-ridership)
2. Open `Project_Assignment_Final.ipynb` in Google Colab
3. Either:
   - **Option A:** Upload the zip file directly into the Colab session when prompted by the upload cell
   - **Option B:** Upload the zip file to your Google Drive and mount Drive in the notebook
4. Run all cells sequentially
5. The interactive dashboard will render at the bottom — use the dropdowns to select a station and era

## Project Structure
```
├── data/
├── notebooks/
│   └── Project_Assignment_Final.ipynb
├── reports/
│   └── Final_Write_up.pdf
├── .gitignore
└── README.md
```

## End Goal
- We hope our product may identify inefficiencies within the BART system and provide scheduling recommendations, identifying travel patterns to help riders avoid crowding and helping planners identify underutilized routes.
