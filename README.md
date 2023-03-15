# Formula1

### Data Used: 
Motor Racing Sport Formula1, downloaded from eargast API.
### Data Contains: 
The data contains the information about the Formula1 sport,
`It has eight files:` circuits, Races, Constructors, Drivers, Results, Pitstops, Laptimes, Qualifying data.

### Data Ingestion Requirements: 
1.Ingested data must have the schema applied.

2.Ingested data must have audit columns

3.Ingested data must be stored in columnar format.

4.Must be able to analyze the ingested data via SQL

5.Ingestion logic must be handle incremental load.

### Data Transformation Requirements: 
1. Join the key information required for reporting to 
   create a new table
2. Join the key information required for Analysis to 
   create a new table
3. Transformed tables must have audit columns
4. Transformed data must be stored in columnar format.
5. Must be able to analyze the transformed data via SQL
6. Transformed logic must be handle incremental load.

### Reporting Requirements:
1. Driver Standings
2. Constructor Standings

### Analysis Requirements:
1. Dominant Drivers
2. Dominant Teams

### Solution Architecture:
![image](https://user-images.githubusercontent.com/97723040/225224385-d0a5dc2b-ea32-4357-b879-87fbaa6b4522.png)
