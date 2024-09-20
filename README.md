# Provinces and Cities of Iran Dataset

This dataset contains information about the provinces and cities of Iran, including their names, geographical coordinates (lat and lon), and relational IDs for linking cities to their respective provinces.

## Dataset Structure

The dataset is structured in JSON format and includes the following fields:

  - **id**: Unique identifier for the city.
  - **name**: Name of the city in Persian.
  - **en_name**: Name of the city in English.
  - **lat**: Geographical lat of the city.
  - **lon**: Geographical lon of the city.
  - **province_id**: Unique identifier for each province.

## Sample JSON Format

```json
[
      {
        "id": 3,
        "name": "شیراز",
        "province_id": 2,
        "name_en": "Shiraz",
        "lat": 29.5918,
        "lon": 52.5836
      }
]
```

## Usage

You can use this dataset for various applications, such as:

- Geographic visualizations
- Location-based services
- Statistical analysis related to provinces and cities in Iran

## Contribution

If you find any issues or would like to contribute to the dataset, please submit a pull request or open an issue.

## License

This dataset is provided under the [MIT License](LICENSE).
