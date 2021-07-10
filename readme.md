# SmsServiceOnline 
`pip3 install SmsServiceOnline==1.0.2`

## Example #1
```python
import SmsServiceOnline

KEY = "<api key here>"
LANG = "ru"
MESSAGE = False


api = SmsServiceOnline.Api(
    api_key=KEY,
    lang=LANG,
    welcome_message=MESSAGE,
)

api.get_balance()
```
```python
>>> 10.2
```

### all methods -> [here](https://sms-service-online.com/ru/api-sms-activate/)  

---
```by @fxcvd with ❤```