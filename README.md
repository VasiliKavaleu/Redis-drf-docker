# Sample of using Redis with DRF

## Run the project
- Clone the repository
- Run `docker-compose build && docker-compose up` in project root folder
- Go to localhost:8000

## Run test
- Run `docker-compose run --rm web python manage.py test api` to run the tests

Getting all data from Redis - GET: /values

Saving data to Redis - POST: /values

```bash
{
    "Key1": "Value1",
    "Key2": "Value2"
}
```

Getting data via keys - GET: /values?keys=Key1,Key2

Updating data in Redis - PATCH: /values

```bash
{
    "Key1": "Some Value"
}
```
