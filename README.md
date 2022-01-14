# REQUIRES ADMIN PRIVILEGES
## StandBy-Memory-Cleaner

Standby Memory Cleaner , Purges the standby memory used by system itself 
This is a RAM cleaner. There are times when programs do not release the memory they used,
but you don’t want to restart the system to get the used memory back.
SAFE TO USE WITH EVERY ANTI- CHEAT 

# USAGE
## Copy 'SMC' to Local Disck C
## Run cmd as adminstrator
Copy and Paste the command given below
``` SCHTASKS /CREATE /ru system /SC MINUTE /TN "Memory Cleaner" /TR "C:\SMC.exe" /MO 5```
