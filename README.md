This is a fork of the official release of CGIProxy that's available at http://jmarshall.com/tools/cgiproxy/releases/

This fork includes changes that make it use slightly different parameter names than a standard install of CGIProxy, in an attempt to avoid detection by corporate proxies.

In addition to the changes available in this repo, there are two additional things you can do to try to avoid detection:

* Rename the script from 'nph-proxy.cgi' to something else.
* Serve the script on an https:// port, and use the https version instead.

None of these changes are remotely bullet-proof.  You should never expect total anonymity (particularly if your corporate proxy does MITM HTTPS snooping).  These changes ONLY avoid automatic detection by default installations of corporate-proxies.  If the logs are manually reviewed, the proxy use will be pretty obvious.
