<pre><div align="center">  
 ██░ ██ ▄▄▄       ██████  ██████ ██░ ██     ▄████▄  ██▓    ██▓█████ ███▄    █▄▄▄█████▓ ██████ 
▓██░ ██▒████▄   ▒██    ▒▒██    ▒▓██░ ██▒   ▒██▀ ▀█ ▓██▒   ▓██▓█   ▀ ██ ▀█   █▓  ██▒ ▓▒██    ▒ 
▒██▀▀██▒██  ▀█▄ ░ ▓██▄  ░ ▓██▄  ▒██▀▀██░   ▒▓█    ▄▒██░   ▒██▒███  ▓██  ▀█ ██▒ ▓██░ ▒░ ▓██▄   
░▓█ ░██░██▄▄▄▄██  ▒   ██▒ ▒   ██░▓█ ░██    ▒▓▓▄ ▄██▒██░   ░██▒▓█  ▄▓██▒  ▐▌██░ ▓██▓ ░  ▒   ██▒
░▓█▒░██▓▓█   ▓██▒██████▒▒██████▒░▓█▒░██▓   ▒ ▓███▀ ░██████░██░▒████▒██░   ▓██░ ▒██▒ ░▒██████▒▒
 ▒ ░░▒░▒▒▒   ▓▒█▒ ▒▓▒ ▒ ▒ ▒▓▒ ▒ ░▒ ░░▒░▒   ░ ░▒ ▒  ░ ▒░▓  ░▓ ░░ ▒░ ░ ▒░   ▒ ▒  ▒ ░░  ▒ ▒▓▒ ▒ ░
 ▒ ░▒░ ░ ▒   ▒▒ ░ ░▒  ░ ░ ░▒  ░ ░▒ ░▒░ ░     ░  ▒  ░ ░ ▒  ░▒ ░░ ░  ░ ░░   ░ ▒░   ░   ░ ░▒  ░ ░
 ░  ░░ ░ ░   ▒  ░  ░  ░ ░  ░  ░  ░  ░░ ░   ░         ░ ░   ▒ ░  ░     ░   ░ ░  ░     ░  ░  ░  
 ░  ░  ░     ░  ░     ░       ░  ░  ░  ░   ░ ░         ░  ░░    ░  ░        ░              ░  
                                           ░                                                  
 </div></pre>    
 
# FAQ

## What is this?
A repository with a list of hassh fingerprints and the associated client names observed with it. All fingerprints are gathered from systems actively trying to log in to other systems via ssh on port 22.

## Ok, what is hassh?
[Salesforce page on hassh](https://github.com/salesforce/hassh)

## What does the file contain?
A csv file containing the hassh fingerprint, how many times it it has been observed (since october 2022), and the associated client names observed with it.

The csv file contains the following and is formatted as below:

<pre>
hassh,observations,versions
51cba57125523ce4b9db67714a90bf6e,1363148,SSH-2.0-libssh-0.6.3,SSH-2.0-libssh-0.6.0
f555226df1963d1d3c09daf865abdc9a,1126497,SSH-2.0-libssh_0.9.6,SSH-2.0-libssh_0.9.5
01ca35584ad5a1b66cf6a9846b5b2821,484518,SSH-2.0-Go
</pre>

## How often is this updated?
Currently, when time permits.
