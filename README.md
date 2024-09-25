# AI4Casting Hub  
Welcome to the AI4Casting Hub, an innovative initiative under the College of Engineering and Physical Sciences (CEPS) at the University of Guelph. Our mission is to drive the future of public health forecasting and preparedness. Anyone interested in using these data for additional research or publications is requested to contact **forecasts@ai4castinghub.com** for information regarding attribution of the source forecasts.

## Epidemic Forecasts for COVID-19, RSV, and Flu  
At the AI4Casting Hub, we provide continuous epidemic forecasts to support public health planning and pandemic preparedness. Using mathematical, statistical, and computational models, we forecast both endemic and emerging diseases. Our work is backed by Ontario Public Health, the CDC, and several prominent Canadian researchers.

**Dates:**  
The Challenge Period will begin **November 1, 2024**, and will run until **April 30, 2025**. Participants are asked to submit **weekly forecasts of disease cases and hospital occupancy** by **5:00 PM EDT on Mondays** (referred to as the Forecast Due Date). In the event that timelines of data availability change, **AI4Casting Hub** may adjust the forecast submission day. Participants will be notified at least one week in advance if this occurs. **Weekly** submissions (including file names) will be specified based on the reference date, which is the Saturday following the Forecast Due Date. The reference date is the last day of the epidemiological week (EW), defined as Sunday to Saturday.

**Prediction Targets:**  
Participating teams are asked to provide **regional and national** predictions for the following targets:

- **Incident infections**: The number of positive tests, either summed across COVID-19, RSV, and flu, or provided separately for each.
- **Hospital bed occupancy**: Either summed across the three diseases or provided separately for each.

Geographical regions of interest include **Ontario, Quebec, British Columbia, the Prairies, Atlantic Canada, Territories, and Canada as a whole**. For Ontario, forecasts can be broken down by individual regions. 

Teams are encouraged to submit forecasts for the epidemiological week (EW) ending on the reference date, as well as for **-1, 0, 1, 2, and 3-week horizons**. While not mandatory, teams may choose to submit forecasts for all locations and horizons. The evaluation data for forecasts will be the **weekly aggregate of confirmed cases and hospital occupancy data**. The target end date for a prediction is the Saturday that ends an EW of interest, and can be calculated using the formula:  
**target end date = reference date + horizon * (7 days)**.

There are standard software packages to convert from dates to epidemic weeks and vice versa (e.g., [MMWRweek](https://cran.r-project.org/web/packages/MMWRweek/) and [lubridate](https://lubridate.tidyverse.org/reference/week.html) for R, and [pymmwr](https://pypi.org/project/pymmwr/) and [epiweeks](https://pypi.org/project/epiweeks/) for Python).

If you have questions about this target, please reach out to **Dr. Monica Cojocaru** (**monica.cojocaru@uoguelph.ca**).

## Acknowledgments  
This repository follows the guidelines and standards outlined by the [hubverse](https://hubdocs.readthedocs.io/en/latest/), which provides a set of data formats and open-source tools for modeling hubs.
