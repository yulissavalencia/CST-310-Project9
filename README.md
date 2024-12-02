Dayana Gonzalez Cruz & Yulissa Valencia
CST-310: Graphics
Project 9: Advanced Shaders
December 1st, 2024
TR1100A Prof. Citro

Running the Project in Linux Terminal

1. Ensure you have a Linux terminal instance open (e.g., WSL, Ubuntu).
   
2. Verify the Project File is in the Current Directory  
   - Use the `ls` command to list files in the current directory:
     ```bash
     ls
     ```
   - Check that your project file (`main.cpp`) is listed in the output. If it’s not, navigate to the correct directory or move the file into the current directory.

3. Compile 

   - Use the following command to compile the project:
     ```bash
     g++ -o Project9 main.cpp -lGL -lGLU -lglut -lGLEW -lglfw -lSOIL -lassimp
     ```

4. Run the Simulation

   - Execute the compiled file to launch the domino simulation:
     ```bash
     ./Project9
     ```

   - A window should pop up displaying the simulation.

5. Interact with the Simulation

   - Use arrows to move up, down, left, and right

6. Exit the Simulation

   - Use `Ctrl + C` in the terminal to close the program if needed.

