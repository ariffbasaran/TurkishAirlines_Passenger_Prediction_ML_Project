# TurkishAirlines_Passenger_Prediction_ML_Project
Turkish airlines reservation passenger estimation machine learning project using python


# Business Problem

Turkish Airlines is requesting the establishment of a machine learning regression model to predict the number of seasonal booked passengers on flights.

# Dataset
| Column Name      | Description                                                                                           |
|------------------|-------------------------------------------------------------------------------------------------------|
| CARRIER          | The binary code of the carrier company. The carrier company remains the same for both legs.      |
| AIRCRAFT_TYPE    | Information about the aircraft type.                                                                 |
| OND_SELL_CLASS   | The selling class of the longest leg.                                                               |
| LEG1_SELL_CLASS  | The selling class of the 1st leg.                                                                   |
| OND_CABIN_CLASS  | The cabin class of the longest leg.                                                                 |
| LEG1_CABIN_CLASS | The cabin class of the 1st leg.                                                                     |
| HUB              | Includes the IATA codes of the airport where a transfer is made from the 1st leg to the 2nd leg. |
| DETUR_FACTOR     | A ratio that indicates how much a passenger's route is extended when they fly indirectly.         |
| CONNECTION_TIME  | Represents the expected waiting time in minutes for transferring from the 1st leg to the 2nd leg. |
| PSGR_COUNT       | Total number of booked passengers.                                                                  |
| LEG1_DEP_FULL    | Departure date and time of the 1st leg.                                                            |
| LEG1_ARR_FULL    | Arrival date and time of the 1st leg.                                                              |
| LEG2_DEP_FULL    | Departure date and time of the 2nd leg.                                                            |
| LEG2_ARR_FULL    | Arrival date and time of the 2nd leg.                                                              |
| LEG1_DURATION    | Duration of the 1st leg's flight.                                                                   |
| LEG2_DURATION    | Duration of the 2nd leg's flight.                                                                   |
| FLIGHT_DURATION  | Time elapsed from the departure of the 1st leg to the landing of the 2nd leg.                      |
