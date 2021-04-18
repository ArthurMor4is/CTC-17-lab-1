# CTC-17-lab-1
Development of intelligent agents in the subject of Artificial Intelligence in the Computer Engineering course at ITA-2020 (professor Paulo André Lima de Castro)

- q1.ipynb: Find the shortest path between Alice Springs and Yulara cities in Australia (australia.csv file), specifying the list of cities and also the distance from start to finish. The file has the following fields: city ID, x coordinate, y coordinate, state and population. The straight-line distance between cities can be calculated from the Cartesian coordinates (x, y) available in the Australia.csv file. A city with ID X connects with cities X + 2 and X-1, if X> 1 and X is even. If X is odd and X> 2, this city X connects with cities X-2 and X + 1. In this case the distance by the road is 10% greater than the distance in a straight line.

- q2.ipynb: Light up: Create an agent capable of solving the game called [Akari](https://www.chiark.greenend.org.uk/~sgtatham/puzzles/js/lightup.html). The game consists of a board (7x7). Some squares are black, some black squares have numbers. The goal is to 'light up' all white cells by placing lamps on them. Each lamp illuminates your home, but the line and column where it is positioned, unless a black house blocks the path. To solve the game, you must meet the following conditions:

    All non-black houses are lit up
  
    No lamp is illuminated by another lamp
  
    All numbered houses have exactly the number of adjacent lamps indicated (the houses above, below, left and right)
    
    Unnumbered black houses can have any number of adjacent lamps
    
    <img width="430" alt="Screenshot_1" src="https://user-images.githubusercontent.com/42987302/97128751-e8124780-171b-11eb-9698-7516d93d9ea7.png">
