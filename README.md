# Traffic Incident Analysis

A data-driven project exploring traffic incident records to understand how location, time, and contextual information relate to road events. This repository focuses on loading and understanding the structure of the dataset as the first step toward a broader analysis.

---

## Objectives (So Far)

- [X] Load raw traffic incident dataset
- [X] Inspect column names, data types, and overall structure
- [X] Document dataset schema for reference
- [ ] Clean and transform date/time fields
- [ ] Perform exploratory data analysis (EDA)
- [ ] Visualize trends and patterns

---

## Dataset Schema

| Column Name       | Data Type | Description                                 |
|-------------------|-----------|---------------------------------------------|
| `Date`            | object    | The date the incident occurred              |
| `Time`            | object    | The time the incident occurred              |
| `City`            | object    | City where the incident took place          |
| `Location`        | object    | Textual location description                |
| `Latitude`        | float64   | Latitude coordinate of the incident         |
| `Longitude`       | float64   | Longitude coordinate of the incident        |
| `High_Accuracy`   | int64     | Indicator of GPS accuracy (1 = high)        |
| `Direction`       | object    | Direction of travel (if available)          |
| `Type`            | object    | Type of incident (e.g., accident, hazard)   |
| `Lanes_Blocked`   | float64   | Number of lanes blocked (if any)            |
| `Involved`        | object    | Entities involved (if mentioned)            |
| `Tweet`           | object    | Original tweet text describing the incident |
| `Source`          | object    | Source account or reporting entity          |

---

## Tools Used

- Python 3
- Jupyter Notebook
- Pandas

---

## Next Steps

- Convert `Date` and `Time` columns to datetime format
- Combine into a single `Datetime` column
- Begin cleaning and exploratory analysis

---

## License

Open-source project available under the [MIT License](LICENSE).
