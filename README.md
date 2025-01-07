# -China-Unicom-vn009
Find the super admin password for your modem and log in to your super admin account with adb 

1.Switch your vn009 system to version 2.6.0 (the factory version should be 2.5.2)

2.Use this website to calculate your super admin password https://tool.zootu.cn/tools/api/007imei/

3.Enter in terminal:adb connect 192.168.21.1:5555（If you don't have adb download it using the link below）

4.Enter your account and password to debug 

https://developer.android.com/tools/releases/platform-tools
# Change IMEI 

atcmd 'AT+SPACTCARD=0'

atcmd 'AT+SPIMEI?'

atcmd 'AT+SPIMEI=0,"860870063231387"'
 
