### Tour de France – Historical Competitiveness Analysis
#### Overview

The Tour de France is one of the most demanding endurance competitions in professional sports. With over a century of history, it provides a unique opportunity to analyze how elite performance and competitive balance have evolved over time.

This project explores how competitive the Tour has been historically by analyzing the time gap between first and second place in each edition.

#### Objective

To evaluate whether the Tour de France has become more competitive over time by:

Converting historical time differences into numerical values
Measuring the gap between 1st and 2nd place
Applying a 5-year rolling average to identify long-term trends

#### Data Preparation

The dataset required several cleaning steps:

Converting ranking values to numeric
Parsing time strings with different formats
Transforming time gaps into seconds and minutes
Handling missing values in historical records

#### Methodology
Extract second-place finishers by year
Compute time difference relative to the winner
Convert gaps to minutes
Apply a 5-year rolling average to smooth short-term volatility
Visualize long-term trends in competitiveness

#### Key Findings
Early editions (1900–1930) show large and volatile time gaps.
Mid-century races display increasing stability.
Modern editions show consistently smaller margins between 1st and 2nd place.

The rolling average reveals a clear structural shift toward tighter competition in recent decades.

#### Conclusion

The Tour de France has evolved from a race with large performance disparities to one characterized by marginal gains and high competitive parity.

This transformation likely reflects advances in training, team strategy, sports science, and technology.

#### Tools Used
Python
Pandas
Matplotlib

#### Project Structure
data/
images/
notebooks/
.gitignore
