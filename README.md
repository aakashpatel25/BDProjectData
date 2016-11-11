# BDProjectData
Data for the project.

Reading a parquet file with the ```sqlContext.read.parquet``` command gives a Dataframe with the following schema:
```
DataFrame[carId: bigint, driverId: bigint, vendorType: string, rateCode: int, pickupTime: timestamp, dropoffTime: timestamp, passengerCount: int, tripTime: int, tripDistance: float, pickupLong: double, pickupLat: double, dropLong: double, dropLat: double, paymentType: string, fareAmount: float, surcharge: float, mtaTax: float, tipAmount: float, tollAmount: float, totalAmount: float]
```

