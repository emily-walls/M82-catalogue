# M82-catalogue
Contains archival catalgoue (SOURCE_CAT.csv) of flux measurements for radio compact sources in M82 to accompany Walls et al. in prep. The code allows reproducability of an integrated or peak flux light-curve for a given source in M82.

Some example source names to use are: 41.95+57.5 and SN2008iz.
There will be a list of avaliable sources to choose from in the near future.

The code also produces a smaller output catalogue for the values extracted from the main catalogue for the source chosen.

The catalogue was last updated 13/4/2026.


Guidance for the catalogue:

SOURCE_NAME         - Source name, most names originate from B1950 naming convention 

RA_(J2000)          - Right Ascension in J20000 coordinates

DEC_(J2000)         - Declination in J2000 coordinates

JD_OBS              - Julian Date the observations occured on 

JD_ERROR            - Julian Date observation error 

YEAR_OBS            - Year the observations were taken in 

TOTAL_FLUX          - Total/Integrated flux measurment measured in mJy

ERROR_TOTAL         - Total/Integrated flux error measured in mJy

PEAK_FLUX           - Peak flux measurement measured in mJy/bm

ERROR_PEAK          - Peak flux error measured in mJy/bm

DIAMETER            - Diameter of remnant measured in mas

ERROR_DIAMETER      - Diameter error measured in mas

FREQ_OBS            - Frequency observations were conducted at measured in GHz

PAPER               - Paper that the measurements were obtained from 

RESOLUTION          - Resolution of the data obtained

OBSERVATIONAL_NOTE  - Any interesting observational notes
