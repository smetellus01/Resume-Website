<template>

<div>
    <img class = "project-image-one" src = "@/assets/images/grid.png" />
    <div class="inner-content">
        <h2 class="heading"><b>A* Pathfinder (Python)</b></h2>

        <hr>

        <p class="paragraph">A* Search Algorithm is similiar to Dijkstra's Algorithm, allowing for the discovery of the shortest path. 
            This hueristic search utilizes the algorithm to find favoring vertices that are close the starting point on a 2D grid. </p><br>

        <p class="paragraph">In the standard terminology used when talking about A*, g(n) represents the exact cost of the path from the 
            starting point to any vertex n, and h(n) represents the heuristic estimated cost from vertex n to the goal. In the above diagrams, 
            the yellow (h) represents vertices far from the goal and teal (g) represents vertices far from the starting point. A* balances the two 
            as it moves from the starting point to the goal. Each time through the main loop, it examines the vertex n that has the lowest f(n) = g(n) + h(n).</p><br>            
    </div>
    
    <img class = "project-image-one" src = "@/assets/images/tic-tac.png" />
    <div class="inner-content">
        <h2 class="heading"><b>Tic-Tac-Toe (JavaScript)</b></h2>

        <hr>
            
        <p class="paragraph">A text-based version of Tic-Tac-Toe in Java played out on a 3x3 two-dimensional array gameboard. The program allows for the option to 
            play against a human or a computer. The outputs are in ascii text format and the user input is read in through strings.
        </p><br>

        <p class="paragraph">The computer player plays to a certain level of intelligence (i.e. no random moves)</p>

        <ol>
            <li>1. If a winning move is available, the computer will take it.</li>
            <li>2. If the opponent is threatening a winning play, the computer will block it.</li>
            <li>3. If the center square is available, the computer will take it.</li>
        </ol>

   </div>
    
    <img class = "project-image-one" src = "@/assets/images/project three.png" />
    <div class="inner-content">
        <h2 class="heading"><b>Dynamic Song Playlist (C++)</b></h2>

        <hr>

        <p class="paragraph">A program consisting of two classes, a Playlist class which will dynamically manage an allocated array of song objects.
            The playlist class manages the playlist through insertion and deletion of songs. The song class creates song attributes such as category,
            style, song, and artist. With the role of dynamically allocated memory, the program supports array resizing when unused slots go above five in the array.
            The program also supports an interactive playlist menu as shown above, which supports nine user commands.
        </p><br><br>
        
        <!-- Repositoty Links -->
    
        <div class="body-content">
        <a style="color: #0000FF;" href="https://github.com/smetellus01/Pathfinder-Visualizer" target="_blank" class="paragraph">Pathfinder Repository</a>
        
        <div class="body-content">
        <a style="color: #0000FF;" href="https://github.com/smetellus01/COP3252/tree/main/Project%203%20-%20Tic%20Tac%20Toe%20Game" target="_blank" class="paragraph">Tic-Tac-Toe Repository</a>
        
        <div class="body-content">
        <a style="color: #0000FF;" href="https://github.com/smetellus01/Dynamic-Song-Playlist" target="_blank" class="paragraph">Song Playlist Repository</a>
    
    </div>

    </div>

</div>

</div>

</div>

</template>

<style scoped>



/*-------------------------------------------*\
    CSS Normalisation 
\*-------------------------------------------*/

.project-image-one{
    position: absolute;
    top: 20px;
}
.heading {
    padding-bottom: 5px;
}
.inner-content {
    padding-top: 30px;
    padding-bottom: 30px;
}