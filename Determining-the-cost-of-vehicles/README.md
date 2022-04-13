# Determining-the-cost-of-vehicles
A used car dealership is developing an app to attract new customers. In it, you can quickly find out the market value of your car. Historical data is available: technical characteristics, configurations and prices of vehicles. We need to build a model to determine the cost.

### Consumer value :
- quality of prediction;
- prediction speed;
- training time.

### Signs:
- DateCrawled - date of downloading the profile from the database
- VehicleType - type of car body
- RegistrationYear — year of car registration
- Gearbox - type of gearbox
- Power - power (hp)
- Model - car model
- Kilometer - mileage (km)
- RegistrationMonth — month of car registration
- FuelType — type of fuel
- Brand - car brand
- NotRepaired - was the car under repair or not
- DateCreated — date of creation of the questionnaire
- NumberOfPictures - the number of photos of the car
- PostalCode — postal code of the owner of the profile (user)
- LastSeen - date of last user activity

### Target feature:
- Price - price (EUR)

## Libraries used:
Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, LightGBM, CatBoost

