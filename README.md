# ZentradesTask-2

## Overview

ZentradesTask-2 is an application designed to parse JSON data from an API and display the information in a user-friendly format. The application allows you to download a JSON file from a provided link, and it contains 1000 records of products, each with the following attributes:

- Subcategory
- Title
- Price
- Popularity

## Usage

Follow these steps to interact with the application:

1. **Download JSON File:**
   - Download the JSON file from the following link: [Download Assignment JSON](https://s3.amazonaws.com/open-to-cors/assignment.json).

2. **Choose File:**
   - Open the application and choose the downloaded JSON or a CSV file.

3. **Specify Format:**
   - Specify the format of the chosen file.
   - Choose the character encoding, delimiter, and indicate whether the file has a header.

4. **Select Displayed Fields:**
   - Choose the fields you want to display from the available options.
   - Use the buttons to add or remove fields.

5. **Display Data:**
   - Display the selected fields in descending order based on popularity.

## How to Run

Simply open the HTML file in a web browser to use the application.

## Example

Here's a brief example of the JSON structure:

```json
{
  "count": 1000,
  "products": {
    "6834": {
      "subcategory": "mobile",
      "title": "Micromax Canvas Spark",
      "price": "4999",
      "popularity": "51936"
    },
    "5530": {
      "subcategory": "mobile",
      "title": "Samsung Galaxy Grand Max",
      "price": "12950",
      "popularity": "48876"
    },
    // ... (more products)
  }
}
