# Sigma-Wedge-Hackathon
We aim at building a model that provides insights on when to buy the Apple stock, such that we obtain a maximum portfolio value.
The portfolio value depicts the total value of the stocks or assets which we own, thus the value increases when we transition from FLAT state to BULL state and decreases when we move from FLAT state to BEAR state.

STEPS:
            1) Firstly, we extract the dataset using the moonshot framework present in quantrocket.
            2) Then, we find the percentage of the dataset using pct_change() function.
            3) Next, we classify the data as BULL(1), FLAT(0) and BEAR(-1).
            4) After that, using the given conditions, we determine the portfolio value.
            5) Then, we try to find the transition matrix and then use it to determine the probability distribution matrix.


Output:

    Portfolio value:  17
    
    Optimal indices:  [5, 7, 11, 15, 20, 27, 29, 40, 49, 51, 58, 60, 68, 78, 84, 87, 93, 99, 102, 107, 109, 112, 116, 119, 122, 132, 141, 159, 163, 176, 186, 190, 206, 208, 211, 215, 217, 231, 233, 237]
    
    Probability Distribution matrix: 
     [[0.13888889 0.72222222 0.13888889]
     [0.14649682 0.59872611 0.25477707]
     [0.125      0.67857143 0.19642857]]
