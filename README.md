# SwordBattle
### Python-based package for [swordbattle](https://sword-io-game.herokuapp.com/), retrieving data and performing fundamental operations.

# Usage
## Obtain Account Stats
```py
from swordbattle import Client

cli = Client("us1", "your secret")
data = cli.get_data()
print(data)
```

## Change username
```py
from swordbattle import Client

cli = Client(secret="your secret")
my_usr = cli.change_user("desired user")
print(my_usr)
```
