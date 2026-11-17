# Universe Database 🌌

A PostgreSQL database project created as part of the **freeCodeCamp Relational Database Certification**.

This project models astronomical objects and their relationships, including galaxies, stars, planets, and moons.

## Database Structure

The database is named `universe` and contains five tables:

| Table | Description |
|---|---|
| `galaxy` | Stores information about galaxies |
| `star` | Stores stars and their associated galaxies |
| `planet` | Stores planets and their associated stars |
| `moon` | Stores moons and their associated planets |
| `planet_types` | Stores categories of planets |

## Relationships

The database uses primary keys and foreign keys to maintain relationships:

- Each star belongs to a galaxy.
- Each planet belongs to a star.
- Each moon belongs to a planet.

## Technologies Used

- PostgreSQL
- SQL

## Database Features

- Primary keys with auto-incrementing sequences
- Foreign key constraints
- `NOT NULL` and `UNIQUE` constraints
- Multiple data types, including `VARCHAR`, `INTEGER`, `NUMERIC`, `TEXT`, and `BOOLEAN`
- Relational database design

## Project Data

| Table | Number of Records |
|---|---:|
| Galaxy | 6 |
| Star | 6 |
| Planet | 12 |
| Moon | 20 |
| Planet Types | 3 |
| **Total** | **47** |

## How to Use

1. Install PostgreSQL.
2. Download or clone this repository
