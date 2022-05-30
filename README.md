# Safe env: Exit if environment variables known to be used as access tokens are set.

May be used before executing anything that might attempt to steal sensitive
environment variables, like hijacked python or node modules ;)

# Why?

just to have a list of environment variables used by libraries to read your
sensitive authentication tokens, specifically, no wildcards used.
