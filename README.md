## API-TEMAN BAGAYA 

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
// GET full data in catalog 
curl -X GET link.api.com/fashion/catalog

// GET data in catalog by category atasan
curl -X GET link.api.com/fashion/catalog?category=atasan 

// GET data in catalog by category celana
curl -X GET link.api.com/fashion/catalog?category=celana 

// GET data in catalog by category alaskaki
curl -X GET link.api.com/fashion/catalog?category=alaskaki 

// POST image to predict for get item 
curl -X POST -F "file=@1.jpg" "link.api.com/fashion/predict"

``` 
- Example using kotlin
```
// you can read this website for more explanation
https://www.geeksforgeeks.org/retrofit-with-kotlin-coroutine-in-android/
https://square.github.io/retrofit/
``` 

