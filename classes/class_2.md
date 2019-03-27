# Restroom
## Attributes
in_service : (boolean)
gendered : (boolean)
gender: (string)
total_stalls: (integer)
occupied_stalls: (integer)
clean: (boolean)

## Methods
is_in_service: (if in_service = true returns true)
is_gendered: (if gendered = true returns true)
which_gender: (if gendered = true returns value of gender)
free_stalls: (total_stalls - occupied stalls returns integer)
