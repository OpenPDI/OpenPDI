# Use of Force (`uof`)

> The use of force can generally be defined as the means of compelling
> compliance or overcoming resistance to an officer’s command(s) in
> order to protect life or property or to take a person into custody.
>
> *-- [Police Data Initiative](https://www.policedatainitiative.org/datasets/use-of-force/)*

## Description of standardized data

Each row in the standardized data contains information for single
officer-subject *Use of Force* incident. If multiple officers or subjects were
involved, there will be multiple rows for the given incident.

| Column name  | Column meaning                                                | Example value |
|--------------|---------------------------------------------------------------|---------------|
| date         | The date of the incident in YYYY-MM-DD format.                | 2015-12-31    |
| state        | The two-letter code for the state in which the stop occurred. | TX            |
| address      | The street address of the incident (upper-cased).             | 1511 FARO DR  |
| city         | The city of the incident.                                     | Austin        |
| latitude     | The latitudinal position of the incident.                     | 37.3860517    |
| longitude    | The longitudinal position of the incident.                    | -122.0838511  |
| service_type |                                                               |               |
| force_type   |                                                               |               |
| reason       |                                                               |               |