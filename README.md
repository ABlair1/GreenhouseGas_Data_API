# GreenhouseGas_Data_API
Microservice API that supports the Food Footprint Calculator. Serves greenhouse gas data for various food items in JSON format. Implemented with Python/Flask.

## How to Use:
To get greenhouse gas data for various food items, send a basic GET request to the API endpoint at the following URL: 

`https://cs361-ghg-data.herokuapp.com/`

A response will be returned in JSON format, which will include various food items and the amount of carbon-equivalent greenhouse gas emissions produced from various sources for each food. All emissions amounts are given in kilograms. Data has been sourced from peer-reviewed research (Nemecek & Poore, 2018).

## Example (single food entry from JSON):

`"Wheat & Rye (Bread)": {`
`    "Product": "Wheat & Rye (Bread)", `
`    "Category": "Grains", `
`    "LUC": "0.1", `
`    "Feed": "0", `
`    "Farm": "0.8", `
`    "Processing": "0.2", `
`    "Transport": "0.1", `
`    "Packging": "0.1", `
`    "Retail": "0.1", `
`    "Total": "1.44"`
`}, `

## Reference:

Nemecek, T., & Poore, J. (2018). Reducing food's environmental impacts through producers and consumers. Science, 360(6392), 987-992. https://www.science.org/doi/10.1126/science.aaq0216.
