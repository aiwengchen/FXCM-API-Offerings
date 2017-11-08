## Rest API (still on testing)
Our REST API is a web-based API using a Websocket connection and was developed with algorithmic trading in mind. 

Developers and investors can create custom trading applications, integrate into our platform in a stateless manner and manage sessions with ease. 

With the use of the socket.io library, the API has streaming capability and will push data notifications in a JSON format. Your application will have access to our real-time streaming market data, subscribe in real time access to trading tables and place live trades.

To begin using our API, you will need the following:

1.	An FXCM account. You can apply for a demo account <a href="https://www.fxcm.com/">here</a> 
2.	A persistent access token. You can generate one from the <a href="https://tradingstation.fxcm.com/">Trading Station web</a>. Click on User Account > Token Management on the upper right hand of the website.
3.	Download Rest API word documents at <a href="https://apiwiki.fxcorporate.com/api/RestAPI/Socket%20REST%20API%20Specs.docx">here</a>
4. Documents in Swagger format at <a href="https://fxcmapi.github.io/rest-api-docs/#"> here</a> 
5. Start coding.  You will need to reference the <a href="https://socket.io/docs/client-api/">socket.io library</a> in your code. 
   a.	Using Javascript, click <a href="https://www.npmjs.com/package/socket.io">here</a>
   b.	 Using Python, click <a href="https://pypi.python.org/pypi/socketIO-client">here</a>
6. Sample code for Python at <a href="https://apiwiki.fxcorporate.com/api/RestAPI/PermanentTokenPost.py">here</a> 

## Other Trading APIs
Except RestAPI, FXCM offers 3 other trading APIs for free:  Java API, FIX API and ForexConnect with each of them connecting directly to FXCM’s trading server. Rest API is still in demo, will update you when it release to prod.
 
FIX API requires an Active Trader account type (An FXCM account with a $5,000 minimum balance required), while other two APIs require at least a Standard account. Requirements for these account types depend on the entity. For more information please contact your account manager at FXCM.
It is also very important to note that historical prices are available only via ForexConnect and Java API

|API Name|Price Feed Frequency|Supporting Languages|Cost|Historical Price|Support CFD|Support MT4|
|:---:|---|---|---|---|---|---|
|**FIX**|Up to 300 per second*|Any|Free***|No|Yes|No|
|**ForexConnect API**|2-3 per second|C++, C#, Java, VB, VBA|Free**|Yes|Yes|Limited Yes|
|**Java Trading API**|2-3 per second|Java|Free**|Yes|Yes|Limited Yes|


>*Market dependent. If the market is volatile you may receive more prices per second.

>**Requires a Standard account.

>***An FXCM account with a $5,000 minimum balance required.

### FIX API: detail at <a href="">here</a>
### Java API: detail at <a href="">here</a>
### ForexConnect API: detail at <a href="">here</a>

## Real Case Study:

### Rest API:
1. Learn how to run BT backtest on FXCM historical data via RestAPI at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/RestAPI/BT strategy on FXCM data.zip">here</a>. 
What is <a href="http://pmorissette.github.io/bt/">bt?</a> 
2. Learn how to run QSTrader on FXCM data via RestAPI at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/RestAPI/QSTrader on FXCM data.zip">here</a>. 
what is <a href="https://www.quantstart.com/qstrader">QSTrader?</a>

### Java API:
1. How to build Rsi signal and back testing using FXCM Java API. <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/FXCM_Java_API_Tutorial_RsiSignal_Strategy.zip" target="_blank"> click here</a>
2. Learn how to build and backtest CCI Oscillator strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/CCIOscillatorStrategy-2.zip">here</a>.
 
### ForexConnect API:
1. Learn how to build and backtest Rsi signals using ForexConnect API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/ForexConnectAPI/RsiSignals_via_ForexConnectAPI.zip">here</a>.
