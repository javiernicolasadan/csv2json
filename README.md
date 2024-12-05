# **CSV to JSON Converter**

A lightweight and efficient script to convert CSV files into JSON format. This project is designed to make it easy to handle CSV data and transform it into JSON for use in web applications, APIs, or data processing workflows.

## Dependencies needed:
```bash
node
npm 
```

## Usage
1. Place your CSV file in the `data` folder (e.g., `data/Contact_Data.csv`).
2. Run the script:
   ```bash
   node index.js
   ```
3. The output JSON file will be in your terminal.

## Project Structure
```bash
csv2json/
├── data/
│   ├── Contact_Data.csv  # Example input file
├── index.js              # Main script
├── package.json          # Project dependencies
└── README.md             # Project documentation
```

## Examples
### Input (CSV: `Contact_Data.csv`):
```csv
Email,FirstName,LastName,MailingCity,MailingCountry
john.doe@example.com,John,Doe,New York,USA
jane.doe@example.com,Jane,Doe,Los Angeles,USA
```

### Output (JSON):
```json
[
  {
    "Email": "john.doe@example.com",
    "FirstName": "John",
    "LastName": "Doe",
    "MailingCity": "New York",
    "MailingCountry": "USA"
  },
  {
    "Email": "jane.doe@example.com",
    "FirstName": "Jane",
    "LastName": "Doe",
    "MailingCity": "Los Angeles",
    "MailingCountry": "USA"
  }
]
```


## 
Exercise by [Javier Nicolas Adan](https://github.com/javiernicolasadan) following the video by [Julian Duque](https://www.youtube.com/watch?v=ewBsz-UaGfI&list=PLgIMQe2PKPSKsz4ag01cKOayd19nEg10u)

