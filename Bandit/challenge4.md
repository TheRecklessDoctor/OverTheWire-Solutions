# Challenge 4


## Solution

```

    # move into inhere
    cd inhere

    # list all files including hidden
    ls -al

    # it was mentioned that the password was in the only human-readable file in the 
    # directory. Therefore it has to be text of some sort. There were 10 files with the 
    # same file name eg: -file00, -file01 and so on..
    # Therefore we first found the file type

    file ./-file{00,01,02,03,04,05,06,07,08,09} 
    # file command with expansion to avoid typing -file over and over.

    #only -file07 was of ascii-text, others were data type

    cat ./-file07

```
