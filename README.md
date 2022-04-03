# MechaCar_Statistical_Analysis
## Overview
AutosRUs is a car manufacturer and is prototyping a new vehicle, the MechaCar. AutosRUS has developed 50 prototypes of the Mechacar using multiple design specifications for vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance. These variables were compared to the miles per gallon (mpg) of each vehicle to determine whether these variables have any statistically significant impacts on mileage. 

Additionally, suspension coils used in the MechaCar protypes are manufactured in three production lots. An analysis of the weight capacities of suspension coils was performed to determine whether there is consistency between the production lots. 

## Results
### Linear Regression to Predict MPG
The mpg data for each prototype vehicle was compared to variables including vehicle length, vehicle weight, spoiler angle, drivetrain, and ground clearance using a linear regression analysis. The linear equation for the data is:

mpg = 6.27*vehicle length + 0.00125*vehicle weight + 0.0688*spoiler angle + 3.55*ground clearance - 3.41*drivetrain - 0.0104

The data p-values indicate that vehicle length and ground clearance have a significant impact on car mileage, while vehicle weight, spoiler angle and drivetrain do not statistically significant impact prototype mpg. The r-sqaured value is 0.715 which indicates the data is fairly well correlated. 

![Deliverable 1 Linear Regression](https://user-images.githubusercontent.com/94587007/161317767-c5839759-344f-4bcb-9073-e8b70b1f43a5.png)

### Summary Statistics on Suspension Coils
AutosRUs has three production lots for the manufacture of suspension coils - Lot1, Lot2, and Lot3. The mean, median, variance, and standard deviation were calculated for the suspension coils as a whole, as well as for suspension coils categorized by each production lot.

Summary statistics for all suspension coils

![total_summary](https://user-images.githubusercontent.com/94587007/161320749-0cadf43e-52d4-4244-abb7-120d1554744c.png)

Summary statistics for suspension coils by production lot

![lot_summary](https://user-images.githubusercontent.com/94587007/161320779-f4731403-bda7-47e3-b8a9-393be42bd15e.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Suspension coils produced in Lots 1 and 2 meet this criteria. However, suspension coils produced by Lot 3 have a variance of approximate 170 pounds per square inch, which exceeds AutosRUs' design specifications for the MechaCar. 

### T-Tests on Suspension Coils
T-tests were performed on the suspension coil data to determine if all manufacturing lots and each lot individually are statustically different from the population mean of 1,500 pounds per square inch.

Overall, suspension coils produced from all lots as well as those produced from Lots 1 and 2 specifically are not statistically different from the expected average of 1,500 psu. The t-test indicates these samples produce p-values exceeding 0.05. It appears that the suspension coils from Lot 3 are statistically different than the expected 1,500 psu mean with a p-value of 0.04. 

![t-test](https://user-images.githubusercontent.com/94587007/161441298-c7a38193-c5ee-4a38-ad94-62ed214938cf.png)

### Study Design: MechaCar vs Competition
AutosRUs is interested in conducting a follow-up investigation to compare the MechaCar's performance against competitors. One potential avenue of investigation would be to determine whether vehicle price has an impact on maintenance costs. The null hypothesis would be that there is vehicle price have no significant impact on future maintenance costs. The alternative hypothesis would be that vehicle price does impact maintenance costs. I would use a simple linear regression analysis to determine whether there is a statistically significant relationship between these two costs and determine how well the two variable are correlated.
