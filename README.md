# surfs_up

## Overview of Project

### Purpose
While on vacation in Hawaii, I had an idea of opening a "Surf n'Shake" shop.  I could use some of my savings; however, an investor will definitely turn my dream into reality.  I decided to reachout to an investor named W. Avy.  He really likes the idea but requires more information about temperature trends before committing to this idea.  W. Avy has requested temperature data for the months of June and December in Oahu, Hawaii. This will help determine if this business would be sustainable year-round.  The standard data analysis principles were used which includes; (1) Determine the number of rows and columns in the data; (2) Data types used; and (3) Is the data readable?

__Requirements for W. Avy__
- Temperature data for June months
- Temperature data for December months

## Resources

- SQLite
- A SQLite database named: hawaii.sqlite
  
## Results
After analyzing the data, I was able produce the required information for W. Avy.
 
The temperature data for the month of June is illustrated below.

![June Analysis](https://github.com/SheaButta/surfs_up/blob/main/Resources/JuneTemps.PNG)

The temperature data for the month of December is illustrated below.

![December Analysis](https://github.com/SheaButta/surfs_up/blob/main/Resources/DecemberTemps.PNG)

From the analysis above, I have identifed three (3) major points;
- The temperature in both June and December are in the low 70s.
- The high temperature of June and December are in the low to mid 80s.
- The standard deviation appears to be about 3 degrees from the mean.

From the analysis above, I have also identifed three (3) major __differences__;
- The count or number of "not empty values" has a difference of 183 between June and December.
- The min temperature in December is 56 and the min temperature in June is 64.
- 25% of the month in June, the temperature is below 70 degrees, whereas in December the 25% of the month the weather is above 70 degrees.
 
## Summary
The "Surf n'Shake" shop seems to be a sustainable business based on the data from June and December.  An average temperature in the low 70s for both June and December, seems to indicate surfing can be done year-round and if you can surf year-round, you can definitely eat ice-cream year-round.  There are two (2) additional weather queries that might provide some additional insight and strenghten this business plan; (1). A query on the precipitation in the month of June; and (2) a query on the precipitation in the month of December.
 
    
 
 
 
 
 
