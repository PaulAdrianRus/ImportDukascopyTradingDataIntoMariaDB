# ImportDukascopyTradingDataIntoMariaDB
Import Dukascopy Trading Data Into Maria DB

The settings for importing the .csv files from the Dukascopy website (https://www.dukascopy.com/plugins/fxMarketWatch/?historical_data) are:
Offer side: BID
Filter flats: Disable + Millions
Day Start Time: UTC + GMT

There are certain symbols which don't start at the default starting date (01/06/2019):
XPD.CMD/USD = 04/07/2021
XPT.CMD/USD = 01/11/2021
ADA/USD = 25/09/2021
AVE/USD = 15/09/2021
BAT/USD = 05/08/2019
BCH/USD = 10/06/2021
CMP/USD = 25/09/2021
DSH/USD = 04/08/2019
ENJ/USD = 25/09/2021
EOS/USD = 04/08/2019
LNK/USD = 25/09/2021
MAT/USD = 25/09/2021
MKR/USD = 25/09/2021
TRX/USD = 04/08/2019
UNI/USD = 01/10/2021
XLM/USD = 25/05/2021
XMR/USD = 25/11/2019
YFI/USD = 25/09/2021
