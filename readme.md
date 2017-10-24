FXCM currently offers 3 trading APIs for free:  Java API, FIX API and ForexConnect with each of them connecting directly to FXCM’s trading server.
 
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

Real Case Study:
Java API:
1. How to build Rsi signal and back testing using FXCM Java API. 
https://apiwiki.fxcorporate.com/api/StrategyRealCaseStudy/JavaAPI/FXCM_Java_API_Tutorial_RsiSignal_Strategy.zip 
