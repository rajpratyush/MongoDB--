# "Fastapi + MongoDB" Boilerplate

> A boilerplate of the minimal and extensible Python modern web framework fastapi and mongodb. It supports restapi and ssr at the same time and is configured based on odmantic, which is a lightweight odm of mongodb.

## Getting start

```shell
git clone https://github.com/amamov/fastapi-mongodb-boilerplate.git <your-project-name>
```

```shell
cd <your-project-name>

# create "secrets.json" for env
touch secrets.json
```

```json
// ./secrets.json
{
  "MONGO_DB_NAME": "your-db-name",
  "MONGO_URL": "mongodb+srv://..."
}
```

```shell
# remove .git
rm -rf .git
```

```shell
pip install -r requirements.txt
```

```shell
python3 start.py
```

## Dependency

- [FastAPI](https://fastapi.tiangolo.com/ko)

- [odmantic](https://art049.github.io/odmantic)
