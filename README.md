# Frota bootstrap-only

This public repository distributes only an immutable, secret-free bootstrap
bundle for the gateway infrastructure executor. It is not the source of truth
for Frota Core, governance, agent memory, configuration, credentials, or
business data.

The bundle is pinned to private canonical source commit `91453c1`.
The bundle is generated from Git blobs with LF-preserving attributes and is
validated by the Linux runtime integration gate before publication.
