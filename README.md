# Advanced-Python-modules


This section contains all the Advanced Python modules that are used in Python

1. Counter
2. OrderedDict
3. Defaultdict
4. namedtuple
5. datatime : This is used in Monkey Patching.Monkey patching is changing a functions inside some modules or method of some classes, when you don't have access to change source codes. Monkey patching occur in the runtime
6. Timing your code
7. Regular expressions:
        a. re.search(pattern, text)
        b. match.start() and match.end() to find the indexes of the matched terms
        c. re.split(split_term,phrase)
        d. re.findall('match','test phrase match is in middle')
        e. test_phrase = 'sdsd..sssddd...sdddsddd...dsds...dsssss...sdddd'

            test_patterns = [ 'sd*',     # s followed by zero or more d's
                'sd+',          # s followed by one or more d's
                'sd?',          # s followed by zero or one d's
                'sd{3}',        # s followed by three d's
                'sd{2,3}',      # s followed by two to three d's
                ]
        f. test_phrase = 'sdsd..sssddd...sdddsddd...dsds...dsssss...sdddd'

            test_patterns = [ '[sd]',    # either s or d
            's[sd]+']   # s followed by one or more s or d
        g. Excluding: re.findall('[^!.? ]+',test_phrase)
        h. test_phrase = 'This is an example sentence. Lets see if we can find some letters.'

            test_patterns=[ '[a-z]+',      # sequences of lower case letters
                '[A-Z]+',      # sequences of upper case letters
                '[a-zA-Z]+',   # sequences of lower or upper case letters
                '[A-Z][a-z]+'] # one upper case letter followed by lower case letters
        i. Escape Codes: test_phrase = 'This is a string with some numbers 1233 and a symbol #hashtag'

            test_patterns=[ r'\d+', # sequence of digits
                r'\D+', # sequence of non-digits
                r'\s+', # sequence of whitespace
                r'\S+', # sequence of non-whitespace
                r'\w+', # alphanumeric characters
                r'\W+', # non-alphanumeric
                ]

        
