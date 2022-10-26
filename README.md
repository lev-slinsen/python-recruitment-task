Task: make a function in python that converts one set of data into another.

Incoming:
[
    {'id': 1, 'size': 25, 'color': 35, 'length': 33},
    {'id': 2, 'size': 28, 'color': 35, 'length': 33},
    {'id': 3, 'size': 28, 'color': 37, 'length': 33},
    {'id': 4, 'size': 28, 'color': 38, 'length': 33},
    {'id': 5, 'size': 25, 'color': 28, 'length': 33}
]

Outgoing:
{'size': {25: {'color': {28: {'length': {33: {'id': 5}}},
                         35: {'length': {33: {'id': 1},
                                         24: {'id': 2}}}}}},
 'size': {28: {'color': {37: {'length': {33: {'id': 3}}},
                         38: {'length': {33: {'id': 4}}}}}}}

Number of variables (columns) may be different, aside from `size`, `color`, `length`, there may be other parameters.
Solution should be in a separate file in the same repo.
