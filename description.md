# Ice Cream MB

## Get shops near a certain location
Endpoint: `POST /api/shops`
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


## Get the opening hours of a shop

