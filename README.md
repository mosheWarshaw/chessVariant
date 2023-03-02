&nbsp;&nbsp;&nbsp;&nbsp;The basis of this variant is the idea of pieces getting their value (their movement capabilities) from the cell they land on. The purple cells transform the piece that was put into it into a different piece. kings and shields are the only pieces that won't transform. There's a button that the user can use to see what piece it will be turned into.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;The layout of the pieces stemmed from a distaste of chess's opening strategies. I didn't enjoy the slow beginning of matches that were forced upon players because their pieces were trapped behind a wall of pawns. By setting up the pieces in the corner the way I did I exploded chess's opening strategies while maintaining a wall of protection of pawns and a shield (your opponent has to get through a pawn or shield before they can kill a more important piece, unless they take the long way around which would also take more than one turn because of the corners they would have to go around created by the transparent cells).
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;However, once I put both sides facing each other from the corners they were too close to each other, cramping the 8 x 8 board size of traditional chess. Therefore, I decided to extend the size of the board to 11 x 11. This was the size needed to give enough space between players, but there was too much room on the side of the board, so I removed some corner cells. Instead of removing them and disrupting the visual of a square board I made the transparent to be clear that pieces can’t be placed on them.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;After I had completed the board's size and the pieces' setup it was time to decide what cells should be made purple, and what type of transformation they should do. It was the natural choice to make the cells the pieces started in be purple, especially since that would allow pawns to transform into more powerful pieces if they reached the other side (like in traditional chess). Then I had to decide how I wanted to place the purple cells that would be in the center of the board, as this would affect every strategy planned in every game played.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;I had first planned on having almost every cell be purple, but that was too unwieldly in practice to play with so many transforming cells. I instead created a square of purple cells in which the user can get from one to the other within 2 turn. The rook can get to the bishop purple cell by sliding left or right (depending on where it is), and the bishop can get to the rook purple cell by going to the prince purple cell and then with the prince’s movement abilities, jumping to the rook purple cell.
<br/>
<br/>
Regarding the changes to pieces:
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;I gave the bishop the extra ability of being able to move like a king because no one would be willing to put a rook on a bishop purple cell otherwise, and everyone would want to transform their bishops into rooks.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;The shield was created as a more efficient self-sacrificing pawn. It cannot kill another piece, and it can move like a king so it move better to actively be used to protect pieces.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;Regarding the queen, it would be too powerful a piece to allow players to create as much as they want of, so I couldn't allow any purple cells that would transform pieces into queens, and I eventually decided to remove the queen entirely from the game because it would be a piece that the purple cells would be a disadvantage to, because no one would want their queen to be transformed into any other piece. the purple cells were the basis of my variant, and the idea was for it to transform the game because of how people would incorporate it/from their strategies upon taking advantage of these purple cells.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;I removed the knight because it always seemed out of place. the king can move one at a time in any direction, the rook can move as far it wants in a horizontal or vertical direction, the bishop can move as far in any diagonal direction, etc., but the knight moves like an 'L'. It seemed so odd compared to the way the all the other pieces moved, and I was never able to appreciate them and use them to whatever their full capability was, so when I was making my own chess variant I decided that while I was at it I was going to remove the piece I didn't like.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;After removing the queen and the knight I had to add pieces to fill their gap, and I decided to create new pieces instead of adding more of the current pieces, because the user can already do that themself by using the purple cells. The prince (the crown without the cross) came about when I decided to create a piece that can jump over other pieces like the knight, and I decided to have a piece that could move like the king which moves in any direction, but instead of moving one cell at a time it jumps 2 cells.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;I then created the general (the Napoleon’s hat) by combining the king's and prince's movement abilities.
<br/>
&nbsp;&nbsp;&nbsp;&nbsp;I set the images of the pieces to note take up the full space of the cell when in a purple cell (hence the purple border around the pieces in them) because I want players to know if their piece would transform when killing an opponent’s piece.
<br/>
<br/>
What the board's set up is:
<br/>
![initialSetup](https://user-images.githubusercontent.com/113654579/221073067-4dbf6034-25a0-4b34-aba5-e4efdbdb7260.png)
<br/>
<br/>
**An example of what picking up a piece looks like:**
<br/>
Before:
![rookVisible](https://user-images.githubusercontent.com/113654579/221073058-e74e5bf3-ee7a-48ec-84ef-92072a5feb18.png)
<br/>
After:
<br/>
![rookPickedUp](https://user-images.githubusercontent.com/113654579/221073063-e29f835a-9ac8-4cda-b37b-41258b224136.png)
