## Flow Overview

1. Scheduled trigger (hourly)
2. Execute DAX query against Fabric dataset
3. Parse JSON results
4. Iterate over result rows
6. Apply alert thresholds
7. Trigger notification action (email)
