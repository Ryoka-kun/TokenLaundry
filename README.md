# TokenLaundry
Automation System for Token Laundry with Authentic Routing

(Please See End-User License Agreement)

Usage of TokenLaundry implies explicit fees subject to roughly 20% However equate to 18 Direct Trade Floor Washes, Separating to Seperate NoKYC Trade Floor Transactions proxied by NoKYC Wallets.

OKX Wallet, Bitget, and Bitflex are necessary for use.

1) Register with OKX NoKYC Wallet, Bitget, and Bitflex.

2) Sign up for API Access and create api keys for each setup. Log or Remember all Secrets, Passcodes, and Access Keys for Usage.

3) Enter the following in your appropriate root folder for use:

  /#>$ apt-get install python3 pip 

  /#>$ pip install ccxt

  /#>$ pip install bitget requests hmac hashlib time urllib sys

4) Edit Service File to direct to appropriate location for python source of tradebot  and all equitable token aamounts to value of USDT shown beside it in tradebot.service.

// service amounts for trade on 5,000USDT equates to roughlly 277.50 for each transaction and shoould be calculated for exact amount of equatable coin in transaction listed in trade.service and adjusted simillar to the included values
// following dividend trade sizes of 5K in exponential multiples.

Token,Market Value (USDT),Allocated Amount After Fees (USD),Quantity Purchased
BTC,42000,277.50,0.0066
ETH,3100,277.50,0.0895
BNB,350,277.50,0.7929
ADA,2.1,277.50,132.1429
DOT,25,277.50,11.1000
LTC,150,277.50,1.8500
LINK,22,277.50,12.6136
XRP,0.9,277.50,308.3333
BCH,500,277.50,0.5550
XLM,0.28,277.50,991.0714
DOGE,0.2,277.50,1387.5000
VET,0.1,277.50,2775.0000
SOL,130,277.50,2.1346
THETA,6,277.50,46.2500
TRX,0.08,277.50,3468.7500
EOS,4,277.50,69.3750
MIOTA,1.3,277.50,213.4615
XMR,220,277.50,1.2614


5) Deposit Money to be LAundered and Fees for Transactions in OKX Start Wallet

6) Place tradebot.service in /etc/systemd/system and enter:

   
  /#>$ sudo systemctl daemon-reload
  
  /#>$ sudo systemctl enable tradebot.service

  /#>$ sudo systemctl start tradebot.service

  /#>$ sudo systemctl status tradebot.service

7) If Status is Green, All Application Services are in Serialized Buffer and Running Correctly.

# End User License Agreement

Use of the following code for demonstration or eductional purposes excluding law enforcement, privately funded schools, and federal licensed academys, is applicably limited to discretion under the eyes of appropriate  sanctions
upon users, parties intendinig download, git clone, or mirror, and all persons under subject of access to this repository.

All Illegal Operation of Code is Punishable among International Sanctions.

All Wallet Providers and Trade Floors Directly Exclude U.S. (American) Access and Membership.


