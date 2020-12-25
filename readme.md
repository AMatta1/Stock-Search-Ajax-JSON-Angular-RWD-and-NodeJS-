
Stock Search Website : Angular_Bootstarp_NodeJS
* Reference Solution: http://ankita-frontend-new.s3-website-us-east-1.amazonaws.com/

Technologies Used
Ajax, JSON, Angular, RWD and NodeJS

APIs Used
Google News API
Tiingo APIs

Explanation :

It involves creating a website that allows users to search for any stock using its name/ short name and get its details like current/high/low/openmid/ask/bid price depending on the real-time status of the market, i.e., open or closed. It uses Tiingo API and NewsAPI to fetch the data.

It also displays top 20 news for the selected stock along with the daily chart that updates in real-time every 4 minutes during open market status. Further, I have used Highcharts to display a historical chart that shows stock prices and data from the past 2 years from the current date.

All the fetched data is auto-refreshed every 15 seconds during 'open' market to display fresh data. Autocomplete API is used to suggest 'search' options on the homepage.

User can buy/sell stocks from the 'details' page. The 'Watchlist' tab shows cards for the bookmarked/watch-listed stocks from the 'details' page. Finally the 'Portfolio' tab allows to view and/or further sell/buy the already bought stocks.

Backend is written in NodeJS (Express framework) and front-end using Angular. Bootstrap is used for various UI components for Responsive Website Design hence, the website adjusts as per the screen size (Smartphone/ Tablet/ iPad/ Desktop etc. )
