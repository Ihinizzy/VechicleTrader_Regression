# VehicleTrader_Regression

Due to the increased price of new cars and the incapability of customers to buy new cars due to the lack of funds, used cars sales are on a global increase.
There is a need for a used car price prediction system to effectively determine the worthiness of the car using a variety of models to assist in decision making.

**Models used** 
*Linear Regression 
*Random Forest Regression
*Ridge Regression
*Lasso Regression

**Dataset Features**
* public_reference- Unable to get actionable information on this variable
* reg_code- Unable to get actionable information on this variable
* mileage- The standard mileage offered by the car company (Lower is usually better)
* standard_colour- Body paint color of vehicle at time of sale (5-total)
  - **Grey**
  - **Blue**
  - **Black**
  - **Silver**
  - **White**
* standard_make- Manufacturer name of vehicle (11-total).
[MINI', 'Volkswagen', 'Mercedes-Benz', 'Vauxhall', 'Nissan',
     'Toyota', 'Audi', 'Renault', 'BMW', 'Fiat', 'Kia']
* standard_model- Model name as stated by manufacturer for target vehicle (19-total).
[Hatch', 'Golf', 'C Class', 'Corsa', 'Qashqai', 'Yaris', 'Polo',
     'Astra', 'A1', 'E Class', 'Clio', 'A Class', '5 Series',
     '1 Series', '500', 'A3', 'Sportage', '3 Series', 'Juke']
* vehicle_condition- Whether vehicle has had a prior owner or not, all vehicles in dataset are used.
  - **USED**
* year_of_registration- Year of first registration of vehicle.
* body_type- body shape of vehicle in question.
  - **Hatchback**
  - **Estate**
  - **Saloon**
  - **SUV**
  - **Coupe**
* crossover_car_and_van- If car is a crossover or a van type vehicle:
  - **False**
* fuel_type- The type of fuel used by the car (**Fuel**, **Diesel**).
* make_model- A combination of the make and model columns
* age- An extrapolation from the registration date, (Current year - Reg year).
* price- The price of the used car.
