# Stock Market Scraper with Golang

This is a simple stock market scraper implemented in Golang. It retrieves stock information from Yahoo Finance for a list of predefined tickers and saves the data to a CSV file.
## Usage
- Make sure you have Golang installed on your system.
- Clone this repository to your local machine.
- Navigate to the directory containing the main.go file.
- Run the following command to execute the scraper:

```bash
go run main.go

```

## Main Function

The main function of the program initiates the scraping process. It defines a list of ticker symbols for the stocks to be scraped. Then, it initializes a collector from Colly, sets up event handlers, and visits the Yahoo Finance page for each ticker symbol to extract the required information. Finally, it print out the data on the terminal and also saves the collected data to a CSV file named stocks.csv.