## Project Proposal



## Question 
When a vancomycin aptamer sensor is quantified with a calibration curve built from other sensors, how much accuracy is lost, and is that loss smaller or larger than the loss from calibrating at the wrong temperature (room temperature vs. 37 °C)?

Electrochemical aptamer-based sensors are meant to work in a live subject without calibrating each sensor, so one calibration curve has to be shared between sensors. Sensors are often calibrated at room temperature, which brings up the question of whether that affects accuracy at body temperature.

## Data 

- **Source:** Downs, Alex (2022). Improved Calibration of Electrochemical Aptamer-Based Sensors. figshare. Collection. https://doi.org/10.6084/m9.figshare.c.5907050.v1. Accessed November 8, 2026.

- **Paper:** Downs, A. M.; Gerson, J.; Leung, K. K.; Honeywell, K. M.; Kippin, T.; Plaxco, K. W. "Improved calibration of electrochemical aptamer-based sensors." *Sci. Rep.* 2022, 12, 5535. https://doi.org/10.1038/s41598-022-09070-7

## Is the data sufficient?

- **How many observations are there?:**
- Figure 2A: : 4 sensors × 23 concentrations × 4 frequencies (10, 25, 30, 300 Hz) = 368 Voltammograms
- Figure 4A: same design as 2A just room temp = 368 Voltammograms
- Figure 2B: 4 sensors × 152 scans at 25 and 300 Hz; 6 vancomycin concentrations = - 1216 Voltammograms

- Total = 1,952 voltammograms
- **Variables:** 
- Each data file has 13 columns : potential, net/forward/reverse current per sensor
- Frequency (Hz), concentration (M), time (h)

- **What is missing?:** 
- The files have no column headers. I inferred the layout and checked it: net = forward − reverse matches for all four sensors.
- The Fig. 2B time file has 151 entries for 152 scans, so one timestamp is missing.

- **what you would do if the data turn out not to answer the question?:** 
- Choose a simpler topic using the same data: In the baseline data (the ten minutes before vancomycin) does the signal drift and does adding the two frequencies mitigate it
- Find another dataset







