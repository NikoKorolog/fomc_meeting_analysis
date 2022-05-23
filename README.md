# fomc_meeting_analysis

This code is meant for analyzing how the VIX reacts on the day of and days surrounding FOMC meeting dates
    The time-span is the past 5 years
    Data was gathered from CBOE for the VIX prices and using a data scraper to gather the FOMC meeting dates from the FOMC website
        The dates were gathered and cleaned in a jupyter notebook and then saves using %store so that it's available to other notebooks running on the same kernel
    Once the dates have been gathered, we look at % changes across 2 time spans:
        1) Open vs Close prices on the day of the meeting
        2) Close price the day before the meeting vs Close price the day after the meeting
    The % changes are plotted onto a Histogram
    The cumulative returns over time of the VIX on these dates is plotted as well
        Results show a normal distribution with the mean centered around 0% change and a long-right tail for specific events/outliers mentioned in the code

Technologies: pandas version 1.4.2, hvplot version 0.7.3, beautiful soup 4 4.11.1, requests 2.27.1, regex 2022.3.15

Installation Guide: Make sure you have the dependencies installed

Contributors: CBOE for the data, FOMC for the dates, Gabriel Paganin gpaganin@berkeley.edu www.linkedin.com/in/gabriel-paganin, Niko Korolog nikokorologmusic@gmail.com




