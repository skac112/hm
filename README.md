# hm

**h**ierarchy **m**apping - library for mapping objects classes from one hierarchy to the other.

## Problem statement

There are two class hierarchies (source hierarchy and destination hierarchy) and a mapping between them. There is also an object with assigned classes (many, in general) from source hierarchy.
The task is to assign classes from destination hierarchy to the object.

# Hierarchies

Hierarchies are multi-inheritance in general, i.e. each class can have multiple ancestors. They are explicitly declared and modeled as DAGs (directed acyclic graphs).

# Mapping

Mapping from source hierarchy (sh) do destination hierarchy (dh) is explicitly declared and modeled by a map of pairs:

(source class -> destination class).

Such a pair maps not only source class to destination class but also implicitly maps all subclasses of source class to destination class.





