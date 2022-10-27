<p href="https://discord.gg/2s59xkx8Yu" align="center">
    <img alt="" src=https://lanyard.cnrad.dev/api/986309129683492894/>

```py
from requests import get

class Answers:
    def __init__(self):
        self.grass = "https://touch-grass.com"

    def request(self):
        req = get(self.grass)
        if req.json()["Toutched_Grass"] == True:
            print("Lying")

        elif req.json()["Toutched_Grass"] == False:
            print("Truth")

    def media(self) -> tuple:
        instagram = "sokisa.dev"
        discord   = "Sokisa#1382"
        discord_server    = "https://discord.gg/2s59xkx8Yu"

        return instagram, discord, discord_server

    def platforms(self) -> tuple:
        projects = ["Tiktok", "Xbox", "Twitch", "Discord"]
        langs    = ["Python"]

        return projects, langs
```





<h3 align="left">Language:</h3>
<a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>


