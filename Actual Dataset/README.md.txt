The Dataset Airline Operations and Passenger Data consists of the following tables:

1. aircrafts_data
2. airports_data
3. boarding_passes
4. bookings
5. flights
6. seats
7. ticket_flights
8. tickets

Step 1: Start sqlite using the command: sqlite3 travel.sqlite

Step 2: Perform the following actions for each table name:
sqlite> .headers on
sqlite> .mode csv
sqlite> .output table_name.csv
sqlite> SELECT * from table_name
sqlite> .quit


The Database once converted to CSV is now ready to perform actions on. Following which we will first clean the data, normalize it and then we will create dashboards from the cleaned data