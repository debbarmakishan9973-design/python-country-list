# python-country-list
Python script to generate list of countries
A simple Python functions that shows the country's names
import pycountry
country_names = []
for country in pycountry.countries:
    country_names.append(country.name)
print(country_names)
