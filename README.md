# London-Transport-Journey-Analysis
This section addresses key design decisions and challenges encountered during the project:

- **Database Choice**: Snowflake was selected for its scalability and ability to handle large datasets efficiently, which is crucial given the volume of transport journey data from TfL.
  
- **Journey Aggregation**: The decision to aggregate journeys in millions was made to keep the results concise and user-friendly, allowing stakeholders to easily interpret data without being overwhelmed by numbers.

- **Error Handling**: During query development, care was taken to handle potential null values effectively, ensuring that analyses remain robust and valid.

- **Performance Optimization**: Indexing and query optimization strategies were employed to improve execution times, especially when dealing with large tables across multiple transport types.

This project reflects a commitment to data integrity and usability, ensuring that stakeholders can draw actionable insights from journey data.
