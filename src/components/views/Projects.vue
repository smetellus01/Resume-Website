<template>

<div>
    <img class = "project-image-one" src = "@/assets/images/grid.png" />
    <div class="inner-content">
        <h2 class="heading"><b>Project One: A* Pathfinder</b></h2>

        <p class="paragraph">A* Search Algorithm is similiar to Dijkstra's Algorithm, allowing for the discovery of the shortest path. 
            This hueristic search utilizes the algorithm to find favoring vertices that are close the starting point on a 2D grid. </p><br>

        <p class="paragraph">In the standard terminology used when talking about A*, g(n) represents the exact cost of the path from the 
            starting point to any vertex n, and h(n) represents the heuristic estimated cost from vertex n to the goal. In the above diagrams, 
            the yellow (h) represents vertices far from the goal and teal (g) represents vertices far from the starting point. A* balances the two 
            as it moves from the starting point to the goal. Each time through the main loop, it examines the vertex n that has the lowest f(n) = g(n) + h(n).</p><br>
    </div>
    <img class = "project-image-one" src = "@/assets/images/tic-tac.png" />
    <div class="inner-content">
        <h2 class="heading"><b>Project Two: Tic-Tac-Toe</b></h2>

        <p class="paragraph">A* Search Algorithm is similiar to Dijkstra's Algorithm, allowing for the discovery of the shortest path. 
            This hueristic search utilizes the algorithm to find favoring vertices that are close the starting point on a 2D grid. </p><br>

        <p class="paragraph">In the standard terminology used when talking about A*, g(n) represents the exact cost of the path from the 
            starting point to any vertex n, and h(n) represents the heuristic estimated cost from vertex n to the goal. In the above diagrams, 
            the yellow (h) represents vertices far from the goal and teal (g) represents vertices far from the starting point. A* balances the two 
            as it moves from the starting point to the goal. Each time through the main loop, it examines the vertex n that has the lowest f(n) = g(n) + h(n).</p><br>
    </div>
    <img class = "project-image-one" src = "@/assets/images/project three.png" />
        <div class="inner-content">
        <h2 class="heading"><b>Project Three: Dynamic Song Playlist</b></h2>

        <p class="paragraph">A* Search Algorithm is similiar to Dijkstra's Algorithm, allowing for the discovery of the shortest path. 
            This hueristic search utilizes the algorithm to find favoring vertices that are close the starting point on a 2D grid. </p><br>

        <p class="paragraph">In the standard terminology used when talking about A*, g(n) represents the exact cost of the path from the 
            starting point to any vertex n, and h(n) represents the heuristic estimated cost from vertex n to the goal. In the above diagrams, 
            the yellow (h) represents vertices far from the goal and teal (g) represents vertices far from the starting point. A* balances the two 
            as it moves from the starting point to the goal. Each time through the main loop, it examines the vertex n that has the lowest f(n) = g(n) + h(n).</p><br>
    </div>

</div>

</template>

<style scoped>



/*-------------------------------------------*\
    CSS Normalisation 
\*-------------------------------------------*/

.project-image-one{
    border: 1px solid rgba(255, 2, 2, 0.1);
}

.heading {
    padding-bottom: 5px;
}
.inner-content {
    padding-top: 30px;
    padding-bottom: 30px;
}