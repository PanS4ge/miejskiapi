There are just 2 classes:

Sprawdzacz.py - Checks the definition
MiejskiDefinicja.py - Main class for definitions

Main classes in here:
MiejskiDefinicja.toJson() - Converts the definition to JSON
MiejskiDefinicja.fromJson(JSON : dictionary) - Converts JSON object to definition
Sprawdzacz.sprawdz_raw(definiction : str) - Returns the raw website
Sprawdzacz.sprawdz_link(link : str) - Returns the MiejskiDefinicja from the link to the website
Sprawdzacz.sprawdz(definiction : str) - Returns the MiejskiDefinicja from the definition

Sprwadzacz will be from importing the miejskiapi package.