# Optimization of Matching

*note: this project runs based on random generated data*

## Usage 1

Generate an assignment/matching between random generated student candidates and professors as well as their perferences to each other. Due to the lack of data, the course capacity is also random generated between 1 to 5.

`py methods.py --num_candidate m --num_course n --save_to PATH`

where m= number of candidates you would like to have and n= number of courses you would like to have.

## Usage 2

Compare different methods based on Monte Carlos Simulation and plot out figures into the folder `figures\numOfCandidates_numOfCourse_numOfSimulations`

`py methods.py --num_candidate m --num_course n --if_figure True --num_simulation k`

where m= number of candidates you would like to have and n= number of courses you would like to have. And k is the number of simulations you would like to run. A number greater than 100 is suggested.