# SMS Foxbox and smstools3

Instructions on the FoxBox Wiki are wrong or outdated.
You're better of looking at the original SMS Server Tools 3 project than reading FoxBox Wiki.

http://smstools3.kekekasvi.com/


## SMS Delivery Reports

Instructions on the FoxBox Wiki are wrong or outdated.

To enable SMS delivery report with FoxBox 8 Rack you need to add these lines to */etc/smbd.conf*
```
[GSMX]
...
init = AT+CNMI=2,1
report = yes
using_routed_status_report = yes
```
