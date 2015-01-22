# takiwaR 0.0.1.0

Initial release!

## mchi()

- Calculates an Marine Cultural Health Index Score.
- An as.char argument that returns all data as nicely formatted strings.
- A simple print method which prints aforementioned nicely formatted strings.

## mchi_wspp()

- Provides a weighting function for species scores.
- Currently faithfully reproduces the provided Excel Spreadsheet (i.e. 20% reduction in relative importance per species).

## mchi_as_char()

- A non-exported (i.e. non-user-accessible) function to return numbers as nicely formatted strings.
- Currently rounds percentages to zero decimal places and everything else to two decimal places.  
- Not intended for general use!