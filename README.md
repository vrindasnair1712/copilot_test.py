# Copilot Uptime Script

## What Copilot Suggested
When I asked GitHub Copilot to create a script to print system uptime, it generated:

```python
import os
uptime = os.popen("uptime -p").read()
print(uptime)

