# lua-rover

**This is an older version, archived for building legacy APICast instances.**

The original build process relied on the "master" branch of Luarocks, which
included an unversioned and unsplit Lua Rover rock. To address this limitation
and enable building specific APICast versions, a new rock and this repository
were created.

A wrapper around LuaRocks (and OPM in the future) to provide transitive locking for dependencies.
