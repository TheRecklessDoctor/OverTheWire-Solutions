# Challenge 0


## Knowledge Needed 

**SSH - Secure Shell Protocol**

A cryptographic network protocol for operating network services securely over an unsecured network. Most commonly used for secure access to remotemachines. It uses encryption mechanisms to ensure that malicious actors won’t understand the message even if they have access to the entire data stream.

SSH uses public-private key cryptography to authenticate a remote connection and a user if necessary.

**Port**

A connection endpoint uniquely identified by a number. It directs data toa specific service.

## Solution

```

    # connect to the remote machine via ssh
    ssh bandit0@bandit.labs.overthewire.org -p 2220

    # next we decided to look at directory contents
    ls

    # found a file called readme so we looked at its contents
    cat readme

```
