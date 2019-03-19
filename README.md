# Port_Optimizer

Using US import ocean freight data with time series forecasting for more accurate daily container volume

If you look around you, chances are most of the items you see were "shipped". They were moved on a boat, plane or truck to get where where you are now. The global logistics industry is antiquated and ripe for data driven disruption. The goal of this project is to analyze US import data to achieve more accurate forecasting through time series modeling. 

The data is 4+ years 2014-2018 of import records for all US ports. This project will focus on the busiest of those ports, the Port of Los Angeles. Data included over 20 million rows of data with each row representing a shipment on a cargo vessel with fields like port of origin, vessel name, estimated arrival day, actual arrival day, text description of the cargo, the harmonized tax code and the weight of the shipment.

Initially Facebook Prophet was used for forecast modeling.

The average container dwell time in Los Angeles-Long Beach in January was 4.3 days, a full day longer than in December, according to the Pacific Merchant Shipping Association, and turn times in January averaged 98 minutes, compared with less than 80 minutes for most of 2018, according to the Harbor Trucking Association (HTA). [joc.com]


References:

__https://www.joc.com/port-news/us-ports/port-long-beach/long-beach-port-optimizer-decision-raises-data-questions_20190313.html__
