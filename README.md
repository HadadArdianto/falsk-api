## API-MACHINE LEARNING-PlanTani

## How to install this API 
1. Clone The repo API 
2. install all requirment needed
```
pip install -r requirments.txt
```
3. running the application API 
```
// in mode debug or developmnt 
python3 app.py

// in mode production 
gunicorn server:app
```

## How to consume this api 
simple just hit the routes API,
- Example using curl
```

// POST image to predict for get item 
curl -X POST -F "file=@1.jpg" "link.api.com/predict"


