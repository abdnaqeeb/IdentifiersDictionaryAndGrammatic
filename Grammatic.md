# Grammatic

## Variables

Variable name differ based on its type and scope.

### General Rules



### Types

A variable can be defined in different types:
1. Primitive type
2. Class type

#### Number type

A number variable can present:
- Count
- Index
- Measurement
- Price
- Amount

##### Count

Many developers use the word "number" as part of the variable name to hold the count of something. For example a variable hold the count of students may have a name like `studentsNumber` or `numberOfStudents`. 

Actually we recommend to avoid using the `number` word in such ways, because it misleads in some occasions. Let us take a couple of examples. `serialNumber` is a string variable used as an Identification of a product. `packageNumber` is more misleading because it can mean the count of packages or the serial number of the package.

We recommend to use `count` instead of `number`. For example `packagesCount` is a variable holding the count of packages, and `studentsCount` is for the count of students.

>[!Important]
>Use `count` instead of `number` for something count.
>

##### Index


##### Measurement

Before you start using measuring variables you have to state somewhere the system and units you are going to use. You can do that in the comments or as we prefer in a separate readme file in the project.

In the following paragraphs we assume you use the metric system. 

>[!Important]
>Use `distance` to represent the distance between two points.

To measure a distance between two points we can use `distance`. If the value is `10` we mean 10 meters, and we need to clarify that by a comment or the readme file mentioned above.

For example, a variable holding the distance value between Stockholm and Lund can be `distanceBetweenStockholmAndLund`, this is quit long name, so if it so clear from the scope that we talk about those two towns then we can use `distanceBetween` or even `distance`.

>[!Important]
>Use `altitude` to represent the height of a point or a mountain over the sea level.

The word `altitude` is well know specific word used widely to represent the height of a point over the sea level, therefore, we use it instead of the word `height`.

Notice that `altitude` value can have a minus value in case of the dead sea.

For example, `everestAltitude` variable hold the value of the mountain Everest top above the sea level.

>[!Important]
>Use `speed` to represent the speed of a car or train or similar objects.

Use `carSpeed` to tell about how many meters per second the car moves.

In some cases we need to state the angular speed in degrees per second unit, for example; to state that the angular speed of the clock is 6 degrees per second we write `clockAngularSpeed = 6`.

>[Important]
>Use `temp` as a well-known appreviation of temperature.

For example; to state that the temperature of room is 18 celsius we write `roomTemp = 18`.


##### Price


##### Amount


#### String type


#### Boolean type


### Scope

A variable can be defined in different scopes:
1. Global
2. Class object field
3. Class object property
4. Function local
5. Function argument
6. Function parameter
7. Loop index
8. Loop iterator
9. Loop local

