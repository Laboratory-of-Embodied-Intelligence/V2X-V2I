# Overview
This project aims at implementing and optimizing a particular scenario for autonomous cars in an V2I environment. We provide the code and blueprints for a benchmark comparison between systems where most computations are done by an infrastructure (IS) rather than vehicles (V) and vice versa.

## Scenario
3 Vs are coming to a T-Crossroad (TC) from each of the three lanes. All Vs need to follow their trajectory which may or not involve switching lanes without stopping nor colliding with another V.
Each V can have different speeds and different starting points.

![scenario_skyview](/img/crossroad.jpg)

## Topics

-Speed control

-Prioritization

-Computation delegation

## Equipment
To implement our simulation, we work with the [Duckietown environment](https://www.duckietown.org/)

The list of parts we used to build our duckibots can be found [HERE](https://docs.google.com/spreadsheets/d/1EFZdp7jWYrYtLfghzxIXdRC1jXTrOBYyAdRAF_iJhaI/edit?usp=sharing).
