# sa-alamo-heights-pd-2021

Graphs: https://app.datawrapper.de/archive/team/bzt6JZUO/95158

## Packages Required

```
library(tidyverse) ### for general data maniuplation
library(readxl) ### for reading Excel files
library(janitor) ### for cleaning data
library(lubridate) ### for working with dates
```

To install a package

```
install.packages("package-name")
```

The data is coming 


## About the files/How to Run this

Start with the "data-processing-cleaning.Rmd" file. This takes the dirty data that Alamo Heights PD provided and each incident has all of the proper offenses associated with it. 

Move to the "alamo-official-code-cleaning.Rmd" file. This looks at all of the codes that AHPD provided and categorized. 

Then go to "offense-cleaning.Rmd". Here we look at each offense rather than each incident and pair them to the AHPD codes. 

Finally, we do an analysis of the data where we ask questions looking at the priorities of each incident and the property crimes throughout the years. 



## Methodology: Story Version (still kinda long, though, I know)

The Express-News received data regarding every incident — and offenses associated with it — that the Alamo Heights Police Department had recorded between Jan. 1, 2011 and Dec. 31, 2021. Using police codes provided by the Alamo Heights Police Department, different offenses associated with an incident were counted to evaluate increases and decreases in different offenses over time. The Express-News also worked with Chief Richard Pruitt to correctly prioritize offenses into "very high," "high," "medium" and low priority categories and define specific offenses as property crimes. For this story, property crimes are defined as damage done to a person’s property, usually intentionally, and includes arson, burglary, criminal mischief, among other categories. Property crime does not include motor vehicle accidents, nor does it include robbery or other incidents in which a person is injured or threatened to be injured.

With the categorized offenses, Express-News classified an incident as "low," "medium," "high" or "very high" priority based on the highest priority associated with the incident's offenses. Pruitt said officers from AHPD, Terrell Hills Police Department or Olmos Park Police Department will respond to an incident with a medium prioritization or higher. 

