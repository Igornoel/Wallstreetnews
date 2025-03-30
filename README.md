# Currency Converter

A simple, user-friendly web application that allows users to convert between different currencies using real-time exchange rates.


## Features

- Convert between multiple currencies with up-to-date exchange rates
- Clean, responsive user interface
- Swap currencies with a single click
- Displays current exchange rate information
- Real-time validation and error handling

## Technologies Used

- HTML5
- CSS3
- JavaScript (ES6+)
- [ExchangeRate-API](https://www.exchangerate-api.com/) for currency conversion data

## Demo

[View the live demo](#) ([The link to demo video](https://www.loom.com/share/7d912cbad83b45d6a63fc85d5a6b3b9c?sid=7dc79b97-2794-4b05-9d07-6ffc60de70a7))

## Getting Started

### Prerequisites

- A modern web browser
- Internet connection (for API access)
- ExchangeRate-API key (free tier available)

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/currency-converter.git
   ```

2. Navigate to the project directory:
   ```
   cd currency-converter
   ```

3. Open `index.html` in your favorite code editor.

4. Replace the API key with your own:
   ```javascript
   const API_KEY = 'YOUR_API_KEY_HERE';
   ```
   
   Get your free API key by signing up at [ExchangeRate-API](https://www.exchangerate-api.com/).

5. Open `index.html` in your web browser to use the application locally.

## Usage

1. Enter the amount you want to convert in the "Amount" field.
2. Select the currency you're converting from in the "From" dropdown.
3. Select the currency you're converting to in the "To" dropdown.
4. Click the "Convert" button to see the result.
5. Use the swap button (⇄) to quickly switch between the selected currencies.

## API Usage

This project uses the ExchangeRate-API v6. The free plan includes:
- 1,500 API requests per month
- 32 supported currency pairs
- Updates every 24 hours

## Customization

### Colors

You can customize the appearance by modifying the CSS variables in the `style` section of the HTML:

```css
button {
    background-color: #3498db; /* Primary button color */
}

button:hover {
    background-color: #2980b9; /* Button hover color */
}
```

### Adding More Features

Some ideas for extending the project:
- Add currency flags next to currency codes
- Implement a dark/light theme toggle
- Add historical conversion rates
- Create a conversion history feature

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under Igornoel

## Acknowledgments

- [ExchangeRate-API](https://www.exchangerate-api.com/) for providing the exchange rate data
- Icons and design inspiration from various open-source projects
