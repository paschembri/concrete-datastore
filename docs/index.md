## Introduction

This document is a user guide to Concrete Datastore and its features.

Concrete Datastore is a Datastore generator that consumes a datamodel file containing a database description, and dynamically generates the corresponding tables.

Concrete Datastore exposes a Restfull API to allow its users to interact with the database by **C**reating, **R**etrieving, **U**pdating and **D**eleting data (**CRUD**).

In order to gain access or modify the database’s data, each request must be authenticated with a unique token for each user (see [authentication](authentication.md) section). This allows Concrete Datastore to know which user is using the plateform. The desired actions depend on the user’s permissions (see [permissions](permissions.md) and [roles](roles.md) sections).

Concrete Datastore also allows its users to have full control on the data requested by enabling a filtering mechanism on the different elements of the database (see [filters](filters.md) section).

## Table of contents

- [API Authentication](authentication.md)
- [API Routes](api-routes.md)
- [API Filters](filters.md)
- [API Permissions](permissions.md)
- [API Roles](roles.md)
- [Tutorials](demo.md)
