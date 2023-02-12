# SwordBattle
### Python-based package for [swordbattle](https://sword-io-game.herokuapp.com/), retrieving data and performing fundamental operations.

# Usage
## Obtain Account Secret
```py
from swordbattle import Client

cli = Client(username="your user", password="your pass")
my_sec = cli.get_secret()
print(my_sec)
```

## Change username
```py
from swordbattle import Client

cli = Client(secret="your secret")
my_usr = cli.change_user("desired user")
print(my_usr)
```
