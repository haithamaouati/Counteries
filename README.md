# Counteries

A structured JSON dataset containing all 193 member states officially recognized by the United Nations, categorized by continent.

## Data Schema

Each entry within the dataset includes the following attributes:

| Field | Type | Description |
| :--- | :--- | :--- |
| `name` | String | English common name |
| `name_ar` | String | Arabic official name |
| `code` | String | ISO 3166-1 alpha-2 country code |
| `capital` | String | Capital city |
| `dial_code` | String | International direct dialing prefix |
| `emoji` | String | Flag emoji representation |
| `currency` | String | ISO 4217 currency code |

## Example Structure

```json
{
  "Americas": [
    {
      "name": "United States",
      "name_ar": "الولايات المتحدة الأمريكية",
      "code": "US",
      "capital": "Washington, D.C.",
      "dial_code": "+1",
      "emoji": "🇺🇸",
      "currency": "USD"
    }
  ]
}
