# Foreign Exchange Currency

## Development
```
npm install

npm start
```

## Deployment using Docker

Make sure docker is installed

```
touch Dockerfile
Example 'Dockerfile' in this project

touch .dockerignore
Example '.dockerignore' in this project

docker build -f Dockerfile -t [app_name] .
Example: [app_name] => foreign-exchange-currency

docker run -it -p 80:80 --rm [app_name]
Example: [app_name] => foreign-exchange-currency
```