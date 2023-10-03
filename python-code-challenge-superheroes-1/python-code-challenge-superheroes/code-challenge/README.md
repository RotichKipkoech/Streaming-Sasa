### AUTHOR: LIONEL KASEMBELI
### LICENSE: MIT LICENSE
# Superheroes API

The Superheroes API is a simple Flask-based web service that allows you to manage superheroes, their powers, and hero-power relationships.

### Prerequisites

Make sure you have Python and SQLite installed on your system.

### Endpoints
## Get Heroes
URL: /heroes
Method: GET
Description: Retrieve a list of all superheroes.

## Get Hero by ID
URL: /heroes/<int:id>
Method: GET
Description: Retrieve details of a superhero by their ID.

## Get Powers
URL: /powers
Method: GET
Description: Retrieve a list of all superpowers.

## Get Power by ID
URL: /powers/<int:id>
Method: GET
Description: Retrieve details of a superpower by its ID.

## Update Power by ID
URL: /powers/<int:id>
Method: PATCH
Description: Update a superpower's details by its ID.

## Create Hero Power
URL: /heropowers/create
Method: POST
Description: Create a new hero-power relationship.

## Contributing
Contributions are welcome! Feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License