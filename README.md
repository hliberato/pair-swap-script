# pair-swap-script
Simple bash script to generate pairs

The script receive two parameters:
-a: anchors
-f: floating

the list should be separated by commas

Example:

`$ ./pair-swap.sh -a ania,tom,john -f megan,james,sarah`


On OXS you could need install `coreutils`:

`$ brew install coreutils`

If running with ZSH (Z shell):

`$ bash pair-swap.sh -a ania,tom,john -f megan,james,sarah`
