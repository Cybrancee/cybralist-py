# cybralist 
useful library for [cybralist.com](https://cybralist.com)

# API DOCS
Link to api docs: [API DOCS](https://docs.cybralist.com)

## Installation
```
pip install cybralist
```
## example 
Server Count Post :
```python
from cybralist import cybralist
from discord.ext import commands

client = commands.Bot(command_prefix="!") 
dbl = cybralist(client,"token of cybralist")

@client.event
async def on_ready():
  x = await dbl.serverCountPost()
  print(x)

client.run("token")
```

Search bot: 
```python
from cybralist import cybralist

client = commands.Bot(command_prefix="!") 
dbl = cybralist(client,"token of cybralist")
id=botid

a = dbl.search(id)
print(a)

```
All functions in api:
```angular2html
1: serverCountPost()
2: search()
3: hasVoted()
```


**JOIN OUR DISCORD SERVER FOR SUPPORT**\
[DISCORD LINK](https://cybralist.com/discord)

