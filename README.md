# dupe.sk
A simple dupe Skript, with an item-type and NBT blacklist.

Blacklist features include, checking held shulker box inventories and checking specific NBT data.

### Here is an example of using NBT data to blacklist specific items.
> give player netherite helmet named "Blacklisted Helmet" with nbt compound from "{blacklisted:true}"

### This Skript contains two commands that can be used by any player. 
> /blacklist will send the player the text stored inside the option {@blacklistMessage}

> /dupe [1-10] will duplicate the player's held item as long as does not contain/is not a blacklisted item. The INT argument can be used to duplicate multiple items at the same time, if this argument is left empty it will simply duplicate their held item once. However if the player has the permission stored inside of option {@dupeamount.three} they will be able to duplicate up to three of their held item at once. If the player has the permission stored inside of option {@dupeamount.six} they will be able to duplicate up to six of their held item at once. If the player has the permission stored inside of option {@dupeamount.ten} they will be able to duplicate up to ten of their held item at once.
