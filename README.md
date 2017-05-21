# Sliding-Tile
The Sliding Tiles Puzzle was created by chess player and puzzle maker Sam Loyd (1841-1911) in the 1870s. The puzzle consists of a N x M board shown in Figure 1, where each cell could be represented as a number, a letter, an image or basically anything you can think of.



![alt tag](https://visualstudiomagazine.com/articles/2015/10/30/~/media/ECG/visualstudiomagazine/Images/2015/10/1015vsm_Castano1Fig1s.ashx)


Moving Tiles from Start Configuration, so as to reach the End Configuration

![alt tag](https://visualstudiomagazine.com/articles/2015/10/30/~/media/ECG/visualstudiomagazine/Images/2015/10/1015vsm_Castano1Fig2s.ashx)

The End Configuration can be achieved only when the Start State is solvable.

The Start Configuration  is solvable if it satisfies the following conditions:
 
 i. If the width is odd, every solvable state has an even number of inversions.
 ii. If the width is even, every solvable state has: 
 
    a) an even number of inversions if the empty tile is on an odd numbered row counting from the bottom; 
    b) an odd number of inversions if the empty tile is on an even numbered row counting from the bottom.
