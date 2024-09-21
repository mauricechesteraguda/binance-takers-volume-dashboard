## Binance Takers Buy/Sell Volume Dashboard

A simple web application that visualizes the takers' buy and sell volume on Binance for a selected cryptocurrency pair. The app uses Binance API to fetch the data and displays the information in a dynamic, responsive chart. Users can select various timeframes, change the cryptocurrency symbol, and update the volume limits to analyze the market trends.
Features
  
  Real-time Data: Fetches and displays Binance's taker buy/sell volume data in real-time.
  Dynamic Timeframes: Allows users to select different timeframes (5m, 15m, 30m, 1h, 4h, 1D).
  Custom Symbol: Users can input any Binance trading pair symbol (e.g., BTCUSDC).
  Custom Limit: Users can set the limit of data points to display on the chart.
  Interactive Chart: Utilizes Chart.js to render an interactive bar chart, with buy/sell volumes displayed along with a dynamic horizontal line for volume analysis.
  Tailwind CSS Styling: Modern and responsive UI using Tailwind CSS.

## Demo

## Technologies Used

  Vue.js: For dynamic UI updates and handling user interactions.
  
  Tailwind CSS: For responsive and sleek UI styling.
  
  Chart.js: For data visualization.
  
  Axios: For making HTTP requests to the Binance API.
  
  Binance API: To fetch market data related to takers' buy/sell volumes.

## How to Use

Clone the repository:
  
  git clone https://github.com/your-username/binance-takers-volume-dashboard.git

Navigate to the project directory:

bash

  cd binance-takers-volume-dashboard

  Open index.html in your browser.

The app will load the default symbol BTCUSDC with a 5m timeframe and a data limit of 30 entries. You can modify these settings via the input fields and buttons.
## Features Overview

  Timeframes: You can switch between different timeframes: 5m, 15m, 30m, 1h, 4h, and 1D.
  Symbol Change: Change the trading pair symbol by entering a new one in the "Symbol" input field (e.g., ETHUSDT).
  Limit Adjustment: Change the number of data points displayed on the chart by adjusting the "Limit" input field.

## API Endpoints Used

The project fetches data from the following Binance API endpoints:


## Customization

  Chart Styles: The chart colors and styles can be easily customized in the updateChart method within the script.
  Button and Input Styles: The buttons and input boxes are styled using Tailwind CSS classes. You can modify these classes or add new ones for further customization.

## Known Issues

  Buttons are disabled for 5 seconds after each API call to prevent multiple requests in a short time span.
  The chart does not store historical data once refreshed. It only fetches the current data based on the selected timeframe and limit.

## Future Improvements

  Add more time intervals.
  Display additional data such as the price movement in the chart.
  Add historical data fetching to provide better analysis.
  Implement additional Binance API endpoints for richer data sets.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.
Contributions

Feel free to fork this repository, create a new branch, and submit a pull request to contribute to this project!

## Contact

For any questions or inquiries, please reach out to https://www.linkedin.com/in/maurice-chester-aguda-09b93981/.

## Support

If you find this project helpful and would like to support its ongoing development, consider buying me a coffee! Your support helps me keep working on this project and developing more features.

[![Buy Me a Coffee](https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png)](https://www.buymeacoffee.com/mauriceague)
