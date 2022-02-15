# Ultimate tic-tac-toe

The code can be easily explored through the notebook file. Just load it on https://swish.swi-prolog.org

The main.pl file is a raw copy, so as to run the code on a Prolog interpreter.

## Requirements
Ensure encoding is set to utf8

`current_prolog_flag(encoding,utf8).`

Otherwise, set it through the init.pl file

`set_prolog_flag(encoding, utf8).`


## How to play

`start_game(<Game>, <player_x_type>, <player_o_type>).`
  
`start_game(tic_tac_toe|ultimate, ai|human, ai|human).`
  
e.g. `start_game(ultimate, ai, human).`