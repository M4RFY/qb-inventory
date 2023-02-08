# qb-inventory with decay system CSS Rework

# Dependencies
* [QBCore Framework](https://github.com/qbcore-framework)
* [qb-target](https://github.com/BerkieBb/qb-target)
* [qb-core](https://github.com/qbcore-framework/qb-core)

# How to install
* Download source files from github
* Drag source files into your resources folder
* Rename folder to `qb-inventory`

# TO DO
you need to add a decay and created value in your qb-core/shared/items for all items, the decay is set to be the days the item lasts
<br>

```lua
-- created = this will get filled in with the time when it's created, just leave this
-- decay = amount of days that an item will decay
-- delete = choice whether to remove the item when it's decayed or not
["created"] = nil, ["decay"] = 28.0, ["delete"] = true
```
<br>
Example:
<br>

```lua
['sandwich'] = {['name'] = 'sandwich', ['label'] = 'Sandwich', ['weight'] = 200, ['type'] = 'item', ['image'] = 'sandwich.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true,	['combinable'] = nil, ['description'] = 'Nice bread for your stomach', ["created"] = nil, ["decay"] = 3.0, ["delete"] = true},
```
In this example our sandwich will decay in 3 days and removed when used.
<br>

# Previews
![full inventory](https://cdn.discordapp.com/attachments/1003822642379374703/1072838189796036649/inv.png)

<br>

# Credits
* [qb-inventory-decay](https://github.com/i-kulgu/qb-inventory-decay)
* [lj-inventory](https://github.com/loljoshie/lj-inventory) 

<br>
