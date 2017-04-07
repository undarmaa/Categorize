# Categorize
categorizer - input text and dictionary, and script assigns categories based on dict
work in progress

goal is to have several was of the same process

1) exact matching - finished, text has to match the dictionary term exactly to be assigned 
     - dog, dog = match; dog, do = no match
2) partial matching - in progress, text contains term from dictionary as a substring (case sensitive)
     - dog, dog = match; dog, do = match
3) approximate matching - done, approximate matching based on Levenshtein distance, cut-off based on % matching
