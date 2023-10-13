# Car Dealer Database

## Table Name

- used cars

## Table columns

- id |PK, BIGINT, AUTO_INCREMENT, UNIQUE, NOT_NULL
- brand |VARCHAR, NOT_NULL
- model |VARCHAR, NOT_NULL
- fuel_type |TINYINT, NOT NULL   //0 petrol, 1 diesel, 2 methane, 3 hybrid, 4 electric
- displacement |INT, NULL
- color |VARCHAR(30), NOT_NULL
- year_of_registration |YEAR, NOT_NULL
- number_owners |INT, NOT_NULL
- price |DOUBLE, NOT_NULL
- warranty |FLOAT, NULL
- traction |TINYINT, NOT_NULL   //0 posterior_traction, 1 anterior_traction, 2 four_matic
- optional |TEXT, NULL
- kilometres |INT, NOT_NULL
- condition |TINYINT, NOT_NULL   //0 like_new, 1 good, 2 medium, 3 bad
- note |TEXT, NULL