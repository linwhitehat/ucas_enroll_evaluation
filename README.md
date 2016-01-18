# ucas_enroll_evaluation
中国科学院大学自动评教脚本
===
需要Python2.7环境，依赖Beautifulsoup和Requests，通过如下命令可安装

> pip install beautifulsoup4

> pip install requests

请在config填入你的用户名和密码

enroll设置为true表示选课
evaluate设置为true表示评教

请在courseid文件中设置你需要选的课程
> - 课程编号:on #表示该课程选择为学位课
> - 课程编号 #表示普通选课
> - 例如：
> - 091M5023H:on
> - 091M4002H
> - 表示091M5023H作为学位课选课，091M4002H只进行普通选课