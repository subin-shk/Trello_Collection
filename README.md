### Trello Postman API Collection


## Before running test requests make sure to create New Environment and keep the environment variables as follow: 

```
BASE_URL: https://api.trello.com
KEY: API_KEY
TOKEN: API_TOKEN
```
<b>Replace <i>API_KEY</i> and <i>API_TOKEN</i> with your api key and token</b>

## Steps to generate key and token

Make your trello acc key and token and keep it in environment variables
- Create [Power up](https://trello.com/power-ups/admin/new)
- Copy the API_KEY and paste it as current value in environment variable with key, "KEY".
- Generate Token by going to the following website: 
```
https://trello.com/1/authorize?expiration=1day&scope=read&response_type=token&key={YourAPIKey}
```
<i>(replace {YourAPIKey} with your actual key)</i>
- Copy the API_TOKEN and paste it to environment variable with key, "TOKEN".
