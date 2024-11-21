# 3D Cube Face Visualization Program

## Description
This Java program allows users to visualize different faces of a 3D cube by entering the cube's dimensions and its elements. The program provides an interactive menu to display specific cube faces, such as the front face, top face, bottom face, and back face. It serves as a learning tool for working with 3D arrays in Java, offering insights into matrix manipulation and data representation.

## Features
- **Dynamic Cube Size**: The cube size (n x n x n) can be specified by the user.
- **Flexible Input**: Accepts user input for cube elements dynamically.
- **Face Visualization**: Displays specific faces of the cube:
  - Front Face
  - Top Face
  - Bottom Face
  - Back Face
- **Interactive Menu**: Allows users to select which face to view through a menu-driven interface.

## How It Works
1. **Input the Cube Size**: Specify the size of the cube (X for an X x X x X cube).
2. **Provide Cube Elements**: Enter elements row by row for the entire cube.
3. **View Cube Elements**: The program displays all cube elements in a structured format.
4. **Choose a Face to Display**: Use the menu to view the desired face of the cube.
5. **Exit the Program**: Select an invalid option or exit explicitly to terminate.

## Usage
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Compile the program:
   ```bash
   javac cube3dusingfunct.java
   ```
3. Run the program:
   ```bash
   java cube3dusingfunct
   ```
4. Follow the prompts in the program to input the cube size, elements, and view faces.

## Menu Options
| Option | Description         |
|--------|---------------------|
| 1      | View the Front Face |
| 2      | View the Top Face   |
| 3      | View the Bottom Face|
| 4      | View the Back Face  |

## Example Input and Output
### Input:
- Cube size: `2`
- Elements:
  ```
  1 2 3 4 5 6 7 8
  ```
  (Entered as rows of a 2x2x2 cube)

### Output:
```
The cube elements:
1  2
3  4
5  6
7  8

MENU
1. Front face
2. Top face
3. Bottom face
4. Back face

Enter your choice: 1
Front face:
1   3
5   7
```

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
