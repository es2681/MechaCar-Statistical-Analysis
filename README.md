# MechaCar_Statistical_Analysis
## Overview
AutosRUs is a car manufacturer and is prototyping a new vehicle, the MechaCar. AutosRUS has developed 50 prototypes of the Mechacar using multiple design specifications, including vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance. These variables were compared to the miles per gallon (mpg) of each vehicle to identify those with the best mileage. 

Additionally, suspension coils used in the MechaCar protypes are manufactured in three production lots. AutosRUs has a dataset in which the weight capacities of suspension coils were tested to determine consistency between the production lots. 

## Results
### Linear Regression to Predict MPG
The mpg data for each prototype vehicle was compared to variables including vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance using a linear regression analysis. The linear equation for the data is:
mpg = 6.27*vehicle length + 0.00125*vehicle weight + 0.0688*spoiler angle + 3.55*ground clearance - 3.41*drivetrain - 0.0104

The data p-values indicate that vehicle length and ground clearance have a significant impact on car mileage, while vehicle weight, spoiler angle and drivetrain do not statistically significant impaacts on mileage. The r-sqaured value is 0.715 which indicates the data is fairly well correlated. 

![Deliverable 1 Linear Regression](https://user-images.githubusercontent.com/94587007/161317767-c5839759-344f-4bcb-9073-e8b70b1f43a5.png)

### Summary Statistics on Suspension Coils
AutosRUs has three production lots for the manufacture of suspension coils - Lot1, Lot2, and Lot3. The mean, median, variance, and standard deviation were calculated for all suspension coils as well as for suspension coils separated by each production lot.

Summary statistics for all suspension coils

![total_summary](https://user-images.githubusercontent.com/94587007/161320749-0cadf43e-52d4-4244-abb7-120d1554744c.png)

Summary statistics for suspension coils by production lot

![lot_summary](https://user-images.githubusercontent.com/94587007/161320779-f4731403-bda7-47e3-b8a9-393be42bd15e.png)


