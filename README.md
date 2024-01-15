# Timestamp Microservice

This API provides a timestamp endpoint that accepts either a date in the format 'YYYY-MM-DD' or a UNIX timestamp and returns the corresponding UNIX timestamp and UTC date.

## Usage

### Endpoint

GET /api/:date


### Parameters

- `date`: A date in the format 'YYYY-MM-DD' or a UNIX timestamp.

### Example

#### Request / Response

```bash
curl https://your-app-url/api/2015-12-25

{
  "unix": 1451001600000,
  "utc": "Fri, 25 Dec 2015 00:00:00 GMT"
}


