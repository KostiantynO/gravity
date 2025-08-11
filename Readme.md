Mount&Blade Module System

For getting documentation and the latest version of the module system check out:

[TaleWorlds MB WB](https://www.taleworlds.com/en/Games/Warband)

[Download mb_warband_module_system_1171](https://download.taleworlds.com/mb_warband_module_system_1171.zip)

[x] print is a function.

```py
print stuff
# to
print(stuff)
```

[x] string.replace():

```py
import string
string.replace('a','') # as import module

# to
s0:str = ""
s0.replace('a','') # method on string itself
```

[x] types.ListType:

```py
if (type(statement) != types.ListType) and (type(statement) != types.TupleType):
# to
if not isinstance(statement, (list, tuple)):
```

[x] types.StringType:

```py
if (type(param) == types.StringType):
# to
if isinstance(param, str):
```
