## Alert Conditions

An alert is triggered if any of the following conditions are met:

- Time in deficit > 30%
- Maximum deficit event < -5000 MWh

Values are explicitly coalesced to avoid NULL values
before evaluation to prevent runtime failures.
