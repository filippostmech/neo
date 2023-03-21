# (n)ear-(E)arth (o)bjects 
Search for and explore close approaches of near-Earth objects (NEOs), 
using data from NASA/JPL's Center for Near-Earth Object Studies.

## Overview
At a high-level, I will implement a command-line tool to inspect and 
query a dataset of NEOs and their close approaches to Earth.

Concretely, I'll have to read data from both a CSV file and a JSON file, convert that 
data into structured Python objects, perform filtering operations on the data, limit the size 
of the result set, and write the results to a file in a structured format, such as CSV or JSON.

When complete, I want to be able to inspect the properties of the near-Earth objects in the 
data set and query the data set of close approaches to Earth using any combination of the 
following filters:

- Occurs on a given date.
- Occurs on or after a given start date.
- Occurs on or before a given end date.
- Approaches Earth at a distance of at least (or at most) X astronomical units.
- Approaches Earth at a relative velocity of at least (or at most) Y kilometers per second.
- Has a diameter that is at least as large as (or at least as small as) Z kilometers.
- Is marked by NASA as potentially hazardous (or not).

## Further Reading:
NEO Earth Close Approaches: 
- [A friendly UI reviewing close approaches to Earth in the near future.](https://cneos.jpl.nasa.gov/ca/)
- [Project Repository: The GitHub repository for the final project for the course.](https://github.com/udacity/cd0010-advanced-python-techniques-project-starter)