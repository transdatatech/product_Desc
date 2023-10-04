# Description generation

## Example of curl request

```
curl --location 'http://localhost:5000/api/description' \
--header 'Content-Type: application/json' \
--data '{
	"data": {
		"type": "product_search",
		"attributes": {
			"product_type": "Skirt",
			"meta_info": "Red" //optional, leave blank otherwise.
		}
	}
}'
```
