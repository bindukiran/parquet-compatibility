parquet-compatibility
=====================

compatibility tests to make sur C and Java implementations can read each other

Submodules:
-----------
* parquet-compat
* parquet-testdata
* parquet-compat-$version

parquet-compat
--------------
This stores the test sources. This is not a maven submodule.

parquet-testdata
----------------
stores all the csvs and impala files (todo discuss impala compatibility test)

parquet-compat-$version:
------------------------
pom.xml has dependency on the corresponding version of parquet-mr.
src is a symlink to sources in parquet-compat (../parquet-compat/src).
