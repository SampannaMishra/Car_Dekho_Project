# Get to know the dataset and the features
Thoughts and assumptions on each feature:
1.selling_price :our target variable since we are predicting the price of vehicles
2.name: Name and model of vehicle, I think the brand and name of the car will be somewhat valuable.
3.year: The year when the vehicle is bought
4.km_driven: This can indirectly tell us the condition of the vehicle, vehicle which travelled a longer distance tends to mean the vehicle is older and hence the selling price will be lower.
5.fuel: Diesel vs petrol should make a difference since the price of the fuel and the engine type are not the same.
6.seller_type: assume selling price of vehicle for 'Individual seller' should be lower since 'Dealer' often charge commission or service fee or any form of fees.
7.transmission: 'Manual' car, 'Automatic' car
8.owner: This specify the number of owners the vehicle had before
9.mileage:higher mileage vehicle should be higher in selling_price
engine: The Cubic Capacity(CC) of engine
10.max_power: The Brake Horse Power(BHP) of the vehicle
11.torque: The torque of the vehicle, for modelling purpose
12.seats: Seats can possibly represent the size of the vehicle
