

**README**
Visit [Mid Point Line Algorithm Simulator](https://not-solucky.github.io/Mid-Point-Line-Algoritm-Simulator/) to use the tool.
This code generates a midpoint line algorithm table. 

**Input:**

The code takes four integer inputs from the user:

* `x1`: x-coordinate of the first point
* `y1`: y-coordinate of the first point
* `x2`: x-coordinate of the second point
* `y2`: y-coordinate of the second point

**Output:**

The code outputs a table containing the following columns:

* `xi`: x-coordinate of the current point
* `yi`: y-coordinate of the current point
* `di`: decision parameter value at the current point
* `E/ NE`: east or north-east decision
* `Final Coordinate`: final coordinate of the current point after zone conversion

**Functionality:**

1. **Zone Conversion:** The code first converts the coordinates to a specific zone based on the relative positions of the two input points.
2. **Slope Calculation:** It then calculates the slope of the line between the two input points.
3. **Decision Parameter:** The code then iterates through the points between the two input points and calculates the decision parameter for each point. The decision parameter is used to determine which direction to move in the next iteration (east or north-east).
4. **Table Generation:** Finally, the code generates a table that displays the calculated values for each point along the line.

**How to use the code:**

1. Save the code as an HTML file (e.g., `midpoint.html`).
2. Open the HTML file in a web browser.
3. Enter the four integer values (x1, y1, x2, y2) in the corresponding input fields.
4. Click the "Simulate" button.
5. The table will be displayed below the input fields, showing the calculated values for each point along the line.
