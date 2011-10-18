A set of utilities and improvements for managing data (fixtures specifically) in Django.

dumpdata
--------

An improved version of the ``manage.py dumpdata`` command:

* Adds a --limit option to specify the maximum number of objects per model to fetch.
* Adds a --sort option to specify ascending or descending order for serialization.
* Automatically follows the dependency graph for ForeignKeys and ManyToManyFields.