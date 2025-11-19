# Cook's Ruler

A 150-line Python TSP heuristic that beats Nearest Neighbor by **+18.4%** on real US cities — in under one second.

No training.  
No parameters.  
Just geometry.

### Results

| Dataset                        | Cooks Ruler 2-opt (miles) | vs Nearest Neighbor |
|--------------------------------|---------------------------|---------------------|
| 100 US Cities                  | 25,188                    | **+18.4%**          |
| 1,000 Nationwide US Cities     | 33,374                    | **+17.2%**          |
| 1,000 Clustered (March 2023)   | 6,489                     | **+10.2%**          |
