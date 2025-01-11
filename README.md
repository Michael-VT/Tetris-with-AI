# Tetris-with-AI
Attempts to write game code using prompts to different AI systems.

<img src="2025.jpeg" alt="All the best in 2025!" width="200"/>

![All the best in 2025!](2025.jpeg?raw=true "Tetris from AI at start of 2025 year!")

I wrote a prompt and sent it to different AI systems, and saved the result in a file called Tetris-AI.html, where AI is the name of the AI ​​that created the game.

Here is the prompt that was set to generate the code:


It is necessary to write the HTML code of the Tetris game page with the game code in JavaScript with the following functionality.

If there is a history, restore the last history of players.

Then ask the name of the Player. And show the result of the last ten games.

Control the game using the drawn buttons under the glass (size of the glass, width 10 cells, height 20 cells) and keyboard buttons:

The space key and the start/pause button start or pause the game.

The left arrow and the left button move the figure to the left to the left wall.

The right arrow and the right button move the figure to the right to the right wall.

The up arrow and the rotate button rotate the figure 90 degrees in one click.

The down arrow and the lower button control the quick lowering of the figure down.

Escape on the keyboard and the restart button end the current game and start a new game with the current player name.

When a row of ten cells along the width of the glass is completely filled, the row disappears and the player is added to the earned score.

The pieces fall with a one-second delay when moving one square down.

After 100 pieces, the delay time is reduced by 10 percent.

When a piece cannot fall down (reaches the bottom or rests against a piece), the game ends.

If a piece touches the bottom of a glass or another piece when moving down, it remains in this position and a new piece begins to fall.

If a player's score exceeds the score of any of those recorded in the table, the player with the lowest score is removed from the table if there are more than 10 rows in it.

The current player's score is recorded in the sorted table, the highest score at the very top of the table.

At the beginning of the game, each piece is assigned a color and it must not change for this type of piece until the end of the game.

Display the current score on the right above the table.

The delay between moves at the beginning of the game is 1 second, and after 40 pieces, the delay must decrease by 10 percent.

The score assumes a point for each removed colored square from the removed row. Calculation of the score, the cell with the color being removed should be estimated based on the position number in the table of the figure with this color plus one and then the resulting value should be multiplied by 2.

And the score after deleting the row should be updated.

The figure that will fall next, the delay time and the current score of the player are shown under the table.

In the table, before the player's name, display the serial number of the place and after the name, display his best score.

The price is calculated as the sum of the prices of each removed square from the filled row and further, and the price of each removed square is determined based on the serial number of the figure in the table of figures.

Next, add one to the resulting value and multiply by an integer value from the value obtained as a thousand minus the current delay time in milliseconds divided by 10.

Constants in the script and variables should be declared before calling functions.


For example, const pieces - a table containing Tetris figures, should be placed immediately in the script after the declaration of the script, immediately after <script>. It is necessary to write the code in the form of one html page in accordance with the description above.


![This game is the best result that the AI ​​Deepseek-2 has given.](TetrisDeepseek.png?raw=true "Tetris made by Deepseek")

![This game is the best result that the Grok-2 AI has produced.](TetrisGrok.png?raw=true "Tetris made by Grok-2")

![This game is the best result that the AI ​​Mistral has given.](TetrisMistral.png?raw=true "Tetris made by Mistral")


As a result, I got pages with games.
