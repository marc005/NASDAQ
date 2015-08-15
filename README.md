# NASDAQ
google script and Nasdaq

In google spreadsheet I use the formula:

=IMPORTDATA("http://www.nasdaq.com/screening/companies-by-industry.aspx?exchange=NASDAQ&render=download")

I now want to save the column stock name and last sale in a panel like this:

                   stock1       stock2       stock3
          date1    last sale    last sale    last sale
          date2    last sale    last sale    last sale
          date3    last sale    last sale    last sale

How can I write a google script to accomplish this? 
The script should run once per day to collect the data!
