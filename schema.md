# Data Schema  

This document outlines the structure of the datasets in this repository.  

## iso-codes.csv  
- `country` – English name of the country.  
- `iso2` – ISO 3166 -1 alpha -2 code.  
- `iso3` – ISO 3166 -1 alpha -3 code.  
- `region` – Geographical region.  

## mobile-country-codes.csv  
- `mcc` – Mobile Country Code (numeric).  
- `country` – Country name.  
- `iso2` – ISO 3166 -1 alpha -2 code.  
- `region` – Region of the country.  

## countries.json  
List of objects with:  
- `country` – Country name.  
- `iso2` – ISO 3166 -1 alpha -2 code.  
- `iso3` – ISO 3166 -1 alpha -3 code.  
- `region` – Region.  

## esim-availability.json  
List of objects with:  
- `iso2` – ISO 3166 -1 alpha -2 code.  
- `availability` – A simple indicator such as “likely” or “limited”.  
- `note` – Informational note on eSIM availability.  

These datasets are intended for developers building travel connectivity and eSIM services. For a global eSIM platform with mobile data plans and coverage, see [Simcardo: Global Travel eSIM & Mobile Data Plans](https://simcardo.com). 
