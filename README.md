# SolCleaner
mass message cleaner for telegram (inspired by hasol)


## Install dependencies
```
pip install telethon
```
or
```
pip3 install telethon
```


## Issue Telegram Api Key
https://my.telegram.org/


## Configuration
Open solcleaner.py, and edit these fields:
```
api_id = 12345
api_hash = '12345789abcefg'
phone = '<< place here your phone number (include + and nation codes)>> '
```

## Use
1. Run script.
2. If it's the first run, you have to enter the auth code that the Telegram service sent
3. Enter any command in any channel.

## Available Commands
### '#clean'
This command cleans all messages you wrote, until '#cleaner'  
After cleaning done, '#clean' message changed to '#cleaner' for next cleaning.

### '#업데이트확인'
This command checks last update date of webtoon 'DENMA', that published on NAVER WEBTOON.
