# Hacked Reatta CUSP

I'm not naming any names, or giving up any contacts on where this came from or where it might have been used (frankly, I don't even really remember).   *I* never used it.  I promise.

Basically it's a trojan horse attack.   It's an exact replica of the normal REATTA  program (attach to detatched job).
But, it has a magic command which causes it to copy the acct.sys password file into the local directory (the passwords in the day were not hashed and were in clear -- more innocent times I guess).

You'd have to sneak in an overwrite the regular reatta.exe with this one on a live console with privs.
