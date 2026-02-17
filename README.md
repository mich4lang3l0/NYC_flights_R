# # ✈️ NYC Flights Data Analysis (2013)

### 📊 Operational Efficiency and Factors Affecting Delays

## 📖 Overview
This project analyzes a dataset of over 336,000 flights departing from New York City airports (JFK, LGA, EWR) in 2013. The goal of this analysis was to identify key factors contributing to flight delays, evaluate airline performance, and provide actionable insights for passengers and operators.

**View full report in NYC_flights.html file**

## 🔍 Key Findings
* **Best Time to Fly:** Morning flights (before 10 AM) and mid-week days (Tuesday/Wednesday) offer the highest punctuality.
* **Seasonality:** There is a significant spike in delays during the summer holiday season (June-July) and December.
* **Weather Impact:** Visibility below 2 miles causes a drastic increase in departure delays.
* **Fleet Reliability:** The data indicates **no clear trend** suggesting that plane age is a significant factor. Average delays fluctuate across different ages without a definitive pattern, implying that maintenance schedules likely keep older aircraft just as reliable as newer ones in terms of punctuality.

## 🛠️ Tools & Technologies
* **Language:** R
* **Libraries:** `tidyverse` (dplyr, ggplot2), `nycflights13`, `lubridate`
* **Format:** R Markdown (HTML Output)

## 📈 Visualizations Highlights
All visualisations are available in the HTML file

<img width="957" height="391" alt="heatmap" src="https://github.com/user-attachments/assets/eeff5d98-37c5-4cc6-be2b-b7f99f21b101" />
> *Heatmap showing average delays by hour and day of week.*

<img width="918" height="479" alt="plane_age" src="https://github.com/user-attachments/assets/a4ed7dd2-8018-4cf7-bfb7-077fb179139d" />
> *Analysis of how plane age correlates with delays.*

## 💻 How to Run
1. Clone this repository.
2. Open `NYC_flights.Rmd` in RStudio.
3. Install required packages:
   ```{r}
   install.packages(c("tidyverse", "nycflights13", "lubridate"))
   ```


[*Created By Michał Węglorz*]
