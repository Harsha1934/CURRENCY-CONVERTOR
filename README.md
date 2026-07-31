# Currency Converter 💱

A simple Currency Converter web application built using HTML, CSS, and JavaScript.

This project allows users to enter an amount, select the currency they want to convert from and to, and get the current exchange rate.

## Features

- Enter the amount to convert
- Select the source currency
- Select the target currency
- Displays the country flag for the selected currency
- Fetches exchange rates using an API
- Calculates the converted amount
- Simple and user-friendly interface
- Responsive design

## Technologies Used

- HTML
- CSS
- JavaScript
- Currency Exchange Rate API
- Flags API

## Project Files

### `codes.js`

Contains the country and currency codes used in the project.

It connects currency codes such as:

- USD → US
- INR → IN
- EUR → EU
- AUD → AU

with their respective country codes so that the correct flag can be displayed.

### `logic.js`

Contains the main JavaScript logic of the currency converter.

It handles:

- Reading the amount entered by the user
- Selecting currencies
- Fetching exchange-rate data from the API
- Calculating the converted amount
- Updating the exchange-rate result
- Updating the currency flags

### `interface.js`

Handles the interaction between the JavaScript code and the webpage.

It is responsible for selecting HTML elements and updating the user interface when the user changes currencies or clicks the conversion button.

### `styles.js`

Contains the styling used for the Currency Converter interface.

It controls:

- Page background
- Converter container
- Input fields
- Currency dropdowns
- Buttons
- Flags
- Text alignment
- Spacing and layout

> If this file contains CSS code, it is recommended to rename it to `styles.css`.

## How It Works

1. Enter the amount you want to convert.
2. Select the currency you are converting from.
3. Select the currency you want to convert to.
4. The corresponding country flags are updated.
5. Click **Get Exchange Rate**.
6. The application gets the exchange rate from the API.
7. The converted amount is displayed on the screen.

## Example

If the user enters:

```text
100 USD
