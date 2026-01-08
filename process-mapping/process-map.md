## Process mapping
Ingest Data
   ↓
MS Fabric
   ↓
Store data in Datalake
   ↓
Clean data & Make tables (PySpark & SQL)
   ↓
Model & Define KPIs (Dax measures)
   ↓
Validate in BI (Power BI or Fabric)
   ↓
Power Automate
   ↓
Scheduled trigger (hourly)
   ↓
Automated DAX Query (against Fabric dataset)
   ↓
Parse JSON response
   ↓
Normalize (null and type handling)
   ↓
Evaluate Conditions
   ↓
[ Alert mail Sent ] OR [ No Action ]

