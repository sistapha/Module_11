
# Used Car Price Modeling using Linear Regression

### What factors drive the price of a used car?

**Context**

The objective of this analysis is to determine the key factors that influence the price of a used car. It is being done for a client who owns a used car dealership.

**Overview**

The goal of the study is to identify a set of factors that drive the price of a car upwards or downwards and a model that can predict the price of a vehicle based on these factors.

**Methodology**

## Feature Definitions

01. Price: Price in USD, not adjusted for inflation.
02. Year: The year in which the car was manufactured
03. Manufacturer: 43 unique auto brands that manufacture the automobiles that are a part of this dataset.
04. Model: The model of the car.
05. Condition: The condition of the car; excellent, good, fair, like new, salvage, new.
06. Cylinders: The number of cylinders in the car engine ranging from 3 to 12. Also has the ‘other’ category too.
07. Fuel: There were five types of fuel, ‘diesel’, ‘gas’, ‘electric’, ‘hybrid’ and ‘other’.
08. Odometer: The distance travelled by the car after it was first bought.
09. Title Status: The cars have 6 types of statues; ‘clean’, ‘lien’, ‘rebuilt’, ‘salvage’ , ‘parts only’ and ‘missing’.
10. Transmission: There are 3 types of transmission; ‘automatic’, manual and other.
11. Drive: There are 3 types of drive transmissions; ‘4WD, ‘FWD’ and ‘RWD’. (Four-wheel drive, forward-wheel drive and rear-wheel drive.)
12. Size: Size of the vehicle
13. Type: This feature identifies if a vehicle is a SUV or a mini-van. There 13 unique values in this feature.
14. Paint_Color: This feature identifies the color of the car. There 12 unique values in this feature.
15. State: The state is political territory and is represented in short form in the data set. Like “fl” is used for the state of Florida.


## FAQ

#### Summary of Findings

**Age:** The price of vehicles decrease with increasing age. Once the vehicle is ten years and older, its price falls dow to $10,000 or less.

**Mileage:** The price of vehicles decrease with higher odometer readings. Once the vehicle has > 110,000 miles, its price falls dow to $10,000 or less.

**Vehicle Type:** The regression model indicates that specialized vehicles (e.g., off-road, truck) and powerful vehicles (cylinders > 6), have a higher price value while economy vehicles with lower power have a lower resale value.

**Important Features:** The car's features: Year, # of cylinders and mileage were the most important.

**Summary:** Consumers want utility (off-road, trucks, four-wheel-drive) and powerful (10,8,6 cylinder) vehicles. As a result, vehicles with these features are valued more.


## Next Steps

We recommend further analysis on the following features:

- Region
- Model
- Color
These features were not used in the regression. If trends exist, then future work could include adding these.

Revisit the dataset in a few years to see if there is an increase in value for: a) fuel efficient vehicles due to gas inflation AND b) electric vehicles.



## Documentation

[Used Car Pricing Model]()

