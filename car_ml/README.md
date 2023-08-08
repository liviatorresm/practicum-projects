## Data

| Variable          | Description                                           |
|-------------------|-------------------------------------------------------|
| DateCrawled       | Date when the profile was downloaded from the database |
| VehicleType       | Vehicle body type                                    |
| RegistrationYear  | Year of vehicle registration                          |
| Gearbox           | Type of transmission                                 |
| Power             | Power (hp)                                            |
| Model             | Vehicle model                                        |
| Mileage           | Mileage (measured in km due to regional dataset specifics) |
| RegistrationMonth | Month of vehicle registration                        |
| FuelType          | Fuel type                                            |
| Brand             | Vehicle brand                                        |
| NotRepaired       | Whether the vehicle has been repaired or not         |
| DateCreated       | Profile creation date                                |
| NumberOfPictures  | Number of vehicle photos                             |
| PostalCode        | Postal code of profile owner (user)                  |
| LastSeen          | Date of last user activity                           |
| Price             | Price (Euro)                                         |

## Goal

Develop a model to predict the market value of cars for a used car sales application.

## Libraries used:
* pandas
* numpy
* seaborn 
* matplotlib
* re
* sklearn
* category_encoders
* xgboost
* lightgbm
* catboost