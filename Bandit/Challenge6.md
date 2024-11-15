# Challenge 6


## Solution

```

    # it mentions that the password is on the server so we need to cd to the 
    # first parent directory
    cd ../
    cd ../

    # searching based on given information and then use grep to find the names
    find . -size 33c -group bandit6 -user bandit7 | grep ".*"

    # however this had a lot of error messages due to inaccessible files so i found a
    # neater solution

    find . -size 33c -group bandit6 -user bandit7 2>/dev/null

    # listed one file so
    cat ./var/lib/dpkg/info/bandit7.password

    # or
    grep '.*' ./var/lib/dpkg/info/bandit7.password

```
