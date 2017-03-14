#About the API Offerings

FXCM currently offers 3 trading APIs for free:  Java API, FIX API and ForexConnect with each of them connecting directly to FXCM’s trading server.
 
FIX API requires an Active Trader account type, while other two APIs require at least a Standard account. Requirements for these account types depend on the entity. For more information please contact your account manager at FXCM.
It is also very important to note that historical prices are available only via ForexConnect and Java API

|API Name|Price Feed Frequency|Supporting Languages|Cost|Historical Price|Support CFD|Support MT4|
|:---:|---|---|---|---|---|---|
|**FIX**|Up to 300 per second*|Any|Free***|No|Yes|No|
|**ForexConnect API**|2-3 per second|C++, C#, Java, VB, VBA|Free**|Yes|Yes|Limited Yes|
|**Java Trading API**|2-3 per second|Java|Free**|Yes|Yes|Limited Yes|


>*Market dependent. If the market is volatile you may receive more prices per second.

>**Requires a Standard account.

>***Requires an Active Trader account.


You can find more information through the following links:

[**FXCM API Introduction**](https://www.fxcm.com/services/api-trading/)

[**FIX API WIKI**](https://apiwiki.fxcorporate.com/doku.php?id=fix_api/)

[**Choosing Proper SDK**](http://fxcodebase.com/wiki/index.php/Choosing_Proper_SDK)

[**Download ForexConnect SDK**](http://www.fxcodebase.com/wiki/index.php/Download)

[**Download JavaAPI SDK**](https://apiwiki.fxcorporate.com/api/java/trading_sdk.zip)

[**Download FIX Specification and Dictionary**](https://www.fxcm.com/forms/eula/)

#API IDEs
there are many IDEs available for each OS and programing language, here is short list of popular IDE for each OS.

##Forex Connect API

[**Windows 32bit and 64bit – Visual Studio 2005 and up**](https://www.visualstudio.com/en-us/downloads/download-visual-studio-vs.aspx)

[**Linux 32bit and 64bit – Eclipse**](https://eclipse.org/)

[**iOS – Xcode**]  (https://developer.apple.com/xcode/ide/)

[**Android - Android Studio**]  (https://developer.android.com/studio/intro/index.html)

[**ForexCOnnect with Python**] (https://github.com/4ever911/python-forexconnect)

[**ForexCOnnect with Matlab**] (https://github.com/FXCMAPI/FXCM-MATLAB)

All libraries and Jar files included with the API install program

##Java Trading API

[**Windows, Linux, Mac  - Netbeans**] (https://netbeans.org/)

API Jar files - fxcm-api.jar, fxmsg.jar

##FIX protocol

[**C++ - Windows, Linux, Mac - QuickFix**] (http://www.quickfixengine.org/)

[**C# - Windows – QuickFix/N**] (http://quickfixn.org/)

[**Java – any OS with Java VM – QuickFix/J**] (http://www.quickfixj.org/)

Each install package includes all libraries, DLLs, and Jar files

For any questions please contact api@fxcm.com

##Lua
Lua is a scripting language FXCM chose to code indicators and strategies for the Trading Station II platform via its charting package Marketscope. 
FXCM decided on Lua because it is a lightweight, extremely fast, simple and powerful scripting language. 
Lua has been proven as a robust language with uses in several different applications ranging from industrial to gaming

Lua is an extension programming language designed to support procedural programming with data description facilities. 
It offers good support for object-oriented programming, functional programming, and data-driven programming. 
Lua is implemented as a library, written in clean C (that is, in the common subset of ANSI C and C++).

Being an extension language, Lua has no notion of a "main" program: 
it only works embedded in a host client, called the embedding program or simply the host. 
This host program can invoke functions to execute a piece of Lua code, can write and read Lua variables, and can register C functions to be called by Lua code. 
Through the use of C functions, Lua can be augmented to cope with a wide range of different domains, thus creating customized programming languages sharing a syntactical framework. 
The Lua distribution includes a sample host program called lua, which uses the Lua library to offer a complete, stand-alone Lua interpreter.

Lua allows programmers to implement namespaces, classes and other related features using its single table implementations. 
It also allows users to read and write files or parse JSON messages fetched from the web (HTTP requests). 
Lua can even read DLL files (Microsoft), so code can be more encrypted and safe.

The IDE we use for LUA at FXCM is [**Indicore SDK**] (http://fxcodebase.com/wiki/index.php/What_Is_Indicore_SDK/)
This SDK is used to create/debug/test and compile indicators or strategies to be used in Trading Station’s Marketscope charting package.

##MT4 databases do not support the following functionality: 

•	Contingency (OCO, ELS, OTO, OTOCO)

•	NetQTY orders

•	Pegged orders

•	Trailing orders (ST, STE, LT, LTE)


