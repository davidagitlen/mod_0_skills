# Seating area
## Attributes
* capacity: (integer)
* type: (string)
* current_number_of_occupants: (integer)
* current_occupants: (array)
* clean: (boolean)

## Methods
* is_table: (if type = table returns true)
* is_booth: (if type = booth returns true)
* open_spaces: (capacity - current_number_of_occupants returns integer)
* insert_occupant_name: (adds occupant name into array)