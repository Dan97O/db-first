<!-- 
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
 -->
<!-- ## data types:
- Strings: [varchar(number), char(number), text, longtext]
- numbers: [tinyint, small/medium int, int, bigint]
- decimal: [float(i,d), double(i,d), decimal(i,d)]
- dates: [datetime, date, year, time, timestamp]

## attributes:
- NULL/NOTNULL
- DEFAULT
- AUTO_INCREMENT
- UNIQUE
 -->
 # Database Intro used cars

## Entity name: Car
## Table name: Used Cars
## Table columns:
- id [BIGINT] PRIMARY_KEY, AUTO_INCREMENT, NOTNULL, UNIQUE, INDEX
- brand [VARCHAR(255)] NOTNULL, INDEX
- model [VARCHAR(255)] NOTNULL, INDEX
- vehicle_class [VARCHAR(255)] NULL
- car_image [VARCHAR(255)] NULL
- engine_displacement [DECIMAL(8,2)] NULL
- kilometer [DECIMAL(10,3)] NULL, INDEX
- city_consumption [DECIMAL(5,2)], NULL
- combined_consumption [DECIMAL(5,2)], NULL
- outdoors_consumption [DECIMAL(5,2)], NULL
- year [YEAR] NULL, INDEX
- price [DECIMAL(8,2)] NULL, INDEX
- color [VARCHAR(255)] NULL
- door_car [TINYINT] NULL
- number_seats [TINYINT] NULL
- emission_class [VARCHAR(25)] NULL
- original_country [VARCHAR(100)] NULL
- key_number [TINYINT] NULL
- vote [TINYINT] NULL, INDEX
- description [TEXT] NULL
- note [TEXT] NULL
