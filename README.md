# runplotting

Exploration in sourcing my Strava data (runs) into aggregate worldwide map — heatmap type thing. Implemented in Jupyter notebook, using VS CODE and conda terminal from my Data Mining class (INFO 3350). 

Pip installed certain geomapping packages to aid in this process. 

## Overall Plan
### Preprocessing: 
- Match Strava activity names to solely running or walking activities, can be done through simple SQL work or referencing Pandas as well.
- Prepare coordinates list from this, referencing only accepted files

### Map Implementation: 
- Reduce opacity so as to make map more readable and digestible.
- !ERROR! Explain other map textures to make this more simple, such as 'Stamen Toner' with correct attribution
- !ERROR, TBD! Different colors for respective runs (low priority)

### Potential Further Implementation?
- Using Strava CSV, simple linear regression in terms of run length, there's no average pace on provided CSV which is a shame
- Heat map by states, reference 2950 further geo packages, fortunately I have a good amount of coordinate data already accounted for.
- Callback to tokenization/ vectorization, topic modeling (unsupervised/ supervised) and make predictiosn based on my comments/ titles? Not a large sample size but could be fun and a callback/ review to class. 
