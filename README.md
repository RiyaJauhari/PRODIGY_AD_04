# PRODIGY_AD_04
I have create the layout by creating 9 buttons within nested LinearLayouts and  even them out over the screen by adding the layout_weight attribute. Our player points and reset button will be in a RelativeLayout.
I have create a 2 dimensional array of buttons,  dynamically assign them with findViewById and set OnClickListeners on them by using a nested for-loop.
 Handle the clicks on our playing field, switch between players and implement a method that checks for a winner at the end of each turn, by going through all rows, columns and diagonals of our playing field and checking if one of them has 3 matching fields. An integer variable will count each round, so we know, that if we don't have a winner after 9 rounds, we have a draw.
I have take care of configuration changes (like an orientation change), by giving our TextViews and Buttons the "freezesText" attribute and saving our member variables in onSaveInstanceState and restore these values in onRestoreInstanceState so we don't lose our game progress.
Finish the winning logic by updating the player points and resetting the board and variables and we will also take care of draw situations.
Also I have implement a restart functionality, which resets our board, points and round count.
