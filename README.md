# A5

A5图书管理系统之归还和自动提醒

1.登录后在首页时调用接口判断是否有借书天数大于25（离还书期限的天数在五天内）的记录，有就进行提示

2.还书时，获取借书记录并判断借书时间离今天是否大于30天，如果是则将状态设为4

3.在页面中增加option为4-超时还书的查询条件

4.在学生端借阅页面调用接口时，会传入当前学生借阅号进行筛选，只查出当前学生的借阅记录

