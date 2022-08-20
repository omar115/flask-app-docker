# flask-app-docker
In this repo I tried to dockerize a flask application.

# Installation Instructions
## How to Install it Locally
### Step-1:
- clone this repo
```
https://github.com/omar115/flask-app-docker.git
```

### Step-2:
- Create a virtual environment (If you do not virtual environment installed, do install it first)
```
python3 -m venv env

```

### Step-3:
- Activate virtual environment and inside the environment install the dependencies
from the `requirements.txt` file.
```
source env/bin/activate
```

```
pip install -r requirements.txt
```

### Step-4:
- Run in your local machine

```
python app.py
```

## How to run this application using Docker

### Step-1:
Install Docker for your machine

### Step-2: 
Run the command to build the docker image

```
docker build -t flask-docker .
```

### Step-3:
Run the command below to run your application

```
docker run -d -p 5000:5000 flask-docker
```

After going through these 3 steps successfully, you will be able to run your flask application using docker.

