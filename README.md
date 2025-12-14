<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

</header>

# Eco City Builder – README

Project Description
Eco City Builder is a command-line Java simulation game where players build a city by adding and removing various types of buildings. Each building affects the city’s Energy, Pollution, Happiness, and Well-being. The goal is to create a balanced, sustainable city and unlock different endings based on performance.

System Requirements
• Java Development Kit (JDK) 8 or higher  
• A command-line interface (Command Prompt, PowerShell, Terminal, or Bash)

No external libraries or frameworks are required.

File Structure
All Java files must be in the same folder:

Game.java  
City.java  
Buildings.java  
GreenPowerPlant.java  
CoalPowerPlant.java  
Park.java  
Residences.java
School.java  
Factory.java  
PublicTransport.java  
Shop.java  
PublicService.java  

How to Compile the Game (Command Line)
1. Open Command Prompt or Terminal.
2. Navigate to the src file in the project folder.

Example: cd path/to/EcoCity/src

3. Compile all Java files with:
 javac *.java

If there are no errors, “.class” files will be generated.

How to Run the Game
After compiling, start the game by typing:
java Game

This should launch the game in the terminal.

How to Play
1.	Select a building type from the menu.
2.	Select whether to ADD or REMOVE the building.
3.	Type the number of buildings you select.
4.	View your  city metrics and decide on any other changes you want to make
5.	When finished, select the finish option to end the game and to view your city statistics alongside your final ending.

Dependencies
This project uses only standard Java libraries (java.util.Scanner).
No external dependencies are required.

Assumptions and Notes
• All game files must be in the same folder.
• Building limits are enforced by the City class.
• Pollution is clamped to never display negative values.
• Percentages are capped between 0% and 100%.
• The game is designed to run in a terminal (text-based).


---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github) &bull; [Review the GitHub status page](https://www.githubstatus.com/)

&copy; 2024 GitHub &bull; [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT License](https://gh.io/mit)

</footer>
