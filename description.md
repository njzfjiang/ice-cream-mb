# Ice Cream MB

Ice Cream MB is an API which allows users to find the best ice cream shops in Manitoba. Ice cream shops can be retrieved based on location, and their popularity and available flavours can be found.

## Get shops near a certain location

Retrieve all ice cream shops within a given radius of a given coordinate. The result is a JSON array of shops. Each element has the name of the shop, its latitude and its longitude.

Endpoint: `GET /icecream/shops`

Parameters:
* `lat`: Latitude
	* required
* `lon`: Longitude
	* required
* `rad`: Radius to get shops within
	* optional, defaults to 1km

Resources:
```json
[
	{
		"name":"Shop 1",
		"lat":0.0,
		"lon":0.0
	},
	{
		"name":"Shop 2",
		"lat":0.0,
		"lon":0.0
	}
]
```

## Get ice cream flavours at a shop


## Getting the popularity of a shop

The popularity of Ice cream is based on the reviews provided by different customers. It depends upon the rating given by different people. It helps to account for different people giving their opinions based on their own personal preferences. With that information, we can take into account the best ice cream places in Manitoba.

## Get the opening hours of a shop

