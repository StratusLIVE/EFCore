StratusLIVE Entity Framework Core Binaries
====================

This holds binaries for Entity Framework 2.2.0 with two incorporated bugfixes: one that checks for nulls in Geometry comparison which has not yet been incorporated into the main codebase; and another that disables a routine that ends up causing an exponential increase in time to load more objects from the database, even when tracking is disabled.

Use
====================

Do not use this repository for anything. The binaries are included in a build step that publishes nuget packages that are then used from one or more of the PlatformCore projects.