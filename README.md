# Turtle-Race
🐢 **Code Description**:

This code simulates a fun turtle race game using Python's `turtle` module. Users can place bets on which turtle they think will win the race. The game displays a race between six turtles, each with a different color. Once the user places their bet, the race starts, and the turtles move forward randomly until one of them crosses the finish line.

🏁 **Specifications of the Code**:

1. **Setting Up the Screen**:
   - The screen is set up with dimensions 500x400 pixels.
   - The user is prompted to place a bet on a turtle by entering a color.

2. **Creating Turtles**:
   - Six turtles with different colors (`red`, `orange`, `yellow`, `green`, `blue`, `purple`) are created.
   - These turtles are positioned at the starting line with specific y-coordinates.

3. **Starting the Race**:
   - The race starts if the user places a bet.
   - The turtles move forward by a random distance between 0 and 10 pixels in each iteration of the loop.

4. **Determining the Winner**:
   - The race continues until one of the turtles crosses the finish line (x-coordinate > 230).
   - The color of the winning turtle is compared with the user's bet to determine if the user won or lost the bet.
   - A message is displayed to the user indicating the outcome.

5. **Ending the Race**:
   - The race stops, and the screen remains open until the user clicks on it to close.

🔧 **Note for Successful Implementation**:

For the successful implementation of this code, it is recommended to run it in an environment set up with a virtual environment (`venv`) or using an IDE like PyCharm, which is well-suited for Python development. This is because the code relies on the `turtle` module, which may require proper configuration and dependencies that are typically managed within a virtual environment. 
