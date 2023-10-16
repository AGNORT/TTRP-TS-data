# TTRP-TS-data
Instances and detailed results for the TTRP-TS. This respository contains the small and large instances for the TTRP-TS, the detailed computational results are also provided.
## 1. The description for the small scale instances

“***n***” denotes the number of the total customers

"***m***" denotes the number of the FCs

"***kt***" denotes the number of  the combination truck

"***ut***" denotes the number of the pure truck

"**Q1**" denotes the capacity of the combination truck

"***Q2***" denotes the capacity of the pure truck

"**q**" denotes the cargo demand of all customers

"**s**" denotes the service time needed by all customers

"**e**" and "**l**" denote the lower and upper bound of the customers' time windows

"**d**" denotes the Euclidean distance for all the vertices in the network

## 2. The description for the large scale instances
The large scale source data has been derived from the research article titled "Branch-and-price and adaptive large neighborhood search for the truck and trailer routing problem with time windows," authored by Parragh, S. N., & Cordeau, J. F.  The DOI for the article is https://doi.org/10.1016/j.cor.2017.01.020. Gratitude is extended to the authors for graciously sharing the source data with us.
The numbers in the first line are Truck Capacity, Trailer Capacity, Number of Customers
The numbers in each of the subsequent lines are Customer Number, X-coordinate, Y-coordinate, Demand, Indicator of Truck Customer (1 = TC, 0 = VC)
The 2nd line is for the depot (node 0) so the last two numbers in the line can be ignored.

## 3. The detailed results for the TTRP-TS

The detailed computational results for both small and large-scale instances are presented in the following format:

"**Route\*:** " indicates the route indexed by "*" with subsequent sequence information.

"**Swap operation:**" provides the swap plan for emptied trailers in each instance. The statement "No emptied trailers swap operation!" signifies the absence of emptied trailer swaps in the optimal solution.

"**Cost:**" indicates the cost of the best solution discovered.












