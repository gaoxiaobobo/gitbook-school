### 两种类型
区级阅卷 
> 教师从人才库中选

区级排考
> 由区级管理员操作，可以在全部学校中选考生，安排考场

### 启封试卷
> 只有启封后，才能在详情页下载试卷

1. 失效时间到，自动触发
2. 点此按钮，手动触发

### 接口规则
```
列表 /examPlan/list     get
新增 /examPlan          post
详情 /examPlan/{id}     get
修改 /examPlan          put
删除 /examPlan/{id}     delete
```