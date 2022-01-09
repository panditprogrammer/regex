# Regualr Expression by  Pandit Programmer


# Flags :
           1. g - Global (more than one occurances)
           2. i - case in-sensitive
           3. . - (period) is used to checking next character anything
           4. ^ - Not specified (Exclude)
           5. + - One or Multiples times occurances
           6. * - zero or Multiples times occurances
           7. ? - lazy way string (sortest string finding)
           8. ? - previous character is optional
           9.  (?) - lookahead 
           10.  ^ - starting string 
           11.  $ - ending string

# Quantifiers - define the occurances using curly braces
         {2,10} -  => aleast two characters at beginning and end ten characters only
         {2,} -  => aleast two characters at beginning and end infinite characters 
        {minimum, maximum }  => aleast min characters at beginning  and max  characters at the ending

# Escape Sequences:
        \w - all characters small and capitals with numbers and underscore
        \W - Not (all characters small and capitals with numbers and underscore)
        \d - all digits or numbers only
        \D - Not (all digits or numbers)
        \s - white spaces only including TAB, SPACE,RETURN etc. 
        \S - Not (white spaces )