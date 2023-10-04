# FAQ

## What is this?
A repository with a list of hassh fingerprints and the associated client names observed with it. All fingerprints are gathered from systems actively trying to log in to other systems via ssh on port 22.

## Ok, what is hassh?

From the [Salesforce github description](https://github.com/salesforce/hassh) of 'hassh':

HASSH is a network fingerprinting standard which can be used to identify specific Client and Server SSH implementations. The fingerprints can be easily stored, searched and shared in the form of a small MD5 fingerprint. 

## What do the files contain?
Both files contain the hassh fingerprints, how many times they have been observed (since october 2022), and the associated client names observed with it.

Content snippets:

csv:

<pre>
hassh,observations,versions
51cba57125523ce4b9db67714a90bf6e,4222603,SSH-2.0-libssh-0.6.3,SSH-2.0-libssh-0.6.0
f555226df1963d1d3c09daf865abdc9a,1409102,SSH-2.0-libssh_0.9.6,SSH-2.0-libssh_0.9.5
01ca35584ad5a1b66cf6a9846b5b2821,1302807,SSH-2.0-Go
</pre>

json: 
<pre>
[{
		"hassh": "f555226df1963d1d3c09daf865abdc9a",
		"observations": 4222603,
		"versions": "SSH-2.0-libssh_0.9.6, SSH-2.0-libssh_0.9.5"
	},
	{
		"hassh": "51cba57125523ce4b9db67714a90bf6e",
		"observations": 1409102,
		"versions": "SSH-2.0-libssh-0.6.3, SSH-2.0-libssh-0.6.0"
	},
	{
		"hassh": "01ca35584ad5a1b66cf6a9846b5b2821",
		"observations": 1302807,
		"versions": "SSH-2.0-Go"
	},
 
</pre>

## How often is this updated?
Currently, when time permits.
