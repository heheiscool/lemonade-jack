lemonade-jack
=============

Lemonade Jack is a lemonade stand type game, the game description can be found here http://en.wikipedia.org/wiki/Lemonade_Stand. The code are written in C++ using cocos2d-x framework. I have tested it, the code should compile for iOS, Android, Win32. Other platforms are untested.

I written this game to learn C++ and game development. You are welcome to use or change the code or graphics in this repo. 


In variation to the original lemonade stand game, Lemonade Jack features the following:

* Up to date graphics
* More business variable
* 6 customer groups (Male and Female of Young, Adult, Pensioner) each has a unique taste preference
* 6 unique places each with difference customer group distributions to set your lemonade stand
* Each customer group in each world has a reputation rating; reputation is earned by each successful sale. Higher reputation will result higher chance of customer buying and higher quantity.

Game Play:
=========
Lemonade Jack is business simulation game that can be played endlessly. However the critical element of the game is to sell lemonade, use profit to buy more Lemon, Sugar and Cups so that you can make more Lemonades to sell. 

Game Center Achievements:
=========================
Top Earner – daily profits are added up, compare your total earnings to other players in Game Center.
Top Seller – Compare your total lemonade sells with other players in Game Center.



基于Cocos2d-x v3.1 采用C++语言开发；开发中我用到了Cocos Studio, plist配置加载，保存，GameCenter, In-App Purchase, 动画，声音等。, y5 \8 @8 w, }4 E; H
本游戏源于一款Lemonade Stand的电脑游戏，游戏中玩家扮演一个做柠檬汁起家的企业家。
该游戏内容包括：
管理库存（柠檬，糖，杯子等），防止您的柠檬汁脱销。5 }% L7 E; h2 a* ^$ S) U
柠檬汁配方，不同的人群有不同的偏好，根据柠檬或糖的比例不同而配合不同的人群。0 w1 X% l: {; L1 _$ u* j3 F. o
游戏中有6个世界场景，每个世界都有不同的人群分布，例如邻里有更多的成年男性和女性，学校男女学生居多，等等。不同的世界有不同的购买力，同时他们的入场费也不同。3 h' [9 ^2 g, `" e9 z8 ?7 w
游戏中有6个人群，他们由3个年龄组老中少，2个性别男性和女性组成。每个组都有不同的偏好。
游戏中还配有评价系统，评价系统是人群和世界独立的。评价会在每次销售成功时增长，评价越高，该人群的购买欲越强。* L% r& g" {" l5 E. d
开发环境
Mac + xcode
Cocos2d-x v3.1
