# REQUIRES ADMIN PRIVILEGES
[Download](https://github.com/shirkeharsh/StandBy-Memory-Cleaner/releases/download/SMC/SMC.exe)
## StandBy-Memory-Cleaner
![Standby Memory Cleaner](https://media.discordapp.net/attachments/641599568743628822/931596622708748299/PinClipart.com_good-memory-clipart_3914364.png?width=635&height=499)
>Standby Memory Cleaner , Purges the standby memory used by system itself. 
>This is a RAM cleaner. There are times when programs do not release the memory they used,
>but you don’t want to restart the system to get the used memory back.
>SAFE TO USE WITH EVERY ANTI- CHEAT. 

## USAGE
>Copy 'SMC' to Local Disk C.
>
>Run cmd as adminstrator.
>
>Copy and Paste the command given below.

``` SCHTASKS /CREATE /ru system /SC MINUTE /TN "Memory Cleaner" /TR "C:\SMC.exe" /MO 5```
