# Beer_song
# A practice of python basic function
word = 'bottles'
for bottle_number in range(99, 0, -1):       # The start number is 99, stop number is 0 which will not be generated, and the step is -1
    print(bottle_number, word, 'of beers on the wall.')
    print(bottle_number, word, 'of beers')
    print('Take one down.')
    print('Pass it around')
    if bottle_number == 1:
        print('No more bottles of beer on the wall.')
    else:
        new_bottle = bottle_number - 1
        if new_bottle == 1:
            word = 'bottle'
        print(new_bottle, word, 'of beer on the wall.')        # the print statement is in the save level of indentation as 'if'
                                                               # no need for 'else' again, becase we just need to change the unit when '1'
    print()
