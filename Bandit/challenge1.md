# Challenge 1

## Background Knowledge

The premise is that since the file name is “-”, you cannot simply use the“cat” command as the dash already has a default usecase. Therefore you either use input redirection or specify the full path.

## Solution

```

    #since the file name was "-" the default behaviour didn't work, therefore 
    cat < -

    #or you can also use
    cat ./-

```
