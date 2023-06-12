# Hebrew Date Converter

This is a simple HTML page that allows users to convert a Gregorian date to the Hebrew calendar using an API. The page includes a date picker for selecting the input date and a "Convert" button to trigger the conversion.

## Instructions

1. Open the HTML file (`index.html`) in a web browser.
2. Select a date using the date picker.
3. Click the "Convert" button to convert the selected date to the Hebrew calendar.
4. The converted date will be displayed below the button.

## Technologies Used

- HTML
- CSS
- JavaScript
- jQuery
- jQuery UI

## API

This project utilizes the Hebcal API for the Hebrew date conversion. The API is called asynchronously using jQuery's `getJSON` method. The response is a JSON object containing the converted Hebrew date, which is then displayed on the page.

## Examples

### Input:
Date: 08/06/1997

### Output:
Hebrew date: ג׳ בְּאָב תשנ״ז

### Input:
Date: 04/05/2023

### Output:
Hebrew date: י״ד בְּנִיסָן תשפ״ג

Feel free to explore and use this code as a starting point for your own Hebrew date conversion projects.

