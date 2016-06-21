# quoteit

Pipe a column of un-quoted text throuh `quoteit` to create a line of quoted text.

sample.txt:

    1
    2
    3
    4
    5
    6
    7
    8
    9
    10
    11
    12
    13

Here's how it's used:

    quoteit < sample.txt
    '1', '2', '3', '4', '5', '6', '7', '8', '9', '10', '11', '12', '13'
