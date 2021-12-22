# yf-packages

# Looking up packages in python (for example)
```py
import requests
import json


result = requests.get("https://raw.githubusercontent.com/JakeRoggenbuck/yf-packages/main/packages.json")
packages = json.loads(result.text)
```
