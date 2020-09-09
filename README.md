# Air-Cargo-Load-Planning-Problem
This is a greedy algorithm for the Air Cargo Load Planning Problem.

The goal is to take pallets and put those pallets onto planes to try and minimize the difference in the CoG from the empty aircraft.
This is done greedily because when talking with air cargo loaders, the priority is the most important part. If there are 3 types of
priority (1,2, and 3) the priority 1 pallets will be put on the next plane no matter what. If there is a priority 1 pallet that just got to the depot, and there is a priority 2 pallet that has been in the bay for over 600 hours, the priority 1 pallet will still go first. This makes it hard to do any kind of optimization, so I decided to do a greedy heuristic that took in the pallet weight, assigned it to a plane, and then configured the pallets in the plane with the intent of minimizing the change in the Center of Gravity. All data is fake data.


