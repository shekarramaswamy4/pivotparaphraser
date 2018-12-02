# pivotparaphraser
python script used to augment training sets for nlp models

This script converts the input line to the languages specified sequentially. The impetus for this script was to better expand
training sets for nlp models. 

Has two modes, single translation (--query flag) or file reading (--inFile flag). Can specify output file (--outFile flag)
for file inputs.

example input: python pivotparaphraser.py --query='How many states in California' --lang=ru|ko
This command will translate the english query into russian, and then from russian to korean. 

