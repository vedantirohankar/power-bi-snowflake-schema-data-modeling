# Table Relationships

| From Table | From Column | To Table | To Column | Cardinality |
|---|---|---|---|---|
| Dim customer | CustomerKey | Sales | CustomerKey | One-to-Many |
| Dim product | ProductKey | Sales | ProductKey | One-to-Many |
| Dim Date | DateKey | Sales | DateKey | One-to-Many |
| Dim geography | GeographyKey | Dim customer | GeographyKey | One-to-Many |
| Dim category | CategoryKey | Dim product | CategoryKey | One-to-Many |
| Dim Date | DateKey | FactBudget | DateKey | One-to-Many |
| Dim category | CategoryKey | FactBudget | CategoryKey | One-to-Many |


#Main purpose of the project is to  demonstrate 
Data modeling
Fact and dimension design
Table relationships
Snowflake schema
Normalized dimensions
