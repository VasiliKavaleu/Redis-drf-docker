## Run the project
- Clone the repository
- Run `docker-compose build && docker-compose up` in project root folder
- Go to localhost:8000

## Run test
- Run `docker-compose run --rm web python manage.py test api` to run the tests

POST /values

```bash
{
    "Key1": "Value1",
    "Key2": "Value2"
}
```

GET /values?keys=Key1,Key2

PATH /values

```bash
{
    "Key1": "Some Value"
}
```
