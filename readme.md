## Rest API (still on testing)
Our REST API is a web-based API using a Websocket connection and was developed with algorithmic trading in mind. 

Developers and investors can create custom trading applications, integrate into our platform in a stateless manner and manage sessions with ease. 

We utilize the new OAuth 2.0 specification for authentication via token. This allows for a more secure authorization to access your application and can easily be integrated with web applications, mobile devices, and desktop platforms

With the use of the socket.io library, the API has streaming capability and will push data notifications in a JSON format. Your application will have access to our real-time streaming market data, subscribe in real time access to trading tables and place live trades.

To begin using our API, you will need the following:

1.	A FXCM account. You can apply for a demo account <a href="https://www.fxcm.com/">here</a> 
2.	A persistent access token. You can generate one from the <a href="https://tradingstation.fxcm.com/">Trading Station web</a>. Click on User Account > Token Management on the upper right hand of the website.
3.	Download Rest API word documents at <a href="https://apiwiki.fxcorporate.com/api/RestAPI/Socket%20REST%20API%20Specs.docx">here</a>
4. Documents in Swagger format at <a href="https://fxcmapi.github.io/rest-api-docs/#">here</a> 
5. Start coding.  You will need to reference the <a href="https://socket.io/docs/client-api/">socket.io library</a> in your code. 
   a.	Using Javascript, click <a href="https://www.npmjs.com/package/socket.io">here</a>
   b.	 Using Python, click <a href="https://pypi.python.org/pypi/socketIO-client">here</a>
6. Sample code for Python at <a href="https://apiwiki.fxcorporate.com/api/RestAPI/PermanentTokenPost.py">here</a> 
7. Sample code for Java Script at <a href="https://apiwiki.fxcorporate.com/api/RestAPI/client4.js">here</a>

## Other Trading APIs
Except RestAPI, FXCM offers 3 other trading APIs for free:  Java API, FIX API and ForexConnect with each of them connecting directly to FXCM’s trading server. Rest API is still in demo, will update you when it release to prod.
 
FIX API requires an Active Trader account type (An FXCM account with a $5,000 minimum balance required), while other two APIs require at least a Standard account. Requirements for these account types depend on the entity. For more information please contact your account manager at FXCM.
It is also very important to note that historical prices are available only via ForexConnect, Java API and Rest API.

|API Name|Price Feed Frequency|Supporting Languages|Cost|Historical Price|Support CFD|Support MT4|
|:---:|---|---|---|---|---|---|
|**Rest API**|Vary*|Any|Free**|Yes|Yes|Limited Yes|
|**FIX**|Up to 300 per second*|Any|Free***|No|Yes|No|
|**ForexConnect API**|2-3 per second|C++, C#, Java, VB, VBA|Free**|Yes|Yes|Limited Yes|
|**Java Trading API**|2-3 per second|Java|Free**|Yes|Yes|Limited Yes|


>*Market dependent. If the market is volatile you may receive more prices per second.

>**Requires a Standard account.

>***An FXCM account with a $5,000 minimum balance required.

### FIX API: detail at <a href="https://github.com/FXCMAPI/FXCM-API-Offerings/tree/master/FXCM-FIX">here</a>
### Java API: detail at <a href="https://github.com/FXCMAPI/FXCM-API-Offerings/tree/master/FXCM-Java">here</a>
### ForexConnect API: detail at <a href="https://github.com/FXCMAPI/FXCM-API-Offerings/tree/master/FXCM-ForexConnect">here</a>

## Real Case Study:

### Rest API:
1. Learn how to run BT backtest on FXCM historical data via RestAPI at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/RestAPI/BT strategy on FXCM data.zip">here</a>. 
What is <a href="http://pmorissette.github.io/bt/">bt?</a> 
2. Learn how to run QSTrader on FXCM data via RestAPI at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/RestAPI/QSTrader on FXCM data.zip">here</a>. 
what is <a href="https://www.quantstart.com/qstrader">QSTrader?</a>
3. Lean how to build/back test 3 strategies "MovingAverageCrossStrategy","BollingerBandStrategy","DonchianChannelStrategy" via FXCM Rest API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/RestAPI/ThreeStrategies.zip">here</a>.
4. Two more strategies "RangeStrategy", "BreakOutStrategy" at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/RestAPI/2StrategiesViaRestAPI.zip">here</a>.
5. Building/back testing RSI strategy via RestAPI at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/RestAPI/RsiStrategy_ResAPI.zip">here</a>.
6. One video demonstrate how to backtest strategies in Visual Studio via FXCM data On QuantConnect LEAN platform at <a href="https://www.youtube.com/watch?v=m6llfznP4d4">here</a>

### Java API:
1. How to build Rsi signal and back testing using FXCM Java API. <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/FXCM_Java_API_Tutorial_RsiSignal_Strategy.zip" target="_blank"> click here</a>
2. Learn how to build and backtest CCI Oscillator strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/CCIOscillatorStrategy-2.zip">here</a>.
3. Lean how to build and back test Breakout strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/BreakOutStrategy_JavaAPI.zip">here</a>. 
4. Lean how to build and back test Range Stochastic Strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/RangeStochasticStrategy.zip">here</a>. 
5. Lean how to build and back test Mean Reversion Strategy using Java API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/MeanReversionStrategy.zip">here</a>. 

### ForexConnect API:
1. Learn how to build and backtest Rsi signals using ForexConnect API at <a href="https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/ForexConnectAPI/RsiSignals_via_ForexConnectAPI.zip">here</a>.
