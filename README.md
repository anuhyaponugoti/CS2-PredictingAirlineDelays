# Predicting Chicago Flight Delays
This case study aims to predict flight delays for Delta, Southwest, and Spirit airlines departing from the Chicago O'Hare International Airport.

## Hook Document
This document describes the context and motivation behind the case study, the data, prompt, and deliverable.

## Rubric
The rubric describes the deliverable instructions and criteria.

## Materials
Two articles and the Data folder are included in the Materials folder. The data is described below. The two articles included are "Delays up at O'Hare Article" and "Airline Employee Shortage Article", which detail the recent delays at the Chicago O'Hare International Airport and how airline employee shortages since the COVID-19 pandemic have contributed to more flight cancellations and delays, respectively.

## Data
Flights departing from the Chicago O'Hare International Airport in 2022 via Delta, Southwest, and Spirit, are located in Materials/Data folder in "Delta.csv", "Southwest.csv", and "Spirit.csv", respectively. Below is the data dictionary that applies to all three of these datasets.
| Column                       | Type   | Description                                                      |
|------------------------------|--------|------------------------------------------------------------------|
| Carrier Code                 | string | A short 2-letter code identifying the airline                    |
| Date                         | string | A string representing the date of the flight in month/day/year format |
| Destination Airport          | string | A 3-letter code that represents the flight’s destination airport  |
| Scheduled departure time     | string | The time that the flight was scheduled to depart in 24-hour format |
| Actual departure time         | string | The actual time the flight departed in 24-hour format              |
| Departure delay               | float  | The difference between scheduled departure time and actual departure time. The total number of minutes the flight was delayed |
| Delay Carrier                 | float  | The number of minutes that the flight was delayed due to the carrier |
| Delay Weather                 | float  | The number of minutes that the flight was delayed due to weather   |
| Delay National Aviation System | float | The number of minutes that the flight was delayed due to the National Aviation System (airport operations, air traffic control, etc) |
| Delay Security                | float  | The number of minutes that the flight was delayed due to security  |
| Delay Late Aircraft Arrival   | float  | The number of minutes that the flight was delayed due to the aircraft arriving late |

## References
[1]	Bureau of Transportation Statistics, “Detailed Statistics Departures,” Bts.gov, 2017. https://www.transtats.bts.gov/ONTIME/Departures.aspx
[2]	“Flight delays, cancellations could continue for a decade amid airline workforce shortage - CBS News,” www.cbsnews.com, Jul. 25, 2023. https://www.cbsnews.com/news/the-future-of-flying-more-delays-more-cancellations-more-chaos/ 
[3] Knowles, Jason. “Non-Weather Flight Delays up in Recent Years at Both O’hare, Midway.” ABC7 Chicago, 22 Nov. 2023, abc7chicago.com/flight-delays-airport-ohare-midway/14089059/. 
