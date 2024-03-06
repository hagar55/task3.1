select CITY.name  from CITY , COUNTRY
where CITY.CountryCode =  COUNTRY.Code and CONTINENT='Africa';
