# Timestamp Microservice

This API provides a timestamp endpoint that accepts either a date in the format 'YYYY-MM-DD' or a UNIX timestamp and returns the corresponding UNIX timestamp and UTC date.

## Usage

### Endpoint

GET /api/:date


### Parameters

- `date`: A date in the format 'YYYY-MM-DD' or a UNIX timestamp.

### Example

#### Request

```bash
curl https://your-app-url/api/2023-12-31

{
  "unix": 1640995200000,
  "utc": "Thu, 31 Dec 2023 00:00:00 GMT"
}


