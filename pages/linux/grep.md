# grep

> Utility to search text for a regex pattern.

- Search for a pattern in a file:

`grep {{regex pattern}} {{file_to_search}}`

- Search for a pattern from `stdout` pipe:

`command | grep {{pattern}}`

- Search using patterns from a file:

`grep -f {{patterns_file}} {{file_to_search}}`
