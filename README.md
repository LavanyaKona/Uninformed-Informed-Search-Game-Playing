# Uninformed-Informed-Search-Game-Playing
The program will compute a route between the origin city and the destination city, and will print out both the length of the route and the list of all cities that lie on that route. It should also display the number of nodes expanded and nodes generated.


Graph Search for Finding Routes Between Cities

**Objective**

The objective of this assignment is to implement a search algorithm that can find a route between any two cities. You will create a program called find_route that takes command-line arguments to perform this task.

**Programming Language:** Python 3.10.5

### File Naming Convention

- Program file name: `find_route.py`
- Input file: `input1.txt`
- Heuristic file: `h_kassel.txt`

### Instructions for Running the Program

1. **Organize Files:**
   - Save all program files in a dedicated folder on your desktop.

2. **Open Terminal:**
   - Right-click on the folder containing the program files and select "Open in Terminal."

3. **Execute the Program:**
   - Use the following commands to run the program:

#### Command for Uninformed Search:

```bash
python find_route.py Input_File Origin_City Destination_City
```

**Example:**

```bash
python find_route.py input1.txt Bremen Kassel
python find_route.py input1.txt London Berlin
```

#### Command for Informed Search:

```bash
python find_route.py Input_File Origin_City Destination_City Heuristic_File
```

**Example:**

```bash
python find_route.py input1.txt Bremen Kassel h_kassel.txt
```

### Code Structure

The code includes several essential functions such as `CNavigation`, `NodePath`, `SD`, `SourceRoute`, `SortNodes`, `checkingPoint`, `prioritizedFrontier`, `uninformedSearch`, and `informedSearch`. The main focus is on two types of search functions: uninformed and informed. In the informed search function, a heuristic file is used to guide the search, while the uninformed search function calculates the path using UCS. The code also tracks and prints the number of nodes popped, nodes expanded, and nodes created for both search methods.

---

