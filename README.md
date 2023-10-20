# Cricket-Score-Board

Creating a digital cricket score board project using React can be a fun and educational way to explore web development. Below is a description of how you might structure and implement such a project:

**Project Overview:**
The digital cricket score board project will be a single-page web application built using React. It will allow users to keep track of the score and other important details of a cricket match in real-time. The score board will display information such as runs scored, wickets fallen, overs bowled, and other statistics.

**Key Features:**
1. **Score Display:** The main component of the application will display the current score, including the total runs scored and wickets fallen.

2. **Overs and Balls:** There will be a component to keep track of the number of overs bowled and the number of balls bowled in the current over.

3. **Batsman and Bowler Details:** A section for displaying the names of the current batsman and bowler, along with their respective statistics, like runs scored and wickets taken.

4. **Runs and Wickets Input:** Users can input the number of runs scored in a particular ball and when a wicket falls. There should be an option to undo the previous action in case of an input error.

5. **Wagon Wheel and Manhattan:** You can include visual representations of where the runs have been scored on the cricket field (wagon wheel) and a Manhattan chart to show runs scored in different areas of the pitch.

6. **Match Status:** Display the current status of the match, such as "Innings Break" or "Match Ended."

**Project Structure:**
You can structure your project as follows:

- **src**
  - **components**
    - **ScoreBoard.js:** The main score board component.
    - **OversBalls.js:** Component for tracking overs and balls.
    - **BatsmanBowlerDetails.js:** Component to display batsman and bowler details.
    - **UserInput.js:** Component for user input of runs and wickets.
    - **WagonWheel.js:** Component for displaying the wagon wheel.
    - **ManhattanChart.js:** Component for displaying the Manhattan chart.
  - **App.js:** The main application component that composes the above components.
  - **index.js:** The entry point of your React application.

**Technologies:**
- React: For building the user interface.
- State Management (e.g., React Hooks or Redux): To manage and update the score and match details in real-time.
- CSS: For styling the components.
- Charting Libraries (e.g., Chart.js or D3.js): For creating wagon wheel and Manhattan chart components.

**User Interaction:**
Users will be able to interact with the digital score board by inputting runs and wickets, which will update the score and statistics in real-time. You can provide buttons or input fields for this purpose. Also, you can add features for toggling between different views like wagon wheel, Manhattan chart, and match status.
