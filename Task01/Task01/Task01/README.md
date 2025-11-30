# Dataset Description

## File: ratings.csv

This file contains movie ratings data with the following structure:

### Columns:
- **userId**: Identifier of the user who gave the rating (integer)
- **movieId**: Identifier of the rated movie (integer) 
- **rating**: Rating score given by the user (float, from 0.5 to 5.0)
- **timestamp**: Unix timestamp when the rating was recorded (integer)

### Data Characteristics:
- Total records: 100,004 (including header)
- User IDs range: 1 to 120
- Rating scale: 0.5 to 5.0 (in 0.5 increments)
- Each user has multiple ratings

### Sample Data:
userId,movieId,rating,timestamp
1,1,4.0,964982703
1,3,4.0,964981247
1,6,4.0,964982224

## File: ratings_count.txt
Contains summary statistics:
- First line: Minimum user ID and their rating count
- Second line: Maximum user ID and their rating count

Example:
1 232
120 22

## File: sqlite.txt
Contains SQLite version information and available output modes.
