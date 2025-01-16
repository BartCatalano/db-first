id                        INT                  UNIQUE
model                     VARCHAR(255)         NOTNULL
production_year           YEAR                 NOTNULL
disponibility             UNSIGNED INT         NOTNULL
description               VARCHAR(255)
kilometres                INT                  NOTNULL
state_interior            VARCHAR(255)
registration              DATE                 NOTNULL
fuel_type                 VARCHAR(30)          NOTNULL
color                     VARCHAR(30)          NOTNULL
number_of_seats           UNSIGNED TINYINT     NOTNULL
car_wear                  VARCHAR(100)         NOTNULL
ncar_door                 UNSIGNED TINYINT     NOTNULL
