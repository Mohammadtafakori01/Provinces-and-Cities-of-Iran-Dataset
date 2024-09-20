# Provinces and Cities of Iran Dataset

This dataset contains information about the provinces and cities of Iran, including their names, geographical coordinates (latitude and longitude), and relational IDs for linking cities to their respective provinces.

## Dataset Structure

The dataset is structured in JSON format and includes the following fields:

- **province_id**: Unique identifier for each province.
- **province_name**: Name of the province in Persian.
- **cities**: An array of city objects, each containing:
  - **city_id**: Unique identifier for the city.
  - **city_name**: Name of the city in Persian.
  - **city_name_en**: Name of the city in English.
  - **latitude**: Geographical latitude of the city.
  - **longitude**: Geographical longitude of the city.

## Sample JSON Format

```json
[
  {
    "province_id": 1,
    "province_name": "تهران",
    "cities": [
      {
        "city_id": 1,
        "city_name": "تهران",
        "city_name_en": "Tehran",
        "latitude": 35.6892,
        "longitude": 51.3890
      },
      {
        "city_id": 2,
        "city_name": "شهرری",
        "city_name_en": "Shahr-e Rey",
        "latitude": 35.5723,
        "longitude": 51.3940
      }
    ]
  },
  {
    "province_id": 2,
    "province_name": "فارس",
    "cities": [
      {
        "city_id": 3,
        "city_name": "شیراز",
        "city_name_en": "Shiraz",
        "latitude": 29.5918,
        "longitude": 52.5836
      }
    ]
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
