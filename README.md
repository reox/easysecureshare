Easy File Share via HTTPS (PoC)
===============================

This is a proof of concept to share files via https with single use.

This can be used to share a single file (that the user can read) on HTTPS to another host.
The main idea is, that a one time use token is generated that is hard to guess and the file
is shared via this link.

It should only use builtin python libraries + openssl, thus the script itself should be very portable.


**USE WITH CAUTION!** It is only a PoC!
