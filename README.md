# grapher
======

\[Discontinued project\]: This source has been integrated into [https://github.com/McOmghall/autotroll the autotroll project] and every new update should be checked there.

A simple crawler on Wikipedia info written in Ruby using wikimedia JSON API.
It parses the Wikipedia link structure into a database graph structure with decorated nodes:
 - Word counts
 - Title list

All dedicated to topic relationship and edition.

Main purpose is to provide with different information retrieval plugins a generic Wikipedia crawler. 

## History

* First it was a multithreaded adhoc console application made in java with a [PostgreSQL](http://www.postgresql.org/) backend (mid 2012)
* Later it was redone with [Anemone](https://github.com/chriskite/anemone) and a [neoj4](http://neo4j.com/) backend (Start of 2013)
* Considered using [Heritrix](http://crawler.archive.org/index.html "archive.org's crawler") over [neoj4](http://neo4j.com/) or implementing a graph extending algorithm on neo4j (Start of 2014)
* Last try was a Nutch 2.x based approach to a neo4j backend that needed writing the bindings for neo4j for the [Apache Gora project](https://github.com/apache/gora "Apache gora")
