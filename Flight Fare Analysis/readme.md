# Flight Fare Analysis
## Feature Overview

| **Column Name**       | **Explanation**                                              |
| --------------------- | --------------------------------------------------------------------- |
| **Airline**           | Name of the airline operating the flight.                             |
| **Date\_of\_Journey** | The scheduled date on which the flight is to be taken.                |
| **Source**            | The city from which the flight departs.                               |
| **Destination**       | The city where the flight is scheduled to arrive.                     |
| **Route**             | The flight path including stopovers (e.g., BLR → DEL → BOM).          |
| **Dep\_Time**         | The scheduled departure time of the flight.                           |
| **Arrival\_Time**     | The scheduled arrival time at the destination.                        |
| **Duration**          | Total travel time taken from departure to arrival.                    |
| **Total\_Stops**      | Number of stopovers the flight makes before reaching the destination. |
| **Additional\_Info**  | Extra information like meal service, baggage, or no info provided.    |
| **Price**             | The fare price of the flight in Indian Rupees.                        |

## Key Insights from the Analysis
- Airline Impact on Price: Certain airlines consistently offered cheaper fares, while premium airlines charged more for similar routes. This insight helps budget-conscious travelers make informed choices.

- Stops and Price Relation: Flights with non-stop or fewer stops were generally more expensive, but also shorter in duration — highlighting a trade-off between cost and convenience.

- Best Time to Fly: Morning flights were found to be cheaper on average, especially on weekdays. Weekends and evening slots had a noticeable surge in prices.

- Route Popularity: Routes like Delhi to Mumbai and Bangalore to Delhi had the highest traffic and wide price variance, offering room for flexible budget planning.

- Fare Types Distribution: The dataset showed a clear dominance of Economy class flights, with a smaller portion falling under Premium Economy and Business classes.

- Booking Strategy: Early booking (inferred from additional fields) correlated with lower fares, emphasizing the importance of planning ahead for cost savings.

- Dynamic Dashboards: The Excel dashboards provide stakeholders a real-time view of pricing trends, performance by airline, and interactive fare comparisons based on selected criteria.
