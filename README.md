# StegaSudoku
A proposed method of transfering arbitrary files via unsolved sudoku puzzles

Software will take hexcode or simple text, map this to a solved sudoku puzzle, add a given number of rule systems to minimize numbers needed to solve the puzzle, and output an image of an unsolved puzzle or simply the coordinates and ruleset ( minimised to a few letters to further reduce transfer file size ).

This will not be a particularly effecient method of data transfer, especially because often data cannot be mapped perfectly onto a given solution. The way this mapping will work is to have a companion image with output that can be overlayed to tell which numbers and in what order are a part of the data. Or alternatively a barcode/qr, but it all depends on the desired discretion because then that would just be the way data is encoded.
