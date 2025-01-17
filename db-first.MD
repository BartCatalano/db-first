id                        INT  UNSIGNED        UNIQUE NOTNULL
model                     VARCHAR(255)         NOTNULL
disponibility             UNSIGNED INT         NOTNULL
description               VARCHAR(255)
kilometres                INT                  NOTNULL
registration              DATE                 NOTNULL
fuel_type                 VARCHAR(30)          NOTNULL
color                     VARCHAR(30)          NOTNULL
number_of_seats           UNSIGNED TINYINT     NOTNULL
car_wear                  VARCHAR(100)         NOTNULL
car_door                  UNSIGNED TINYINT     NOTNULL
production_year           YEAR                 NOTNULL
state_interior            VARCHAR(255)