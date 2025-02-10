# timer

**set your script to run for example every 1 hour on linux**

```crontab -e```
- If it's python:
 ```
  0 * * * * /usr/bin/python3 /path/to/script/example.py
 ```
- If it's Bash
 ```
  0 * * * * bash /root/tradingbot/example.sh
 ```
