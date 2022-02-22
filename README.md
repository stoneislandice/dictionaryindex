# dictionaryindex
This simple python script will help you index your digital dictionaries, for the first release, input the pdf of your dictionary and provide a template image of what the big initial indexes look like in your book, after running the script you will receive a pdf file with all the matches in your dictionary as well as the pages where the matches were found.
## Installation

        $ pip install requirements.txt
        $ python3 dictionaryindex.py {dictionary} {index image} {difference=30} {no. dilation iteration=3}
        
        #### dictionary: a pdf file of the dictionary
        #### index image: a screenshot of the first index in the dictionary (see example)
        #### difference: the maximum difference of compared black and white color averages, increasing this value widens the chance of getting matches
        #### no. dilation iteration: the image preprocessing function smudges the image, this is essentially the intensity of the smudge
