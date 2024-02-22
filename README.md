# Energy Consumption Radar Chart By Country

This is our project on the Energy Consumption Dataset for the DSC 106 class.
* The link to our project is here: [Renewable Energy Interactive Radar Chart](https://etvoucsd.github.io/RenewableEnergyData/dsc106project3.html)
* The link to our write - up on the project is here: [Project-Write Up](https://docs.google.com/document/d/18UMJkuv8YmAhcdcIO0NX3_Q94d4zSPBmvuL4zOwM5lg/edit)

## Design Decisions:
### Visual Encodings:
* **Radar Charts**: Radar charts were chosen to visualize the energy consumption statistics for different countries. They effectively represent multivariate data by using axes radiating from a central point.
*  **Color Coding**: Each country is assigned a unique color for better differentiation. The color scale is ordinal, making it easy to associate the same color with the same country across different charts.
*  **Dropdown Interaction**: The use of a dropdown menu enables users to toggle between 'consumption per capita' and 'primary energy consumption' views. This interaction provides a dynamic way to explore both aspects of  energy data.
*  **Mouse Interaction**: By hovering the mouse over each point, users are able to see the consumption value and percentile value that correspond to each point.

## Development Process Overview:
* **Data Processing and Filterting**: Significant time was devoted to processing the CSV data and filtering it for relevant information. This included converting data types and segregating 'per capita' and 'consumption' data. In addition, the values of each column was converted as a percentile of the country with respect to the rest of the world.
* **SVG Element Creation**: Considerable effort was invested in creating SVG elements dynamically based on the selected chart type. Debugging was crucial to ensure SVG elements were being generated as expected.
*  **DropDown Interaction Implementation**: Developing the dropdown menu and ensuring it interacts correctly with the charts involved careful consideration of D3.js event handling. The goal was to provide the user with the option of viewing data per capita (to look at a more comparable scale between large and small countries) and the original data.
* **Documentation and ReadMe**: Effort was dedicated to making the charts responsive and visually appealing. This included adjusting dimensions, grid lines, and tooltips for an optimal user experience.
