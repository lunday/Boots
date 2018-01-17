OPER 782 - Analytic Proposal Review \#1
================
Matthew Small
17 January 18

Section 1
=========

1.  Provide a short name (either a single word or an acronym) for the analytic you plan to develop.

Boots

1.  Provide a brief title (1-2 sentences) describing - at the 50,000 foot level - what your analytic does. Your title should be short and to the point, but should also be clear to an end user.

The analytic takes Defense Manpower Data Center(DMDC) data on troop numbers abroad for active duty military personnel and generates forecasts for the selected country or countries, provides accuracy statistics, a visual depiction of the forecasts including actual observed values, and projected troop numbers for the year or years of interest.

1.  Provide a description (2-3 paragraphs) of why this analytic data product will be useful for an end-user. This description should address the following points (where applicable).

<!-- -->

1.  Describe any of the features that your analytic will perform when complete

The features which my analytic will perform when complete are to import the data, tidy the data in the format popularized by Wickham, group the data by country, branch, order the data by year, convert the data to a zoo/time series object, implement forecast functions, plot the forecasts, provide accuracy metrics, provide forecast values, and range for years of interest

1.  Describe the typical end-user for whom this analytic is being developed

The typical end-users for whom this analytic is being developed are analysts at USTRANSCOM/JDPAC.

1.  Describe any specific knowledge/skills/abilities an end-user must have to use your analytic

Important knowledge/skills/abilities an end-user must have in order to utilize the analytic is a knowledge of forecasting techniques such as ARIMA, exponential smoothing, and possibly some dynamic regression models; however, the analytic will provide a basic description of what the model is and its key parameters and terms.

1.  If your analytic implements known statistical methods, specify them

The analytic implements autoregressive integrated moving average (ARIMA) forecasting models, simple exponential smoothing models, Holt models, and forecasting accuracy metrics

1.  If your analytic builds on existing statistical methods or **R** packages, specify them

This analytic is built upon packages: *forecast, ggplot2 and tidyverse*

1.  How will end-users access your analytic data product?

End-users will access the data analytic product via the internet.

1.  Are there any security concerns that need to be addressed?

All data are available from the unclassified, open-source database maintained by DMDC. There are no security concerns that need to be addressed.

1.  Are there any appearance/design constraints that your analytic must adhere to?

There are no appearance/design constraints that the analytic must adhere to, but the goal is to provide a clean design with easy to use graphical user interface.

Section 2
=========
