前期版本基于pyctp接口，后期改为vnpy接口，采用eventEngine，使用tkinter作为GUI的python交易平台

主要功能：

(1) 支持多账户，本地仓位管理，保证金计算，开仓平昨平今的逻辑

(2) 增加trade level以支持多腿下单，屏蔽开仓平仓逻辑，可以做跨合约套利

(3) 支持多品种，多策略同时运行并可手动更改交易参数

(4) 策略层增加tradepos level以便对trail profit, stop loss等增加支持

(5) 基于mySQL数据库，对实时数据tick,minute,daily进行保存

(6) 具有option pricng C++库

(7) 具有option模块和相应GUI(逐步扩展中)

(8) 具有分钟级回测CTA策略

(9) 支持仿真交易(历史数据paper trading)和实时模拟交易(实时数据paper trading)

下一步计划

(1) 期权套利和做市策略，volatility surface calibration/remarking

(2) 自动期权delta hedging

(3) 增加使用Mongodb

(4) 完善tick级回测


有兴趣合作联系

QQ: 1940877918

知乎：无所谓，自制pyktrader挖矿
