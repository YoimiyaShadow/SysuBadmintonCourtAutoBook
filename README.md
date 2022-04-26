# SysuBadmintonCourtAutoBook

 学习自 https://github.com/xumj9/sysubadminton 

 用到的库：baidu-aip, cv2, selenium, pillow  

 主要修改：  
  1.仅适配Microsoft Edge  
  2.实现网页502 Bad Gateway后自动刷新   
  3.适配最新南校预订网页 2022.04.26  

 使用手册：      
1. 修改参数   

    netid = 'xxx'#NetID  
    password = 'xxxxx'#密码  
    bookdate = '2018-07-27'#预定日期（请严格按照格式填入     
    playtime = '17:01-18:00'#预定时间段（请严格按照格式填入     
 
2. 在config中填入自己的百度翻译api    
3. 默认目录为C:\sysubook\   
4. 如预订其他校区，请搜索“南校园”、“show.html?id=61”并自行替换字符和id
5. Edgedriver请见：https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
6. Python环境配置请自行百度

# 声明：如因该项目被体育部取消预订资格，本人概不负责
 

