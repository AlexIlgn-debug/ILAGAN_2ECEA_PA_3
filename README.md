# ILAGAN_2ECEA_PA_3

## Problem-1 

    import pandas as pd
// Import Pandas

    cars = pd.read_csv('cars.csv')
    cars
// read file 'cars.csv

    cars.head()
    cars.tail()
// Prints the first five and last five rows of the dataframe

## Problem-2

    odd = cars.iloc[:, 0:10:2]
    odd
// Gets the first 5 odd column

    cars.iloc[[0], :]
// Displays the row of the car Mazda RX4

    cars.iloc[[23], [0,2]]
// Displays the cycles of the car Camaro Z28

    cars.loc[[1, 28, 18], ['Model' ,'cyl', 'gear']]
// Displays the Model name, cycles, and gears of cars Mazda RX4 Wag, Ford Pantera L, and Honda Civic
