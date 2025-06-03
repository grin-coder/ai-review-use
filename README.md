# ai-review-use
ai评审组件引入教程
1. 在自己的仓库里添加下述密钥
<img src="https://github.com/user-attachments/assets/888379ff-c34e-4854-b6b6-feba5bfc6525" width="500">

2. 进入doc目录找到remote.yml,将其 内容 配置到github的流水线中，配置入口在下方图片中可找到
<img src="https://github.com/user-attachments/assets/f4233f94-3baf-4f91-af21-b531932fdee3" width="500">

3. 接下来可以进行代码提交，通过微信接收消息通知，并跳转到记录日志的仓库里
<img src="https://github.com/user-attachments/assets/a4872cca-8a5d-4782-8f55-4e2f1776858b" width="400">
<br>
<img src="https://github.com/user-attachments/assets/b02c8e0d-8e61-48ce-8a6e-49bc3467dd4a" width="500">



注意：
1. 微信的模板内容如下<br>
项目名称：{{repo_name.DATA}}<br>
分支名称：{{branch_name.DATA}}<br>
提交作者：{{commit_author.DATA}}<br>
提交信息：{{commit_message.DATA}}<br>
【AI代码评审已完成】 请查看评审结果，及时处理相关问题。 
