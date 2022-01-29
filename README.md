# Food Names API 🍗🍔🍕🍜

+ An API that will return random Food Names 🍡🥧🎂🌮
+ Dedicated To All Food Lovers ❤️

## Usage:

+ ### [`https://randomfoodnamesapi.herokuapp.com/`](https://randomfoodnamesapi.herokuapp.com/) to get the documentation.
+ ### [`https://randomfoodnamesapi.herokuapp.com/api/Food-Names/all`](https://randomfoodnamesapi.herokuapp.com/api/Food-Names/all) to get all the Food Names at once.
+ Change `all` to parameter `?number=` to specify the number of Food Names you want to receive.
+ Change `all` to parameter `?index=` to specify the index of the Food Name you are targeting.

This project is hosted by [Heroku](https://www.heroku.com/) with zenomodiffofficial@gmail.com

## Rebuild the project:
+ Clone the repo.
+ Run `python -m venv .env` to create a virtual environment.
+ Run `source .env/bin/activate` to activate the virtual environment.
+ Run `pip install requirements.txt`.
+ Run `python app.py`.
+ App starts at `http://localhost:5000` by default, but can be configured with a `.env` file. 

## Example:

+ ### [`https://randomfoodnamesapi.herokuapp.com/api/Food-Names?number=1`](https://randomfoodnamesapi.herokuapp.com/api/Food-Names?number=1) returns: ↓
```JSON
[
  {
    "Food_Name": "Mutton Soup"
  }
]
```

+ ### [`https://randomfoodnamesapi.herokuapp.com/api/Food-Names?number=2`](https://randomfoodnamesapi.herokuapp.com/api/Food-Names?number=2) returns: ↓
```JSON
[
  {
    "Food_Name": "Gobi Munchuriyan"
  }, 
  {
    "Food_Name": "Chicken fingers"
  }
]
```
