# sublime-ssl-windows

This is a Sublime Text dependency that adds a custom `_ssl` shared
library to the following versions of Sublime Text:

 - ST2 on Windows (x32 and x64)

The reason this dependency is necessary is because the `_ssl.pyd` included with
Sublime Text 2 on Windows is linked against an old version of OpenSSL that does
not support SSL certificates using SHA-2 signatures.

Package Control will not work with Sublime Text 2 on Windows without this
dependency installed.
