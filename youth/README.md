# 中青阅读获取cookie
https:\/\/\w+\.youth\.cn\/TaskCenter\/(sign|getSign) - script-request-header https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js
https?:\/\/ios\.baertt\.com\/v5\/article\/complete - script-request-body https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js
https:\/\/ios\.baertt\.com\/v5\/article\/red_packet - script-request-body https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js
https:\/\/ios\.baertt\.com\/v5\/user\/app_stay\.json - script-request-body https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js
# 中青看点浏览赚
https:\/\/ios\.baertt\.com\/v5\/task\/browse_(start|end)\.json - script-request-body https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth_gain.js
# 中青阅读获取body
https://ios.baertt.com/v5/article/complete.json - script-request-body https://raw.githubusercontent.com/songyangzz/QuantumultX/master/zqgetbody.js


# Task
0 0/20 2-12 * * * https://raw.githubusercontent.com/CenBoMin/QuantumultX/master/Scripts/Youth/Youth_AutoRead.js, tag=中青看点 阅读, img-url=https://raw.githubusercontent.com/Orz-3/task/master/youth.png, enabled=true

*/10 0 1-23 * * * https://raw.githubusercontent.com/CenBoMin/QuantumultX/master/Scripts/Youth/youth.js, tag=中青看点 签到+转盘, img-url=https://raw.githubusercontent.com/Orz-3/task/master/youth.png, enabled=true

20 5 10 * * * https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth_gain.js, tag=中青看点 浏览赚, img-url=https://raw.githubusercontent.com/Orz-3/task/master/youth.png, enabled=true

0 0/10 2-23 * * * https://raw.githubusercontent.com/Sunert/Scripts/master/Task/youth.js, tag=中青看点 增加阅读时间, img-url=https://raw.githubusercontent.com/Orz-3/task/master/youth.png, enabled=true

*/30 * 7-22 * * * https://raw.githubusercontent.com/jiuli12/Script/main/youthRead.js, tag=中青看点 多账号自动阅读, img-url=https://raw.githubusercontent.com/Orz-3/task/master/youth.png, enabled=false

*/30 0-22 * * * https://raw.githubusercontent.com/jiuli12/Script/main/youth.js, tag=中青看点 多账号签到+转盘, img-url=https://raw.githubusercontent.com/Orz-3/task/master/youth.png, enabled=false

