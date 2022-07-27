# path_visualisation

->This is a path visualisation project in which A* algorithm is used to find the path between two points i.e(start,end).<br/>
->I have choosen A* because it finds shortest path from particular start-to-end points.</br>
->Dijkstra’s Algorithm works well to find the shortest path, but it wastes time exploring in directions that aren’t promising. Greedy Best First Search explores in promising directions but it may not find the shortest path. The A* algorithm uses both the actual distance from the start and the estimated distance to the goal.<br/>

How to visualise/User Guide:<br/>
*Click on a grid and the first click is taken as start point.<br/>
*Second click is taken as Choose an end point.<br/>
*With remaining clicks,create walls or obstacles in the path.<br/>
*Click space after creating the walls and wait for for the algorithm to find its path.<br/>
*The final path is purple path.<br/>

NOTE:<br/>
*Orange and cyan represents start and end points respectively.<br/>
*Black represents obstacles.<br/>
*After pressing space i.e in visualisation red represents the dead nodes and green represents active or epandable nodes.<br/>
*Finally purple represnts the path.<br/>
*Right click to clear the grid<br/>

References:<br/>
*https://www.redblobgames.com/pathfinding/a-star/introduction.html<br/>
*http://theory.stanford.edu/~amitp/GameProgramming/Heuristics.html<br/>
*https://devdocs.io/pygame/<br/>
