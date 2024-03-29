# Number

A number variable can present among others:
- [[#Count]]
- [[#Index]]
- [[#Measurement]]
- [[#Price]]
- [[#Amount]]

## Count

Many developers use the word "number" as part of the variable name to hold the count of something. For example a variable holds the count of students may have a name like `studentsNumber` or `numberOfStudents`. 

Actually we recommend to avoid using the `number` word in such ways, because it misleads in some occasions. Let us take a couple of examples. `serialNumber` is a string variable used as an identification of a product. `packageNumber` is more misleading because it can mean the count of packages or the serial number of the package.

>[!Important]
>Use `count` instead of `number` for something count.

We recommend to use `count` instead of `number`. For example `packagesCount` is a variable holding the count of packages, and `studentsCount` is for the count of students.

## Index


## Measurement

Before you start using measuring variables you have to state somewhere the system and units you are going to use. You can do that in the comments or as we prefer in a separate readme file in the project.

In the following paragraphs we assume you use the metric system. 

>[!Important]
>Use `distance` to represent the distance between two points.

To measure a distance between two points we can use `distance`. If the value is `10` we mean 10 meters, and we need to clarify that by a comment or the readme file mentioned above.

For example, a variable holding the distance value between Stockholm and Lund can be `distanceBetweenStockholmAndLund`, this is quit long name, so if it so clear from the scope that we talk about those two towns then we can use `distanceBetween` or even `distance`.

>[!Important]
>Use `altitude` to represent the elevation of a point or a mountain over the sea level.

The word `altitude` is well know specific word used widely to represent the elevation of a point over the sea level, therefore, we use it instead of the word `height`.

Notice that `altitude` value can have a minus value in case of the dead sea.

For example, `everestAltitude` variable hold the value of the mountain Everest top above the sea level.

>[!Important]
>Use `speed` to represent the speed of a car or train or similar objects.

Use `carSpeed` to tell about how many meters per second the car moves.

In some cases we need to state the angular speed in degrees per second unit, for example; to state that the angular speed of the clock is 6 degrees per second we write `clockAngularSpeed = 6`.

>[!Important]
>Use `temp` as a well-known appreviation of temperature.

For example; to state that the temperature of room is 18 celsius we write `roomTemp = 18`.

>[!Caution]
>When we use `temp` to stand for temperature, we should use different word to stand for temporary. We recommend to use `tempo` for that.

## Price

The word `price` is neutral. This means that for a single product we may have two or more prices. Selling price is not the same as purchase price.

If the kind of the price is clear from the scope context, you can use the word `price`, otherwise, you have to prefix it with explanatory adjective to be like `sellingPrice`, `purchasePrice`, `wholesalePrice`, `retailPrice` and so on.

## Amount

