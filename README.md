# Battlesimulator
Part 0 / 4:
● Getters used from the Pokemon class in the Battle class: get_num(), get_name(),
get_kind(), get_pokemon_type(), get_hp(), get_owner().
● Setters used from the Pokemon class in the Battle class: set_hp().
Methods used from the Pokemon and Person classes in the menu for the Battle class:
● From the Pokemon class: print_all_pokemon(), print_non_owned_pokemon().
● From the Person class: None.
Part 1:
● For looking up the Pokemon object based on the number, a for loop was used to iterate
through the __all_pokemon_list in the Pokemon class.
● To print only Pokemon without owners in the second method, a list comprehension was
used to filter Pokemon without owners from the __all_pokemon_list.
Part 2:
● A list was used to store the two Pokemon objects in the Battle class.
● Getters and setters from the Battle class were used when updating and retrieving
information about Pokemon and battle results.
Part 3:
● A while loop was used for the rounds of the Battle.
● The Battle stops when either of the battling Pokemon has HP less than or equal to 0,
indicating the end of the battle.
