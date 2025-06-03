# ai-review-use
ai评审组件引入教程
1. 在自己的仓库里添加下述密钥
![image](https://github.com/user-attachments/assets/888379ff-c34e-4854-b6b6-feba5bfc6525)

2. 进入doc目录找到remote.yml,将其 内容 配置到github的流水线中，配置入口在下方图片中可找到
![image](https://github.com/user-attachments/assets/f4233f94-3baf-4f91-af21-b531932fdee3)

3. 接下来可以进行代码提交，通过微信接收消息通知，并跳转到记录日志的仓库里
   ![image](https://github.com/user-attachments/assets/7c8d4da6-9b0a-4555-ae2a-fc7a4a8ea315)
![image](https://github.com/user-attachments/assets/b02c8e0d-8e61-48ce-8a6e-49bc3467dd4a)



注意：
1. 微信的模板内容如下
项目名称：{{repo_name.DATA}}
分支名称：{{branch_name.DATA}}
提交作者：{{commit_author.DATA}}
提交信息：{{commit_message.DATA}}
【AI代码评审已完成】 请查看评审结果，及时处理相关问题。 
