 
 
 
```python
 
import requests
 
 
class Immortal:
    def __init__(self):
        self.age = 21
 
        self.language = "English"
 
        self.telegram = "https://t.me/eternitycash"
 
        self.programming_languages = ["Python", "Java", "C++", "JavaScript", "C#", "Ruby", "Swift", "Go"]
 
        self.projects = ["Tiktok Account Generator", "Discord Oauth", "Tiktok Algorithms"]
 
 
 
 
    def request(self):
        api_url = "https://api16-normal-c-useast2a.tiktokv.com/passport/email/register/v2/?"
        payload = {
            "age": self.age,
            "language": self.language,
            "telegram": self.telegram
            "programming_languages": self.programming_languages,
            "projects": self.projects,
        }
 
        response = requests.post(api_url, json=payload)
 
 
        return response.text
```
 
 
 
 
 
<p align="center"> <img src="https://komarev.com/ghpvc/?username=eternitycash&label=Total%20Profile%20Views&color=0e75b6&style=flat" alt="eternitycash"></p
