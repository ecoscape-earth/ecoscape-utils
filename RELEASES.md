0.0.36: 

- Added `min_time` option to `get_all_squares` and `get_square_observations` to filter checklists by minimum duration.

0.0.37: 

- Now the breeding season is represented via a pair like ("04", "06") indicating the first and last month of breeding season.  This also means the default is uniformly None. 

0.0.39: 

- Fixed bugs in min_time parameter.

0.0.40: 

- Fixed bug in DB query quoting. 

0.0.42: 

- Added `get_state_checklists` function to get all checklists in a state.
- Deprecated old ways of reading checklists by state or square.
