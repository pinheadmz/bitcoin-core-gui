Updated RPCs
------------

- RPC `getaddressinfo` now returns a new boolean field `"isactive"`, which is
only `true` if the address is derived from an active descriptor or HD seed.
This information can inform a user to avoid reusing certain addresses that may
have been imported from external sources or generated by their wallet before it
was encrypted. (#27216)