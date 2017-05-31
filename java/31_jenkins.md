
Jenkins


目标： 2017-05-28

1. 从svn获取最新的代码
2. 生成war
3. 发布到tomcat上






keywords:
pipeline




Step 1: download http://mirrors.jenkins.io/war-stable/latest/jenkins.war
Step 2: run java -jar jenkins.war

	初始密码 2bccab74ab894e92954163c1abf4adde
	代码路径 /Users/qinlili/.jenkins/secrets/initialAdminPassword

	 前提已经有了jdk 1.8

Step 3: 打开localhost:8080

	Step 3.1 安装默认安装plugin





JenkinsFile是放在 Repository中的







如何安装jdk 1.8 ?


如何查看本机CPU的信息 ？

sysctl -n machdep.cpu.brand_string


如何截取当前画面？


Shift + Command + 3
Shift + Command + 4






Tutorial 6 : Basic Configurations

配置了多个node（暂时用不到）


Tutorial 7 : Getting started with JOBS


1. How to create a basic JOB in Jenkins
2. Basic job configuration
3. How to run the Job remotely
4. How to chain Job Execution



3) 设置token， 直接用浏览器激活
4） Build after other projects are built



Tutorial 8 : Jenkins integration with GIT(SCM)


git remote add origin https://github.com/xxx.git

git push -u origin master

git status


git add .





Tutorial 9 : How to use CATLIGHT (Jenkins Build Monitor)


Tutorial 10 : What is Automated Deployment

Tutorial 11 : How to do Automated Deployment
Tutorial 12 : Notifications - How to send Email from Jenkins
Tutorial 13 : What is Pipeline in Jenkins 
Tutorial 14 : How to setup DELIVERY PIPELINE in Jenkins
Tutorial 15 : How to setup BUILD PIPELINE in Jenkins
Tutorial 16 : what is BLUE OCEAN
















Manage Jenkins



