# Currency Converter

A simple and elegant web-based currency converter application that allows users to convert between different world currencies with real-time exchange rates.

## Features

- 💱 **Real-time Exchange Rates**: Fetches live exchange rates from the Fawaz Ahmed Currency API
- 🌍 **Multiple Currencies**: Supports conversion between 160+ world currencies
- 🏳️ **Country Flags**: Visual representation with country flags for each currency
- 📱 **Responsive Design**: Clean and user-friendly interface that works on all devices
- ⚡ **Instant Conversion**: Quick and accurate currency conversion
- 🎨 **Modern UI**: Beautiful gradient design with smooth user experience

## Technologies Used

- **HTML5**: Structure and layout
- **CSS3**: Styling and responsive design
- **JavaScript (ES6+)**: Logic and API integration
- **Font Awesome**: Icons
- **Fawaz Ahmed Currency API**: Real-time exchange rate data
- **FlagsAPI**: Country flag images

## Project Structure

```
currency-converter/
├── index.html      # Main HTML structure
├── stylee.css      # Stylesheet for the application
├── codes.js        # Currency codes and country mappings
└── mains.js        # Main application logic
```

## Getting Started

### Prerequisites

No special prerequisites needed! Just a modern web browser.

### Installation

1. Clone or download this repository
2. Navigate to the `currency-converter` directory
3. Open `index.html` in your web browser

That's it! The application will work directly without any build process or package installation.

### Usage

1. Enter the amount you want to convert in the input field
2. Select the source currency (From) from the dropdown
3. Select the target currency (To) from the dropdown
4. Click "Get Exchange Rate" button to see the converted amount
5. The exchange rate is automatically updated when you change currencies

## API Details

This project uses the [Fawaz Ahmed Currency API](https://github.com/fawazahmed0/currency-api) to fetch real-time exchange rates:

- **API Endpoint**: `https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1`
- **API Type**: Free, no API key required
- **Update Frequency**: Daily updates

## Supported Currencies

The application supports 160+ currencies including:
- USD (US Dollar)
- EUR (Euro)
- GBP (British Pound)
- INR (Indian Rupee)
- JPY (Japanese Yen)
- CNY (Chinese Yuan)
- AUD (Australian Dollar)
- CAD (Canadian Dollar)
- And many more...

See `codes.js` for the complete list of supported currencies.

## Features Breakdown

### `index.html`
- Main HTML structure with form elements
- Currency selection dropdowns
- Amount input field
- Exchange rate display area

### `stylee.css`
- Responsive layout design
- Modern color scheme
- Smooth transitions and styling

### `codes.js`
- Maps currency codes to country codes
- Used for displaying appropriate country flags

### `mains.js`
- Currency dropdown population
- Exchange rate fetching logic
- Flag update functionality
- Amount conversion calculations
- Event handlers for user interactions

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Opera (latest)

## Contributing

Contributions are welcome! If you'd like to improve this project:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source and available under the MIT License.

## Acknowledgments

- [Fawaz Ahmed](https://github.com/fawazahmed0) for providing the free currency API
- [Font Awesome](https://fontawesome.com/) for icons
- [FlagsAPI](https://flagsapi.com/) for country flag images

## Future Enhancements

Potential improvements for future versions:
- Currency conversion history
- Favorite currency pairs
- Graph visualization of exchange rate trends
- Dark mode support
- Offline caching of exchange rates
- Multiple currency comparison

---

**Made with 💜 using vanilla JavaScript**

