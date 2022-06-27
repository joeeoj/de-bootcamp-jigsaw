# Jigsaw Labs: Data Engineering Bootcamp

https://www.jigsawlabs.io/

Start: Wed June 15, 2022

Class days:

* Tu/Wed/Th 3:30 PM - 6:30 PM PST
* Sun 9:30 AM - 6:30 PM PST

### module 1 - analytics engineering

* weeks 1 - 12
* Python: Data Structures, Functions, Apis, OOP
* SQL: Postgres, Snowflake
* ELT Pipelines: Fivetran, DBT, Mode

### module 2 - data engineering

* weeks 13 - 24

* Flask: ORMs, MVC, Adapter Pattern
* Cloud: Docker, AWS EC2
* Pipelines: Airflow, AWS S3, RDS, Redshift

----------

## week 01 - data structures in python

* Datatypes
    * lists and strings
* error messages
    * dictionaries
* exploring data types
    * nested dicts
* writing outlines
* string and dictionary quiz
* preparing data
    * changing data
    * loops vs list comprehension
* list of dictionaries
    * sorting data
* list comprehension
    * review of split and join
* conditionals
    * truthy and is
    * filtering with lists

## week 1 outline

I. Datatypes

A. Primitives
* Strings
    * `', '.join(['a', 'b', 'c'])`
    * `'this is a test'.split(' ')`
* Integers

B. Collections
* Lists - ordered
    1. Mutation
        * append
        * pop
    2. Selection
        * by index i.e. `values[0]`
    3. Coercing
* Dictionaries - unordered
    1. Mutation
        * append
        * pop
    2. Selection
        * by index i.e. `values[0]`
    3. Coercing
        * `list({'a': 1, 'b': 2}) -> [('a', 1), ('b', 2)]`
* Sets - unordered
    1. Mutation
        * `vals.add(5)` - add just one item
        * `vals.update([1, 2, 3])` - add multiple items
    2. Selection
        * by index i.e. `values[0]`
    3. Coercing

II. Functions

## week 02

Note-taking app suggestion: [Obsidian](https://obsidian.md/)

* list comprehension
    * `[val for val in values]`
* filtering with list comprehension
    * `[n for n in nums if n % 2 == 0]`
* functions
* variable scope
