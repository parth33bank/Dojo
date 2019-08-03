## How to get this repository?
- You need to have git installed on your system
- Once git is installed run this
```
git clone https://github.com/parth33bank/Dojo
```

## How do I run this?

### Flask
From the web folder
```
python -m flask run
```

### Docker
From the web folder
```
docker build -t flask-app:latest
docker run -d -p 5000:5000 flask-tutorial
```

### Docker-Compose
Navigate to the Dojo folder
```
docker-compose up --build
```
