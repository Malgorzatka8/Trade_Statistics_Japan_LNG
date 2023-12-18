# Trade_Statistics_Japan_LNG

Code downloads Japan's monthly LNG import data (QUANTITY and VALUE). Converts to USD usign Bank of Canada valet API. Brent prices added for reference. 

HS code for LNG: 271111

Source: https://www.customs.go.jp/toukei/srch/indexe.htm?M=03&P=1,2,,,,,,,,1,0,2023,0,10,0,2,271111,,,,,,,,,,1,,,,,,,,,,,,,,,,,,,,,,200

Dashboard available at:  https://public.tableau.com/app/profile/gosia.skwara/viz/JapaneseLNGImports-pricesvolumevalue/Prices?publish=yes

Column names: Index(['CUSTOMS', 'QUANTITY2', 'VALUE', 'Date', 'FXMJPY/CAD', 'FXMUSD/CAD',
       'Europe Brent Spot Price FOB (Dollars per Barrel)', 'Brent USD$/MMBtu',
       'VALUE_CAD', 'VALUE_USD', 'QUANTITY_MMBtu', 'USD$ per MMBtu',
       'QUANTITY_Bcf/d'],
      dtype='object')
