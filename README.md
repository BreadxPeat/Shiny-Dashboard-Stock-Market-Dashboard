# Shiny-Dashboard-Stock-Market-Dashboard

This Shiny app creates a dashboard that allows the user to select a stock symbol, the start and end dates, and the number of days for the moving average and RSI calculation. It generates a chart of the stock's price and technical indicators (moving averages, RSI, and MACD). The dashboard also includes a comparison tab that displays a pie chart and a bar plot comparing the chosen stocks.

# Prerequisites

This app requires the following libraries to be installed:

1. shiny
2. shinydashboard
3. quantmod
4. ggplot2

# Execution 
1. Install the required libraries.
2. Load the Shiny library by running library(shiny).
3. Run the app using the shinyApp() function.

# Application
1. Select a stock symbol from the dropdown menu.
2. Select the start and end dates for the stock data.
3. Use the slider to select the number of days for the moving average.
4. Use the dropdown menu to select the number of days for the RSI calculation.
5. The app will generate a chart of the stock's price and technical indicators.
6. Switch to the "Comparisons" tab to compare the chosen stocks.
7. Dashboard has Help tab in case you do not understand any term


![image](https://github.com/user-attachments/assets/49d030b9-858e-49e6-a63d-c9111d8a3e03)

![image](https://github.com/user-attachments/assets/a478d7e5-7de2-43ec-b0f7-885782255877)

![image](https://github.com/user-attachments/assets/e5178036-e399-457d-b5c1-78f974ea094f)

# Acknowledgements
This app was created using the shinydashboard package for Shiny by RStudio. It also uses the quantmod package for retrieving and manipulating financial data and the ggplot2 package for generating charts.

