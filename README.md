This project forked from the React tutorial.

My additions:
- Draw message. 
Because the initial React tutorial does not have a draw message and still prompted the next player to play even after a draw, I chose to add this feature. I modified the calculateWinner function to output the Draw! message if no squares left is empty. 

- Take backs:
I know that the tutorial already includes buttons to go back to move #n, but I still added this features because it's more intuitive and is easier to use for the user. The goal is to be able to take back by clicking directly on the 'x' or 'o'. I did this by modifying the handleClick function, adding a condition that if an occupied square is clicked on, its value returns to 'null'. 