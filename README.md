# viz_power_network_LMPs
Basic code to visualize DC Optimal Power Flow LMPs and congestion in a power grid. See how changing system parameters changes congestion and LMPs. Darker node color = higher generator capacity factor. Dashed red lines = that line is congested.
Uses CVXPY to solve the convex optimization problem and networkx to visualize.

![6 bus example](https://github.com/kyribaker/viz_power_network_LMPs/blob/main/6bus.png?raw=true)

Code is currently written for the 6-bus example from the paper ``Single-Settlement, Energy-Only Electric Power Market for Unpredictable and Intermittent Participants,'' by Pritchard, Zakeri, and Philpott, Operations Research 58(4), 2010.
